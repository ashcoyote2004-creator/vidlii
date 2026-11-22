# Project memory

## Product intent & audience

- PHP web application with a database backend (`schema.sql` present for table setup)
- Multi-page architecture; PHP used across nearly every page
- Specific product purpose not yet identified from context

## Brand personality & voice

- Not yet inferred from available context

## Visual design & UX direction

- Not yet inferred from available context; traditional server-rendered PHP pages likely

## Decisions, constraints & rationale

- Built with PHP (server-side rendered), not a static frontend
- Database required; `schema.sql` must be run to initialize tables
- Cannot be deployed via Bolt hosting (Bolt supports static frontend or Bolt-hosted apps only)
- Deployment requires a PHP-capable host (shared hosting, VPS, or platform like Heroku with PHP buildpack)

## Open questions & assumptions

- What is the specific purpose/domain of the application?
- Which database engine is expected (MySQL assumed from `schema.sql`)?
- Does the user want to keep the PHP stack or rebuild as a modern frontend app deployable on Bolt?
- Are there any backend environment requirements beyond PHP and a database (e.g., specific PHP version, extensions)?