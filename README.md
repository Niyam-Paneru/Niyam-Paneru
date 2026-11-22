# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and side projects that have a habit of getting bigger than planned.

Usually it starts with "I wonder if I can do this."

## Where to dig in

A few of the things that escaped the "this should only take an afternoon" stage.

**[reastream](https://github.com/Niyam-Paneru/reastream)** — I asked a reverse-engineering tool for a few records. It responded with **1.26 GB** of JSON. We clearly had different definitions of "a few." I wrote a Rust streaming reader; [one measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md) kept **6.55 MB** of records. The remaining gigabyte was apparently for emotional support.

**[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** — You click Submit. The page freezes. Was the form submitted? Nobody knows. Now imagine giving an AI a mouse and unlimited optimism. I built the JavaScript control core that checks permissions, stale pages and uncertain writes before it gets another turn. The Chrome driver lives elsewhere.

**[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** — Four bookings out of 34 calls: **11.8%**. Four out of 14 callers who wanted to book: **28.6%**. The receptionist did exactly the same amount of work. The denominator appears to be employee of the month. This Python module makes that distinction explicit. The calls are synthetic, not customer results.

**[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** — A receptionist offers 10 AM and 11 AM. The caller asks for 2 PM.

> **AI:** You're booked!  
> **Calendar:** News to me.

A Python state machine that only creates a booking value for an offered and confirmed slot. No live calendar integration in this repo.

## Other things I could have simply ignored

| Project | How we got here |
| --- | --- |
| [Temporal Memory Core](https://github.com/Niyam-Paneru/temporal-memory-core) | I wanted an AI with a memory. I did not ask for time travel. It separates when a fact was true from when the system learned it. |
| [Voice Pipeline Guard](https://github.com/Niyam-Paneru/voice-pipeline-guard) | The AI finally has the perfect answer. The caller is now making lunch. Audio validation and timing checks to keep late responses from being delivered. |
| [Ubuntu Phone Compute Bridge](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge) | My laptop was doing all the work while my phone was watching YouTube. A Windows-to-phone job controller with result validation. Not a hosted compute service. |
| [Relic Zero](https://github.com/Niyam-Paneru/relic-zero) | One-use invitations, state validation, and a panda with access to absolutely none of the source code. A game-rules prototype, not an audited security system. |

## Currently consuming my free time

**Niyam-AI** is my private personal-AI project. I want it to remember the things that matter, learn from corrections and get better over time. The irony of building an assistant to help with my work and then spending so much of my time working on the assistant has not escaped me.

**Niyam Guard** — I tried blocking distracting apps on my phone. Unfortunately, the person in charge of the blocker was also the person trying to bypass it. Bit of a conflict of interest. I'm building a private Android Device Owner app to make distraction blocking harder to bypass, with recovery mechanisms so I don't accidentally lock myself out of my own phone. Still in development.

## Languages I argue with

Python · TypeScript · JavaScript · Rust · C

And the usual suspects: FastAPI, Node.js, Playwright, PostgreSQL and React.

Python raised me. C is currently explaining everything Python politely left out.

---

Some repositories are standalone projects; some are public pieces of larger private ones. I've tried to leave enough code and evidence in each to make it clear what's actually there.

From an earlier project: [DentSignal's Twilio chapter](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence), sanitized historical telephony code, not a deployable receptionist.

[Portfolio](https://niyampaneru.me/) · [More repositories](https://github.com/Niyam-Paneru?tab=repositories) · [Email](mailto:niyampaneru79@gmail.com)
