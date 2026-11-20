# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and side projects that have a habit of getting bigger than planned.

## Start somewhere

**[reastream](https://github.com/Niyam-Paneru/reastream)** — I asked a reverse-engineering tool for a small piece of evidence. It gave me **1.26 GB**. Apparently we disagree on the meaning of *small*. I wrote a Rust streaming reader to extract what mattered: **6.55 MB** of records in [one measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md). My laptop appreciated the compromise.

**[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** — An agent clicks Submit. The page freezes. The agent wants to click again. That's how one mysterious timeout becomes two very real submissions. This JavaScript core tracks permission and uncertain writes so “try again” isn't the default. It's the control logic, not the Chrome driver.

**[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** — I turned a booking rate of **11.8%** into **28.6%** without getting a single extra booking. Please don't hire me as a growth hacker. The trick is a different denominator; this Python module makes reports say which population they're measuring. The example uses synthetic calls, not client results.

**[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** — A caller asks for 2 PM. The receptionist only offered 10 AM and 11 AM. An enthusiastic chatbot says “Booked!” The calendar, which has never met this appointment, has questions. This Python state machine only creates a booking value for an offered and confirmed time. There's no live calendar integration here.

**[Relic Zero](https://github.com/Niyam-Paneru/relic-zero)** — A secret invitation passes from person to person, each leaving a mark on a mysterious panda. The panda is head of security in name only. JavaScript handles the one-use tokens and state checks; it's a rules prototype, not an audited public game.

## The projects I keep coming back to

**Niyam-AI** is my private personal-AI project. Some assistants have an impressive memory for things that never happened. I'm working on making mine remember the useful real stuff, learn from corrections, and admit when it doesn't know.

**DentSignal** is private voice-receptionist and backend work. I published [the old Twilio chapter](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence) as sanitized historical code you can inspect, not as a claim that the whole current receptionist is public.

There are smaller experiments too: [temporal memory](https://github.com/Niyam-Paneru/temporal-memory-core), where February 10 knowledge isn't allowed to sneak into February 5; a [voice timing guard](https://github.com/Niyam-Paneru/voice-pipeline-guard) for good answers that arrive after the caller has left; and a [phone-compute controller](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge) that refuses to give my phone credit for work it didn't do.

Some repos are complete small tools; others are public pieces of bigger private projects. I try to make that distinction clear. The README can be ambitious; the code still has to show up.

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
