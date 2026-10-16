# Pablo Bessone

## Full Stack Developer · React, TypeScript, Node.js & NestJS

**Frontend-focused, comfortable working across APIs, databases and integrations.** Based in Argentina (UTC−3), building web applications professionally since 2020.

[Portfolio & case studies](https://paablobs.github.io/web-portfolio/en/) · [Portfolio en español](https://paablobs.github.io/web-portfolio/es/) · [LinkedIn](https://www.linkedin.com/in/pablobessone/) · [Email](mailto:pablo.bessone@outlook.com)

I'm open to **full stack, frontend and backend roles**. My experience combines AngularJS modernization, React/TypeScript microfrontends and shared components with NestJS services, REST APIs, SQL and ERP integrations. I've also delivered a production AI chatbot within an existing educational platform.

## Professional experience

### Full Stack Developer · We Are Psh
September 2021 — Present

- Redesign application screens and migrate AngularJS functionality to React and Redux, collaborating with UI/UX on Figma designs and expected behavior.
- Delivered an end-to-end production chatbot within an existing AI-powered educational platform, implementing the chat interface, backend endpoints, model integration, conversation history and streaming.
- Implemented Markdown-defined behavioral guardrails and PII anonymization for student and teacher data. Validated behavior through automated evaluations, adversarial scenarios, manual reviews and feedback, covering inappropriate responses, prompt injection and sensitive-information disclosure.
- Implement and maintain React/TypeScript microfrontends and contribute to the team's shared component library.
- Develop and maintain REST APIs and TypeScript/NestJS services connected to MySQL for user-status information.
- Integrate user events from frontend and backend with Mixpanel for product analytics.
- Configure and maintain CI/CD pipelines for microfrontends and microservices, and troubleshoot Docker containers.

### Full Stack Developer · Futit Services
January 2020 — September 2021

- Integrated Jira with the ERP to synchronize tasks, statuses and worklogs used by the management team.
- Integrated Scaleway with Openbravo/Etendo so server creation could be managed from the ERP.
- Developed frontend functionality for Openbravo WebPOS and worked on e-commerce interfaces and user flows.
- Managed databases and provided direct client support for business application workflows.

## Skills used professionally

- **Frontend:** JavaScript, TypeScript, React, Redux, AngularJS modernization, microfrontends, shared component libraries.
- **Backend & data:** Node.js, NestJS, REST APIs, MySQL, PostgreSQL.
- **Delivery & integrations:** Docker, CI/CD, Mixpanel, Jira, Openbravo/Etendo, Scaleway.
- **Applied AI:** AI / LLM integration, guardrails, PII anonymization, LLM evaluations.

**Applied in personal projects:** Astro, Firestore, Supabase, SQLite/WebAssembly, Web Workers, Web Crypto, Vitest, React Testing Library, Playwright and GitHub Actions. The projects below provide source code and implementation details; these are separate from my professional stack.

## Selected engineering projects

### [Nout](https://github.com/paablobs/Nout) — offline-first notes

Take rich-text notes without an account, with optional Firestore synchronization after signing in.

- **Implementation:** repository adapters for localStorage and Firestore; migration of local notes and folders on sign-in; timestamp-based reconciliation and batched writes.
- **Verification in the repository:** Vitest data-layer tests, Firebase emulator permission/repository tests and Playwright offline-only browser workflows. CI is configured to run lint, format, build and test suites.
- **Tradeoff:** local-first access adds migration and sync complexity. Timestamp-based reconciliation is not collaborative text merging or a guarantee against every network failure.

[Live app](https://nout.it) · [Case study](https://paablobs.github.io/web-portfolio/en/projects/nout/)

### [Nimvo](https://github.com/paablobs/nimvo) — local-first personal finances

Track monthly income and expenses in a password-protected `.nimvo` file, without accounts or a remote database.

- **Implementation:** SQLite/WebAssembly inside a Web Worker, typed operations, domain repositories and versioned migrations. Amounts use integer cents; file exports use Web Crypto (AES-256-GCM and PBKDF2).
- **Verification in the repository:** unit/component tests for calculations, persistence and encrypted containers; Playwright flows for Chromium and Firefox, file handling, keyboard navigation and basic accessibility checks.
- **Tradeoff:** users control saving and backups. No built-in sync or password recovery; a loaded tab works without a network connection, but reloading still requires the host. Automated tests are not an independent security audit.

[Live app](https://paablobs.github.io/nimvo/) · [Case study](https://paablobs.github.io/web-portfolio/en/projects/nimvo/)

### [Sabotetris](https://github.com/paablobs/sabotetris) — chaos effects & global rankings

A Tetris-style game with escalating chaos effects, softcore/hardcore modes, and separate local and global rankings.

- **Implementation:** React and Excalibur.js/TypeScript, with Supabase anonymous auth, Edge Functions and PostgreSQL for online runs and leaderboards.
- **Verification in the repository:** ranking regression tests, storage/offline failure cases, PostgreSQL tests and Edge Function type checks. Submission validation, request limits and idempotency reduce abuse and duplicates.
- **Tradeoff:** scores are client-calculated, so the leaderboard is not authoritative or cheat-proof. Online runs must be prepared before gameplay; this is not opponent-to-opponent multiplayer.

[Live app](https://paablobs.github.io/sabotetris/) · [Case study](https://paablobs.github.io/web-portfolio/en/projects/sabotetris/)

### [Web Portfolio](https://github.com/paablobs/web-portfolio) — bilingual, statically rendered

Astro renders React sections to HTML without client-side React hydration. English/Spanish routes include localized metadata and equivalent-page language links. Vitest and generated-HTML checks cover navigation, links, case studies and sitemap output.

[Live site](https://paablobs.github.io/web-portfolio/) · [Case study](https://paablobs.github.io/web-portfolio/en/projects/web-portfolio/)

Additional UI project: [What Day Is Next?](https://github.com/paablobs/whatdayisnext).

## What I bring to a team

- Experience connecting UI changes with backend services and existing business workflows.
- Frontend modernization and shared-component work, not just isolated screens.
- Personal projects with documented technical decisions, automated checks and explicit limitations.

For a role involving React/TypeScript interfaces, backend services or end-to-end features, [let's talk](mailto:pablo.bessone@outlook.com).
