# Niyam Paneru

Hi, I'm Niyam. I build backends, browser automation, voice systems, and little experiments that have a habit of becoming **very large little experiments**.

The usual sequence is: “This should take an afternoon.” Then I discover a failure case. Then another. Six tests later, the original idea is hiding somewhere under a recovery protocol.

I like software that can answer **“did it actually happen?”** A timeout isn't a failed action, a green test isn't a deployment, and an AI saying “done” isn't a receipt. If the system doesn't know, I'd rather it say so than perform confidence for the audience.

## Choose a rabbit hole

| Project | The problem (and the questionable decision it led to) |
| --- | --- |
| **[reastream](https://github.com/Niyam-Paneru/reastream)** · Rust | A reverse-engineering tool handed me a **1.26 GB** result. I wanted a small part of it, not a second mortgage on my laptop's RAM. A [measured run](https://github.com/Niyam-Paneru/reastream/blob/main/docs/measurements/README.md) extracted **6.55 MB** of records. |
| **[Attended Browser Bridge](https://github.com/Niyam-Paneru/attended-browser-bridge)** · JavaScript | A browser clicks Submit, then freezes. Click again? Maybe you've just submitted twice. This is the write-control core that refuses to gamble on that “maybe.” No Chrome driver in this public repo. |
| **[Metric Integrity](https://github.com/Niyam-Paneru/metric-integrity)** · Python | Four bookings can produce **28.6%** or **11.8%**, depending on what you count. Both calculations are correct. Only one answers the question. The denominator is apparently a character in this story. |
| **[AI Booking Workflow](https://github.com/Niyam-Paneru/ai-booking-workflow)** · Python | A receptionist that won't book 2 PM when it only offered 10 and 11. Revolutionary technology: not making things up. It's a state machine, **not** a connected calendar. |
| **[Temporal Memory Core](https://github.com/Niyam-Paneru/temporal-memory-core)** · Python | A fact can be true on Monday and only learned on Friday. Mixing those up gives your assistant accidental time-travel powers. This module keeps the two clocks separate. |
| **[Relic Zero](https://github.com/Niyam-Paneru/relic-zero)** · JavaScript | A one-use invitation relay starring a mysterious panda. The panda gets lore. The secrets get actual rules. |

## Bigger projects, smaller public windows

**Niyam-AI** is my ongoing personal-AI project: memory, evidence, and learning when to say “I don't know.” **DentSignal** is voice-receptionist/backend work. Its public [Twilio history](https://github.com/Niyam-Paneru/dentsignal-twilio-evidence) is an older, sanitized implementation, not the whole current application.

Other detours include a [voice timing guard](https://github.com/Niyam-Paneru/voice-pipeline-guard) (a late answer is not suddenly punctual because the transcript is good), a [phone-compute controller](https://github.com/Niyam-Paneru/ubuntu-phone-compute-bridge) (the laptop isn't allowed to take credit for the phone's work), and a [research approval gate](https://github.com/Niyam-Paneru/human-gated-research) (approval for one proposal isn't approval for its evil twin).

Some public repos are standalone tools; others are focused pieces of bigger private systems. I try to label that instead of advertising an entire spaceship when the repo contains a very carefully tested door.

## Tools I keep reaching for

Python, FastAPI, JavaScript/TypeScript, Node.js, Playwright, PostgreSQL, React, Rust.

And C, whenever I feel like being personally reminded that memory has consequences.

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
