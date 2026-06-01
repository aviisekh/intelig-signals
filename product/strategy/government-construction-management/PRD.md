# Product Requirements

## MVP Scope

Build the foundation for a government construction management product that digitizes daily site operations. The first implementation should prioritize schema quality, core workflows, and a mobile-first interface.

## Functional Requirements

### Organization and Access

- The system must support government offices and contractor companies as organizations.
- Users must belong to an organization and have a role.
- Engineers must only see projects assigned to them or owned by their government organization.
- Contractor users must only see projects linked to their contractor organization.
- Site supervisors must only submit reports for assigned project sites.

### Project Portfolio

- Engineers must see a dashboard of assigned construction projects.
- Each project must include name, code, government office, contractor, location, contract dates, budget, and status.
- A project may contain one or more physical sites.
- Project status must support planning, active, paused, completed, and cancelled.

### Site Supervision

- Each site must have assigned supervisors.
- Supervisors must create daily reports per site.
- A daily report must capture report date, weather notes, work summary, progress percentage, blockers, safety notes, and submitted status.
- Reports must be reviewable by engineers.

### Labor Attendance

- Supervisors must record worker attendance for a daily report.
- Attendance must track worker, role/trade, presence status, check-in/check-out times when available, and notes.
- Workers must be associated with contractor organizations.

### Material Logistics

- Supervisors must record materials received, consumed, and remaining at the site.
- Materials must support units such as bags, cubic meters, kilograms, liters, pieces, and tons.
- Material entries must reference the daily report and the site.

### Evidence

- Supervisors must attach photo or document evidence to daily reports.
- Evidence must preserve file metadata, caption, uploaded user, and capture location when available.

### Review

- Engineers must review daily reports and mark them accepted, rejected, or needs revision.
- Review decisions must include reviewer, timestamp, status, and optional comments.

## Non-Functional Requirements

- Use React, Next.js, Supabase, and Vercel.
- Use strict TypeScript with no `any` usage. References: `FE-TS-001`, `FE-TS-002`.
- Organize future app code by vertical feature slices. References: `FE-STRUCT-001`, `FE-STRUCT-004`.
- Use PostgreSQL UUID primary keys and timestamp with time zone. References: `DB-PG-001`, `DB-PG-002`.
- Use tenant-scoped Row Level Security on all `organization_id` tables. References: `DB-RLS-001`, `DB-RLS-002`.
- Use parameterized queries and static table references. References: `DB-QUERY-002`, `DB-QUERY-003`.

## MVP Exclusions

- Payment processing.
- Tender/procurement lifecycle.
- Payroll calculation.
- Offline sync conflict resolution beyond durable draft UX.
- Advanced AI analysis.
