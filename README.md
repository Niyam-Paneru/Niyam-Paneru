# Niyam Paneru

**Software developer focused on backend systems, AI automation, realtime voice, and reliable agent workflows.**

I build systems where the hard part is not only making the happy path work, but defining what happens when permissions expire, side effects are ambiguous, latency blows the budget, or the available data cannot support the metric someone wants.

Full private codebases stay private by design. The public repositories below are **small, sanitized proofs derived from project work** so the core behavior can be reviewed quickly without exposing credentials, customer data, or private operational code.

---

## Selected public work

| Repository | What it demonstrates | Architecture / evidence | Verification in repo |
|---|---|---|---|
| **[agent-policy-core](https://github.com/Niyam-Paneru/agent-policy-core)** | Deny-by-default policy for tool-calling agents, expiring permissions, idempotency, ambiguous-effect blocking, and write-time credential redaction. | [architecture](https://github.com/Niyam-Paneru/agent-policy-core/blob/main/docs/architecture.svg) | 28 test cases · CircleCI |
| **[voice-pipeline-guard](https://github.com/Niyam-Paneru/voice-pipeline-guard)** | Bounded audio capture, explicit rejection reasons, fail-closed latency budgets, and metadata-only metrics. | [architecture](https://github.com/Niyam-Paneru/voice-pipeline-guard/blob/main/docs/architecture.svg) | 16 test cases · CircleCI |
| **[human-gated-research](https://github.com/Niyam-Paneru/human-gated-research)** | Evidence-ranked proposals and content-bound human approval before irreversible actions. | [architecture](https://github.com/Niyam-Paneru/human-gated-research/blob/main/docs/architecture.svg) | 14 test cases · CircleCI |
| **[metric-integrity](https://github.com/Niyam-Paneru/metric-integrity)** | Denominator-safe reporting, measured/modelled basis labels, and refusal of unsupported attribution. | [architecture](https://github.com/Niyam-Paneru/metric-integrity/blob/main/docs/architecture.svg) | 14 test cases · CircleCI |
| **[dentsignal-twilio-evidence](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence)** | Sanitized historical Twilio voice, webhook, number-provisioning, callback, SMS, and migration evidence from DentSignal. | [evidence pack](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence) | Source/history pack with private commit provenance |

---

## Stack I use

**Python / FastAPI · JavaScript / TypeScript / Node.js · React / Next.js · PostgreSQL / SQLite · Redis / Celery · Playwright / Puppeteer · CircleCI / GitHub Actions**

I care about verification as much as implementation: tests, explicit failure states, idempotency, bounded side effects, privacy boundaries, observability, and documentation that separates what is proven from what is still unknown.

## Case studies

**[niyampaneru.me](https://niyampaneru.me)** — architecture walkthroughs and case studies from larger private project work, including the problem, system shape, specific repair or implementation, evidence, and limitations.

## Contact

- Website — [niyampaneru.me](https://niyampaneru.me)
- Email — [niyampaneru79@gmail.com](mailto:niyampaneru79@gmail.com)
