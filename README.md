# Hi, I'm Rahul 👋
### Docs Engineer & Developer Experience (DX) Specialist

I build **Docs-as-Code workflows, contract-first API ecosystems, and resilient developer onboarding experiences**. Rather than treating documentation as static text, I treat it as production software—tested in CI/CD, governed by automated linters, and engineered for sub-5-minute time-to-first-call.

---

## 🛠️ Flagship Portfolio Projects

### 1. [Event Ingestion Quickstart & Throttling Resilience](https://github.com/Sys-tem-guy/event-ingest-quickstart)
> **Focus:** Developer Onboarding, Client Resilience, and Automated Docs Testing  
> **Stack:** Python 3.10+, RFC 6585 (HTTP 429), Requests, GitHub Actions CI, Diátaxis Framework

* **Rapid Time-to-First-Call:** Designed a task-oriented quickstart enabling developers to dispatch batch telemetry payloads within 5 minutes, enforcing Twelve-Factor environment variable consumption and fail-fast credentials validation.
* **Full Jitter Exponential Backoff:** Built an idiomatic retry engine implementing uniform random jitter ($\text{sleep} = \text{uniform\_random}(0, \text{ceiling})$) and dynamic `Retry-After` header precedence, preventing thundering herd stampedes during gateway rate-limiting.
* **Continuous Documentation Testing:** Engineered a GitHub Actions CI workflow executing sample code against live mock endpoints on every commit to eliminate documentation drift.

---

### 2. Modular OpenAPI 3.1 & Idempotency Architecture
> **Focus:** API Governance, Contract-First Design, and Schema Linting  
> **Stack:** OpenAPI Specification 3.1, Spectral CI, JSON Schema, Git

* **Modular Contract Design:** Architected reusable, decoupled OpenAPI components with external `$ref` pointers to ensure clean versioning and team-wide reusability.
* **Automated Governance:** Enforced naming standards, security schemes, and error payload consistency across teams using automated Spectral CI linting rulesets.
* **Distributed Idempotency:** Authored clear developer guides and state machine documentation detailing idempotency-key lifecycles, replay behavior, and race-condition prevention in distributed transaction systems.

---

## 📐 Technical Competencies

```text
┌───────────────────────────┬───────────────────────────┬───────────────────────────┐
│     Docs-as-Code & CI     │       API Contracts       │    Developer Experience   │
├───────────────────────────┼───────────────────────────┼───────────────────────────┤
│ • GitHub Actions CI/CD    │ • OpenAPI 3.0 / 3.1       │ • Time-to-First-Call Opt. │
│ • Spectral Linting        │ • JSON Schema Draft 2020  │ • Client Retry Algorithms │
│ • Git Workflows & PRs     │ • RESTful Best Practices  │ • Distributed Throttling  │
│ • Markdown / MDX          │ • HTTP Status Mechanics   │ • Error State Design      │
│ • Static Site Generators  │ • Idempotency Keys (UUID) │ • Sample Code Testing     │
└───────────────────────────┴───────────────────────────┴───────────────────────────┘
```

---

## 🧭 How I Approach DX & Documentation

1. **Test Every Snippet:** Code samples in documentation must be executed and validated in CI to ensure zero drift between software updates and guide text.
2. **Design for the Failure Path:** Most guides only document `200 OK`. Great DX documents `429 Too Many Requests`, connection timeouts, and state recovery so client integrations don't fail in production.
3. **Task-Oriented Structure:** Using frameworks like Diátaxis to strictly separate Tutorials, How-To Guides, Technical References, and Conceptual Explanations.

---

## 📬 Connect With Me

* **GitHub:** [@Sys-tem-guy](https://github.com/Sys-tem-guy)
* **Target Roles:** API Technical Writer | Docs Engineer | Developer Experience (DX) Engineer
* **Open to:** Full-time, Remote, and Contract Opportunities
