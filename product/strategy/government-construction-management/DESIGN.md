# Design

## Experience Model

The MVP should feel like an operational field tool, not a marketing site. The first screen after login should be the product workspace.

## Navigation

- Dashboard: portfolio status for engineers and contractor administrators.
- Projects: list, filters, and project detail.
- Sites: site-level operational view.
- Daily Reports: report creation, review queue, and history.
- Labor: worker registry and attendance history.
- Materials: material catalog and site movements.
- Evidence: photos and documents linked to daily reports.

## Mobile-First Supervisor Flow

1. Select assigned project site.
2. Start today's daily report.
3. Record work summary and progress percentage.
4. Add labor attendance.
5. Add material received, consumed, and remaining.
6. Attach site photos.
7. Submit report.

## Engineer Review Flow

1. Open dashboard.
2. Scan projects with missing reports, blockers, or delayed progress.
3. Open a daily report.
4. Review labor, materials, progress, notes, and evidence.
5. Accept, reject, or request revision.

## UI Standards

- Use dense, work-focused layouts appropriate for government and contractor operations.
- Avoid landing-page treatment for the app workspace.
- Use semantic HTML landmarks and accessible forms. References: `FE-UX-005`, `FE-UX-011`.
- Show unauthorized actions disabled rather than hidden. Reference: `FE-UX-007`.
- Require confirmation for destructive archive/delete flows. References: `FE-UX-008`, `FE-UX-009`.
- Use semantic color, typography, shadow, spacing, and radius tokens only. References: `FE-DESIGN-001` through `FE-DESIGN-006`.
