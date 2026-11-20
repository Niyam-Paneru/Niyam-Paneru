# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and side projects that have a habit of getting bigger than planned.

It usually starts with “this should be simple.” Then a form might have submitted before the browser froze, or a perfectly correct percentage turns out to use the wrong denominator. Suddenly the small experiment has a test suite and a rather long README.

I keep coming back to one question: **did it actually happen?** A timeout doesn't prove failure, and an AI saying “done” isn't evidence.

## A few things you can poke around in

**[reastream](https://github.com/Niyam-Paneru/reastream)** — A tool gave me a **1.26 GB** analysis file. I wanted a few fields. Somehow writing a Rust streaming reader became the *smaller* job. On [one recorded run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md), it kept **6.55 MB** of records without loading the whole thing into memory.

**[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** — A browser agent clicks Submit. The page freezes. Did it submit? Nobody knows. The obvious next move is to click again and accidentally apply for the same job twice. I built the JavaScript write-control core for that awkward moment. The Chrome driver isn't in this public repo.

**[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** — Want a better-looking booking rate without getting any more bookings? Change the denominator. Four bookings can be **28.6%** or **11.8%**, depending on the question. Both calculations are valid; the headlines are not interchangeable.

**[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** — A caller wants 2 PM. The receptionist offered 10 and 11. The polite thing is to help; the *wrong* thing is to invent a 2 PM appointment. This Python state machine knows the difference. It isn't connected to a live calendar.

**[Relic Zero](https://github.com/Niyam-Paneru/relic-zero)** — A one-use invitation chain for a mysterious panda. I could explain why the panda is involved, but that would make this sound more deliberate than it was. The token rules are real; the panda doesn't handle the secrets.

## What keeps pulling me back

**Niyam-AI** is my ongoing private personal-AI project, mainly about memory, evidence, and what happens when an assistant is very sure of something it shouldn't be. **DentSignal** is voice-receptionist and backend work; I published [an older, sanitized Twilio implementation](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence), not the whole current application.

There are more experiments around [memory with two clocks](https://github.com/Niyam-Paneru/temporal-memory-core), [voice responses that arrive too late](https://github.com/Niyam-Paneru/voice-pipeline-guard), and [getting a phone to do the laptop's homework](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge).

Some repositories are standalone tools. Others are small, runnable pieces of bigger private projects. The README should make it clear which is which; a nice screenshot is not an architecture diagram.

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
