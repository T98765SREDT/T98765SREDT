# Independent Software Projects

**Haoran Tan** · Japan · [LinkedIn](https://www.linkedin.com/in/haoran-tan-dev/)

This page summarizes three personal software projects. It is not employment history; the code, tests, and documentation behind each point are available in the linked repositories.

## Project overview

**Independent portfolio projects** · August 2026–Present

- Turned three workflow ideas into runnable applications with interfaces, validation, storage or reporting, and automated tests.
- Used Python, JavaScript, SQL/SQLite, HTML/CSS, Git, REST-style APIs, HTTP, and standard testing tools.
- Added validation, error handling, persistence, export logic, retries, and credential redaction where each project needed them.
- Included setup steps, test commands, CI checks, contribution notes, security guidance, and MIT licenses.

## Selected project outcomes

### JobFlow — Full-Stack Job Application Tracker

[Repository](https://github.com/T98765SREDT/jobflow) · Python · SQLite · JavaScript · REST APIs

- Built a full-stack CRUD application for tracking remote roles, follow-up actions, pipeline stages, salary ranges, and search/filter views.
- Kept HTTP routing, validation, and SQLite access in separate modules; validated required values, enum fields, dates, URLs, salary ranges, and payload size on the server.
- Created a responsive browser interface plus automated coverage for validation, persistence, filtering, analytics, static delivery, and API behavior.

### QA Sentinel — API Regression & Quality Monitoring CLI

[Repository](https://github.com/T98765SREDT/qa-sentinel) · Python · HTTP · Concurrency · Test Automation

- Built a dependency-free CLI that runs JSON API test suites concurrently, retries temporary failures, and keeps results in a consistent order.
- Implemented checks for status codes, nested JSON, headers, body contents, and latency budgets; generated secret-safe HTML, JSON, and JUnit XML reports for local use and CI systems.
- Added a deterministic demo API and integration tests that verify report generation, retries, failure behavior, CLI exit codes, and credential redaction.

### EvalForge — Offline-First AI Response Evaluation Dashboard

[Repository](https://github.com/T98765SREDT/evalforge) · [Live demo](https://t98765sredt.github.io/evalforge/) · JavaScript · HTML/CSS · Node Testing

- Built a local-first review workspace for comparing AI or code-review responses on accuracy, relevance, clarity, completeness, and safety.
- Kept scoring and export logic in separate modules, with tests for weighted results, incomplete rubrics, tie thresholds, CSV escaping, and JSON output.
- Designed the frontend for keyboard access, reduced-motion preferences, responsive layouts, searchable local history, and transparent scoring evidence.

## Working style

- Write down the inputs, outputs, and likely failure cases before adding a feature.
- Keep important logic in small functions or modules that can be tested directly.
- Use AI assistance when it is useful, then review the code and run the relevant tests myself.
- Document current limits instead of claiming unfinished features. Authentication, production hosting, monitoring, and multi-user access are future work where noted.
