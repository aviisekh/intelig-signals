# Architecture

## Stack

- Frontend: React with Next.js App Router.
- Backend: Next.js Route Handlers and Server Actions where appropriate.
- Database and auth: Supabase Postgres and Supabase Auth.
- Hosting: Vercel.
- Testing: Playwright for end-to-end workflows.

## Architectural Style

Use vertical slices organized around business capabilities:

- identity-and-access
- project-portfolio
- site-supervision
- daily-reporting
- labor-attendance
- material-logistics
- evidence-management
- report-review

Each slice owns its commands, queries, models, view models, and route-level containers. Shared UI remains domain-agnostic.

## CQRS Boundaries

Commands mutate state:

- CreateProject
- AssignEngineerToProject
- AssignSupervisorToSite
- StartDailyReport
- SubmitDailyReport
- RecordLaborAttendance
- RecordMaterialMovement
- AttachReportEvidence
- ReviewDailyReport

Queries read optimized views:

- EngineerProjectDashboard
- ContractorProjectDashboard
- SiteDailyReportHistory
- DailyReportReviewQueue
- LaborAttendanceByReport
- MaterialLedgerBySite

## Domain Boundaries

- Organization owns tenant membership and access scope.
- Project represents the contract-level construction work.
- ProjectSite represents a physical site under a project.
- DailyReport is the aggregate root for one supervisor's daily submission.
- LaborAttendance, MaterialMovement, and ReportEvidence are children of DailyReport.
- ReportReview records engineer decisions without mutating submitted evidence.

## Data Access

- All tenant-scoped tables include `organization_id` or derive access through a protected parent.
- Supabase RLS policies must enforce organization membership and assignment-based access.
- All foreign keys must have explicit constraints and indexes.
- Money uses `NUMERIC(19,4)`.
- Enum-like values are stored as `VARCHAR` with check constraints.

## Supporting Specs

- `DATA_MODEL.md` defines the initial ERD and table responsibilities.
