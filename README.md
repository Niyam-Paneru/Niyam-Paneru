# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and side projects that have a habit of getting bigger than planned.

Usually it starts with "I wonder if I can do this."

## It was supposed to be a small project.

**[reastream](https://github.com/Niyam-Paneru/reastream)** — I needed a few records from a reverse-engineering result. It gave me **1.26 GB**. Rather than develop a healthier relationship with large files, I wrote a Rust streaming reader. [One measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md) kept **6.55 MB** of records. My laptop appreciated that.

**[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** — There's a wonderful moment after clicking Submit when the page does absolutely nothing and you're left wondering whether you've submitted the form or need to click again. I built a JavaScript control core for that problem: permissions, stale pages and writes with unknown outcomes. The Chrome driver lives elsewhere.

**[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** — Four bookings out of 34 calls: 11.8%. Four out of 14 callers who wanted to book: 28.6%. Four appointments either way, but one of those numbers looks much happier on a slide. This Python module keeps track of what a metric actually measures. The calls are synthetic.

**[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** — A receptionist offers 10 AM and 11 AM. The caller asks for 2 PM.

> **AI:** You're booked!  
> **Calendar:** News to me.

A Python state machine that only creates a booking value for an offered and confirmed slot. No live calendar integration in this repo.

## Other things I could have simply ignored

| Project | How we got here |
| --- | --- |
| [Temporal Memory Core](https://github.com/Niyam-Paneru/temporal-memory-core) | I wanted an AI with a memory. I did not ask for time travel. It separates when a fact was true from when the system learned it. |
| [Voice Pipeline Guard](https://github.com/Niyam-Paneru/voice-pipeline-guard) | A great voice response is less impressive when the caller hung up six seconds ago. Audio validation and timing checks. |
| [Ubuntu Phone Compute Bridge](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge) | My phone has a processor too. I thought it could help out. A Windows-to-phone job controller with result validation, not a hosted compute service. |
| [Relic Zero](https://github.com/Niyam-Paneru/relic-zero) | Somewhere between one-use invitation tokens and state validation, a panda got involved. A game-rules prototype, not an audited security system. |

## And somehow I'm still working on these

**Niyam-AI** is my private personal-AI project. I want it to remember the things that matter, learn from corrections and get better over time. The irony of building an assistant to help with my work and then spending so much of my time working on the assistant has not escaped me.

**Niyam Guard** — I bought a smartphone. The smartphone acquired most of my attention. We're currently renegotiating the terms. I'm building a private Android Device Owner app to make distraction blocking harder to bypass, with recovery mechanisms so I don't accidentally lock myself out of my own phone. Still in development.

## Languages I argue with

Python · TypeScript · JavaScript · Rust · C

And the usual suspects: FastAPI, Node.js, Playwright, PostgreSQL and React.

C is particularly good at reminding me how much I took Python for granted.

---

Some repositories are standalone projects; some are public pieces of larger private ones. I've tried to leave enough code and evidence in each to make it clear what's actually there.

From an earlier project: [DentSignal's Twilio chapter](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence), sanitized historical telephony code, not a deployable receptionist.

[Portfolio](https://niyampaneru.me/) · [More repositories](https://github.com/Niyam-Paneru?tab=repositories) · [Email](mailto:niyampaneru79@gmail.com)
