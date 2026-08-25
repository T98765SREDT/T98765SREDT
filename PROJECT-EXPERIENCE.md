# Independent Software Engineering Project Experience

**Haoran Tan** · Japan · [LinkedIn](https://www.linkedin.com/in/haoran-tan-dev/)

This page presents independent project work in a resume-friendly format. It is intentionally scoped to personal software engineering projects and does not represent employment at the linked products.

## Software Engineering Project Developer

**Independent portfolio projects** · August 2026–Present

- Own the complete development cycle for small software products: turn a user workflow into requirements, select an architecture, implement focused modules, test risk-bearing behavior, and document decisions and limitations.
- Build with Python, JavaScript, SQL/SQLite, HTML/CSS, Git, REST-style APIs, HTTP, and automated testing; prefer small, auditable implementations where dependencies do not add product value.
- Treat validation, error handling, data persistence, serialization, retries, and security boundaries as product requirements rather than afterthoughts.
- Publish reproducible repositories with local quickstarts, test commands, CI workflows, contribution guidance, security scope, and MIT licensing.

## Selected project outcomes

### JobFlow — Full-Stack Job Application Tracker

[Repository](https://github.com/T98765SREDT/jobflow) · Python · SQLite · JavaScript · REST APIs

- Built a full-stack CRUD application for tracking remote roles, follow-up actions, pipeline stages, salary ranges, and search/filter views.
- Designed a clear boundary between HTTP routing, centralized validation, and transactional SQLite access; validated required values, enum fields, dates, URLs, salary ranges, and payload size server-side.
- Created a responsive browser interface plus automated coverage for validation, persistence, filtering, analytics, static delivery, and API behavior.

### QA Sentinel — API Regression & Quality Monitoring CLI

[Repository](https://github.com/T98765SREDT/qa-sentinel) · Python · HTTP · Concurrency · Test Automation

- Built a dependency-free CLI that executes declarative JSON API suites concurrently with deterministic ordering, bounded retries, and actionable assertion diagnostics.
- Implemented checks for status codes, nested JSON, headers, body contents, and latency budgets; generated secret-safe HTML, JSON, and JUnit XML reports for local use and CI systems.
- Added a deterministic demo API and integration tests that verify report generation, retries, failure behavior, CLI exit codes, and credential redaction.

### EvalForge — Offline-First AI Response Evaluation Dashboard

[Repository](https://github.com/T98765SREDT/evalforge) · JavaScript · HTML/CSS · Node Testing

- Built a local-first review workspace for comparing AI or code-review responses on accuracy, relevance, clarity, completeness, and safety.
- Isolated scoring and export behavior in pure modules, so weighted verdicts, incomplete rubrics, tie thresholds, CSV escaping, and JSON output are verified without browser automation.
- Designed the frontend for keyboard access, reduced-motion preferences, responsive layouts, searchable local history, and transparent scoring evidence.

## Technical working style

- Break ambiguous requests into explicit data, workflow, and error-handling requirements.
- Keep higher-risk logic observable and testable rather than hiding it inside presentation code.
- Use AI-assisted development as an accelerator, then inspect, test, and take responsibility for the resulting code.
- State trade-offs honestly: these are local-first portfolio products; authentication, production deployment, observability, and multi-user access are documented future work rather than claimed features.
