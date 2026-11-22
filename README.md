# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and side projects that have a habit of getting bigger than planned.

Most of my projects begin with curiosity. Some end with documentation. The rest are still negotiating.

## Where to dig in

Some people go outside when they're bored. I create another repository.

**[reastream](https://github.com/Niyam-Paneru/reastream)** — I asked a reverse-engineering tool for a few records. It responded with **1.26 GB** of JSON. We clearly had different definitions of "a few." I wrote a Rust streaming reader; [one measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md) kept **6.55 MB** of records. My laptop and I have a healthy relationship now. We just needed to set some memory boundaries.

**[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** — I wanted an AI that could use websites on my behalf. Somewhere along the way, I became responsible for supervising its internet privileges. I built the JavaScript control core that checks permissions, stale pages and uncertain writes before it gets another turn. The Chrome driver lives elsewhere.

**[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** — Four bookings out of 34 calls: **11.8%**. Four out of 14 callers who wanted to book: **28.6%**. The business didn't improve, but the spreadsheet experienced tremendous personal growth. This Python module makes that distinction explicit. The calls are synthetic, not customer results.

**[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** — A receptionist offers 10 AM and 11 AM. The caller asks for 2 PM.

> **AI:** You're booked!  
> **Calendar:** News to me.

A Python state machine that only creates a booking value for an offered and confirmed slot. No live calendar integration in this repo.

## Other things I could have simply ignored

| Project | How we got here |
| --- | --- |
| [Temporal Memory Core](https://github.com/Niyam-Paneru/temporal-memory-core) | Keeping track of what happened is hard enough. Keeping track of when you found out what happened is another repository, apparently. It separates when a fact was true from when the system learned it. |
| [Voice Pipeline Guard](https://github.com/Niyam-Paneru/voice-pipeline-guard) | The AI finally has the perfect answer. The caller is now making lunch. Audio validation and timing checks to keep late responses from being delivered. |
| [Ubuntu Phone Compute Bridge](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge) | My phone has multiple CPU cores. For most of its career, they've been used to load the next YouTube video. I felt there was room for professional development. A Windows-to-phone job controller with result validation. Not a hosted compute service. |
| [Relic Zero](https://github.com/Niyam-Paneru/relic-zero) | Everybody's building AI agents. I put a panda in charge of a secret invitation network. We all have different priorities. A game-rules prototype with one-use tokens and state validation, not an audited security system. |

## Currently consuming my free time

**Niyam-AI** — I'm building a personal AI to save myself time. So far, it has discovered a remarkably efficient way to consume it. It's a private project focused on remembering what matters, learning from corrections and getting better over time.

**Niyam Guard** — I wanted to spend less time on my phone, so naturally I started developing an Android application that requires me to spend more time on my phone. I'm building a private Android Device Owner app to make distraction blocking harder to bypass, with recovery mechanisms so I don't accidentally lock myself out of my own phone. Still in development.

## Languages I argue with

Python, TypeScript, JavaScript, Rust and occasionally C, whenever I want the computer to remind me that memory has consequences.

FastAPI, Node.js, Playwright, PostgreSQL and React are in the mix too.

PostgreSQL and I have a relatively healthy relationship. JavaScript and I are working on ours.

---

Some repositories are standalone projects; some are public pieces of larger private ones. I've tried to leave enough code and evidence in each to make it clear what's actually there.

From an earlier project: [DentSignal's Twilio chapter](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence), sanitized historical telephony code, not a deployable receptionist.

Anyway, I was supposed to be working on something else when I wrote this.

[Portfolio](https://niyampaneru.me/) · [More repositories](https://github.com/Niyam-Paneru?tab=repositories) · [Email](mailto:niyampaneru79@gmail.com)
