# Niyam Paneru

I build backends, browser automation and voice systems. I particularly enjoy the problems nobody puts in the demo: the button that doesn't respond, the API that says OK and the booking that somehow exists only in the chatbot's imagination.

My favorite error message is the one that actually tells me what went wrong. Rare species.

[Portfolio](https://niyampaneru.me/) · [Email me](mailto:niyampaneru79@gmail.com) · [The entire rabbit hole](https://github.com/Niyam-Paneru?tab=repositories)

## The good stuff

### [reastream](https://github.com/Niyam-Paneru/reastream) — Rust vs. an absolutely unreasonable JSON file

I wanted a few records. A reverse-engineering tool gave me 1.26 GB.

Apparently, asking nicely was not enough. I wrote a streaming reader instead. In [one measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md), it read the full file and kept just 6.55 MB of relevant records.

My laptop and I are still on speaking terms.

### [Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge) — please stop clicking that button.

An agent clicks Submit. Nothing happens. It clicks again. Somewhere, a backend engineer develops a new facial tic.

This is the JavaScript control core that tracks permissions, stale page state and uncertain writes so the agent doesn't turn one timeout into two submissions. The actual Chrome driver isn't in this repo.

### [AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow) — the calendar would like a word

> **AI:** You're booked for 2 PM!  
> **Calendar:** Am I?

A Python state machine that only creates a booking value when the caller selects and confirms a time that was actually offered. No invented availability. No live calendar integration, either.

### [Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity) — how to improve a KPI without doing any work

Four bookings out of 34 calls: **11.8%**. Four bookings out of 14 booking-intent calls: **28.6%**.

Same bookings. Different denominator. Someone's PowerPoint just got a promotion.

I wrote a Python module to make metrics carry their population and evidence. Synthetic calls, not customer results. The numbers are allowed to be exciting; the claims still have to be true.

## Meanwhile, in the lab...

| Project | The problem I couldn't leave alone |
| :--- | :--- |
| [Temporal Memory Core](https://github.com/Niyam-Paneru/temporal-memory-core) | Teaching an assistant that finding something out on February 10 doesn't mean it knew on February 5. No time travel on my watch. |
| [Voice Pipeline Guard](https://github.com/Niyam-Paneru/voice-pipeline-guard) | The world's most brilliant answer is surprisingly useless after the caller hangs up. Audio validation and timing gates. |
| [Ubuntu Phone Compute Bridge](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge) | Giving my phone a job other than displaying videos. A Windows-to-phone job controller with result checks, not a hosted compute service. |
| [Relic Zero](https://github.com/Niyam-Paneru/relic-zero) | A secret invitation, one-use tokens and a panda. Yes, a panda. Rules prototype; the panda has not passed a security audit. |

## The two projects I keep returning to

**Niyam-AI** — My private personal-AI project. I want an assistant that remembers what matters, learns when I correct it and can say "I don't know" without experiencing an existential crisis. Still working on it.

**DentSignal** — Private voice receptionist and backend work. The [old Twilio chapter](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence) is public: sanitized historical telephony code, callbacks and number management. It's an exhibit, not a working public receptionist. Please do not ask the museum for an appointment.

## My relationship with technology

Python for getting things done. TypeScript when JavaScript needs adult supervision. FastAPI, Node.js, PostgreSQL, Playwright and React for building the actual things. Rust for negotiating with memory. C for when I miss negotiating with memory and would rather be personally responsible for it.

## A small house rule

Some of these repositories are small standalone tools; others are public slices of private work. I try to leave enough source, measurements and limitations for you to tell the difference.

A passing test is nice. A reproducible result is better. A screenshot of a green checkmark is not a business model.

Anyway, back to the bug.
