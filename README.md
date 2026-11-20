# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and side projects that have a habit of getting bigger than planned.

It usually starts with “this should be simple.” Then a form might have submitted before the browser froze, or a perfectly correct percentage turns out to use the wrong denominator. Suddenly the small experiment has a test suite and a rather long README.

I keep coming back to one question: **did it actually happen?** A timeout doesn't prove failure, and an AI saying “done” isn't evidence.

## A few places to start

**[reastream](https://github.com/Niyam-Paneru/reastream)** — A reverse-engineering tool handed me a **1.26 GB** analysis file. I only needed part of it, so I wrote a Rust streaming reader. In [one measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md), it kept **6.55 MB** of records. My laptop appreciated the restraint.

**[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** — A browser clicks Submit, then freezes. Clicking again might submit the same thing twice. This JavaScript core tracks permissions and uncertain writes rather than guessing. The browser driver isn't in this public repo.

**[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** — Four bookings out of 14 interested callers is **28.6%**. Four out of all 34 calls is **11.8%**. Same bookings, different story. No extra appointments needed to change the headline.

**[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** — A Python state machine that won't confirm a time it never offered. It isn't connected to a real calendar; it just refuses to invent appointments.

**[Relic Zero](https://github.com/Niyam-Paneru/relic-zero)** — A one-use invitation chain built around a mysterious panda. Yes, there's a panda. No, the panda isn't in charge of the secrets.

## The projects behind the smaller experiments

**Niyam-AI** is my ongoing private personal-AI project, especially memory, evidence, and knowing when not to guess. **DentSignal** is voice-receptionist and backend work; the public [historical Twilio code](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence) shows an older implementation, not the current full app.

Other public pieces include [temporal memory](https://github.com/Niyam-Paneru/temporal-memory-core), [voice timing](https://github.com/Niyam-Paneru/voice-pipeline-guard), and a [phone-compute protocol](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge).

Some repositories are standalone tools. Others are small, runnable pieces of larger private projects. I'd rather make that clear than claim the whole application is sitting in a single README.

## Tools I keep reaching for

Python, FastAPI, JavaScript/TypeScript, Node.js, Playwright, PostgreSQL, React, Rust.

Also C, whenever I want the computer to remind me that memory has consequences.

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python" width="36" height="36" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" width="36" height="36" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="36" height="36" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" width="36" height="36" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="36" height="36" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" title="React" width="36" height="36" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" alt="Rust" title="Rust" width="36" height="36" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" title="C" width="36" height="36" />
</p>

[Case studies](https://niyampaneru.me/) · [All repositories](https://github.com/Niyam-Paneru?tab=repositories) · [Email](mailto:niyampaneru79@gmail.com)
