# Niyam Paneru

I build software that talks to browsers, APIs, audio pipelines, and occasionally humans. The humans are still the hardest integration.

Mostly **Python, TypeScript/JavaScript, Rust, FastAPI, Playwright, and PostgreSQL**. I like working systems, clear failure states, and logs that don't gaslight the person debugging them.

## Things I've actually built

| Project | What's there to inspect |
| --- | --- |
| **[reastream](https://github.com/Niyam-Paneru/reastream)** · Rust CLI | Read a measured **1.26 GB UTF-16LE analysis file** and kept a **6.55 MB capability index** (19,962 records). Streaming parser, tests, and [benchmark notes](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md). |
| **[Best Tech Solutions website](https://github.com/Niyam-Paneru/bts-website-preview)** · HTML/CSS/JS | Multi-page computer-shop **client preview**: laptop galleries, services, contact, and WhatsApp enquiries. Source is public; launch approval is still pending. |
| **[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** · JavaScript | A runnable **write-control core** for browser automation: permissions, fresh page snapshots, one-write intent ledger, and blocked blind retries. No browser driver in this public repo. |
| **[Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** · Python | A tested **booking state machine** that rejects time slots it never offered instead of confidently confirming fictional appointments. No live calendar integration. |
| **[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** · Python | A small analytics demo where **4 bookings / 14 booking-intent calls = 28.6%**, but **4 / 34 total calls = 11.8%**. Same records, different claims; both calculations carry their evidence basis. |
| **[Voice Pipeline Guard](https://github.com/Niyam-Paneru/voice-pipeline-guard)** · Python | Testable WAV size/format bounds and realtime timing decisions: missing or late processing evidence suppresses output. Synthetic audio, not a live calling service. |

## The larger projects behind some of these experiments

- **DentSignal** — an independent voice-receptionist/backend project. The public [Twilio history pack](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence) shows sanitized earlier call/callback and number-management code; it is **not** the current full app. My [published repair case studies](https://niyampaneru.me/) use synthetic checks and spell out their limitations.
- **Browser Bridge and Niyam-AI** — private browser-control and personal-AI work. Their public building blocks include [agent policy](https://github.com/Niyam-Paneru/agent-policy-core), [temporal memory](https://github.com/Niyam-Paneru/temporal-memory-core), and [human-gated research](https://github.com/Niyam-Paneru/human-gated-research). Those repositories demonstrate specific components, **not** entire deployed products.
- **Learning OS** — experiments in measuring whether practice was independent or assisted. The [public evidence core](https://github.com/Niyam-Paneru/learning-evidence-core) contains the inspectable rules.

## Small engineering obsessions

A timeout is **not** proof a write failed. A passing unit test is **not** proof a service is in production. And a dashboard percentage without its denominator is a decorative number.

That's why the public repositories include runnable behavior tests, synthetic examples, and explicit boundaries. Some are standalone tools; others are deliberately small modules from private projects. Each README says which is which.

If you're curious about the stranger corners: there's a [phone-compute protocol](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge), an [opportunity triage engine](https://github.com/Niyam-Paneru/opportunity-intelligence-core), and [a panda-powered capability relay](https://github.com/Niyam-Paneru/relic-zero). The panda is not in charge of security.

**More:** [Case studies and interactive synthetic checks](https://niyampaneru.me/) · [Email](mailto:niyampaneru79@gmail.com)
