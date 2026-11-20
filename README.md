# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and side projects that have a habit of getting bigger than planned.

They usually begin with “this should be simple.” Then a page freezes after Submit, a chatbot invents an appointment, or a tool hands me 1.26 GB of analysis when I asked for a few records.

Somehow I've become the person who asks computers for receipts.

## Start somewhere

**[reastream](https://github.com/Niyam-Paneru/reastream)** — I asked a reverse-engineering tool for a little evidence. It handed me **1.26 GB**. That's technically an answer, in the same way dropping a library on someone is a book recommendation. I wrote a Rust streaming reader; [one measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md) kept **6.55 MB** of useful records.

**[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** — An agent clicks Submit. The page freezes. The agent's first instinct is to click again; mine is to prevent an accidental sequel. This JavaScript core tracks permissions and uncertain writes so a timeout doesn't become two submissions. It's the control logic, not the Chrome driver.

**[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** — I discovered an amazing growth hack: turn **11.8%** into **28.6%** by changing the denominator. Zero additional bookings, one extremely pleased dashboard. This Python module makes percentages carry their population and evidence instead of hiring the chart as a publicist. The example uses synthetic calls.

**[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** — The receptionist offers 10 AM and 11 AM. The caller wants 2 PM. A chatbot cheerfully says “Booked!” and leaves reality to sort out the details. My Python state machine refuses to confirm a time it never offered. It does **not** connect to a live calendar.

**[Relic Zero](https://github.com/Niyam-Paneru/relic-zero)** — A one-use secret-invitation chain involving a mysterious panda. The panda handles public relations. JavaScript handles token validation, which is good because the panda has not passed a security audit either.

## The projects that won't leave my desk

**Niyam-AI** is my private personal-AI project. The goal is an assistant that remembers what happened, not a director's-cut version of what happened. **DentSignal** is private voice-receptionist/backend work; the public [Twilio chapter](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence) is sanitized historical code, not the full current receptionist.

I also built [memory with two clocks](https://github.com/Niyam-Paneru/temporal-memory-core) so an assistant doesn't learn something on February 10 and claim it knew on February 5; a [voice timing guard](https://github.com/Niyam-Paneru/voice-pipeline-guard) for brilliant answers that arrive after the caller has gone; and a [phone-compute controller](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge) that refuses to give my phone credit for work my laptop secretly did.

Some repositories are standalone tools. Others are small public pieces of larger private projects. I try to show the part you can actually inspect rather than advertise a spaceship held together by a README.

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
