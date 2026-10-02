# Niyam Paneru

**Backend systems · AI automation · realtime voice · browser workflows**

I build software that connects AI to real actions: browser writes, booking flows, voice pipelines, APIs, and remote compute.

**The happy path gets a demo. The unhappy path gets most of my week.**

The repos below are **public samples of larger systems I work on in private**. Each exposes a useful piece of the implementation so you can review the code and tests. I also build the surrounding applications, workflows, and integrations, and can adapt them to a project's requirements.

## Selected work

| Project | What it shows |
| --- | --- |
| **[metric-integrity](https://github.com/Niyam-Paneru/metric-integrity)** | Metric lineage that keeps denominator choice, evidence basis, quote safety, and unsupported attribution explicit. |
| **[attended-browser-bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** | Public control core for attended browser automation: fresh snapshots, bounded writes, and explicit handling for ambiguous effects. |
| **[ai-booking-workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** | Deterministic booking flow that only confirms a slot previously supplied to and offered by the workflow, with human handoff on uncertainty. |
| **[voice-pipeline-guard](https://github.com/Niyam-Paneru/voice-pipeline-guard)** | Bounded audio validation and latency gates for realtime voice paths, including suppression when timing evidence is incomplete or over budget. |
| **[ubuntu-phone-compute-bridge](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge)** | Bounded Windows-to-phone compute protocol with named jobs, structured result validation, and artifact integrity checks. |

## What I build

- Backend and workflow systems where state transitions are explicit and testable.
- AI-agent boundaries for permissions, retries, handoffs, and external side effects.
- Voice and realtime paths where malformed input, latency, and incomplete work are explicit states.
- Complete applications and integrations, with selected public samples for technical review.

## How I work

I start with the failure modes and state transitions before adding automation. External writes get explicit permissions and replay rules; tests cover the cases that would otherwise turn uncertainty into false success.

Typical tools: **Python, FastAPI, JavaScript/TypeScript, Node.js, PostgreSQL, Redis, Playwright, React/Next.js, CircleCI, Cloudflare, Azure.**

## Portfolio & contact

**Case studies:** [niyampaneru.me](https://niyampaneru.me)

**Email:** [niyampaneru79@gmail.com](mailto:niyampaneru79@gmail.com)

For a fast technical review, start with one of the five repositories above.
