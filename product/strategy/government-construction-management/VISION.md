# Vision

The product becomes the field execution system for public construction projects: supervisors submit accurate daily records from mobile devices, contractors monitor their project obligations, and government engineers review progress with evidence instead of chasing paper updates.

## Product Positioning

Mobile-first construction project management for government contractors and public engineers.

## Primary Users

- Government engineer: oversees assigned projects, reviews daily progress, verifies contractor work, and identifies risk.
- Contractor administrator: manages projects, supervisors, workers, and material flow across active contracts.
- Site supervisor: records daily labor attendance, material logistics, site progress, photos, issues, and remarks from the field.

## Success Criteria

- An engineer can see all assigned projects and understand today who reported, what progressed, and what is blocked.
- A supervisor can submit a complete daily site report from a phone in less than five minutes.
- A contractor can review labor and material history across their active projects.
- Every tenant-scoped record is protected with Supabase Row Level Security.
- The MVP database model supports future web and mobile clients without redesigning core entities.

## Product Principles

- Field-first: the supervisor workflow must work well on mobile screens and poor connectivity.
- Auditability over convenience: important records must preserve who submitted them, when, for which site, and with what evidence.
- Clean domain model first: project, site, contractor, supervisor, worker, attendance, material, report, and evidence are separate concepts.
- Government visibility: engineers need portfolio-level status, not only raw forms.
