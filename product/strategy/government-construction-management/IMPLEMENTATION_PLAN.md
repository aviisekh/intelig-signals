# Implementation Plan

## Phase 1: Product Foundation

- Finalize product strategy docs from meeting notes.
- Design the initial ERD and table responsibilities.
- Identify RLS boundaries and assignment-based access rules.
- Define MVP workflow slices.

## Phase 2: Database Baseline

- Create Supabase migrations for organizations, memberships, projects, sites, assignments, daily reports, attendance, materials, evidence, and reviews.
- Add explicit foreign keys, indexes, check constraints, and RLS policies.
- Seed local development data for one government office, one contractor, one engineer, one supervisor, and two project sites.

## Phase 3: App Shell

- Scaffold Next.js app with strict TypeScript.
- Configure Supabase auth and environment handling.
- Create role-aware navigation and workspace layout.
- Build dashboard, project list, and project detail read models.

## Phase 4: Supervisor MVP

- Build mobile-first daily report creation.
- Add labor attendance entry.
- Add material movement entry.
- Add evidence upload metadata.
- Submit reports for engineer review.

## Phase 5: Engineer MVP

- Build review queue.
- Add report detail review screen.
- Support accepted, rejected, and needs revision decisions.
- Add dashboard indicators for missing reports, blockers, and recently submitted reports.

## Phase 6: Verification

- Add Playwright tests for supervisor report submission and engineer review.
- Verify RLS with cross-organization access tests.
- Run lint, typecheck, and e2e before release.

## Two-Week MVP Target

- Week 1: database, auth, app shell, project/site dashboard.
- Week 2: daily reports, labor, materials, evidence metadata, review queue, e2e coverage.
