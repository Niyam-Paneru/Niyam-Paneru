# Niyam Paneru

**Backend systems · AI automation · voice/realtime · reliable agent workflows**

I build software that connects AI to real actions: browsers, calendars, voice pipelines, APIs, and remote compute.
The common thread is explicit state, bounded permissions, and failure handling that does not quietly turn uncertainty into success.

## Selected work

| Project | What it shows |
| --- | --- |
| **[agent-policy-core](https://github.com/Niyam-Paneru/agent-policy-core)** | Deny-by-default tool policy with expiring grants, effect-state checks, idempotency, and redacted audit evidence. |
| **[attended-browser-bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** | Public control core for attended browser automation: fresh snapshots, bounded writes, and explicit handling for ambiguous effects. |
| **[ai-booking-workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** | Deterministic booking flow that only offers provider-backed slots, confirms the selected slot, and hands off when confidence is low. |
| **[voice-pipeline-guard](https://github.com/Niyam-Paneru/voice-pipeline-guard)** | Bounded audio validation and latency gates for realtime voice paths, including suppression when completion timing is unknown or over budget. |
| **[ubuntu-phone-compute-bridge](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge)** | Windows-to-Android/Ubuntu job execution with a fixed job registry, structured results, and artifact integrity checks. |

## What I build

- Backend and workflow systems where state transitions are easy to inspect.
- AI-agent boundaries for permissions, retries, handoffs, and external side effects.
- Voice and realtime paths where latency, malformed input, and incomplete work are explicit states.
- Small public proof repositories that expose the mechanism without publishing credentials, personal data, or private operational details.

## How I work

Start with the failure that matters, build the smallest useful proof, try to break it, then widen the system only when the evidence supports it.
I treat retries, timeouts, stale state, and human handoff as engineering behavior—not cleanup work after the demo.
When uncertainty cannot be resolved safely, I prefer a bounded stop over a confident guess.

Typical tools: **Python, FastAPI, JavaScript/TypeScript, Node.js, PostgreSQL, Redis, Playwright, React/Next.js, CircleCI, Cloudflare, Azure.**

## Portfolio & contact

**Case studies:** [niyampaneru.me](https://niyampaneru.me)  
**Email:** [niyampaneru79@gmail.com](mailto:niyampaneru79@gmail.com)

For a fast technical review, start with one of the five repositories above; each is designed to make the control flow and failure boundary inspectable.
