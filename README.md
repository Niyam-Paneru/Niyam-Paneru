# Niyam Paneru

**Backend and AI automation engineer. I build the parts agents skip.**

Most of my work sits in the seams: what an autonomous system is allowed to do, how
it proves it did only that, and what it refuses to claim it knows.

- Policy gates that can only narrow permissions, never widen them at runtime.
- Effects that fail closed — including the ones whose outcome is *unknown*.
- Capture bounds that limit the read, not just the buffer.
- Metrics that carry their denominator, and attribution that is refused rather
  than estimated.

---

## Public work

Each repository is a sanitised extract from private production systems. Zero
runtime dependencies, runs in under a second, and the tests are the argument.

| | Repository | What it demonstrates | Tests |
|---|---|---|---|
| 1 | **[agent-policy-core](https://github.com/Niyam-Paneru/agent-policy-core)** | A deny-by-default gate for tool-calling agents. Exact-origin targeting, permissions that expire after 90 days, and idempotent effects where an *ambiguous* outcome is a block rather than a retry. | 28 |
| 2 | **[voice-pipeline-guard](https://github.com/Niyam-Paneru/voice-pipeline-guard)** | Bounded audio capture and a fail-closed latency gate. An over-budget stage has *failed*, and no measurement at all is also not a pass. | 16 |
| 3 | **[human-gated-research](https://github.com/Niyam-Paneru/human-gated-research)** | Evidence-ranked proposals where every irreversible action needs a human approval bound to a content **digest**, not an identifier — so an approved plan cannot be quietly repointed at a different target. | 14 |
| 4 | **[metric-integrity](https://github.com/Niyam-Paneru/metric-integrity)** | Denominator-safe reporting. Every figure carries its basis; modelled estimates cannot reach a quote; recovered revenue is reported as *unavailable* when no durable join exists. | 14 |

---

## Case studies

**[niyampaneru.me](https://niyampaneru.me)** — ten write-ups covering system
builds and focused repairs. Each pairs the architecture with the specific bug, the
code change, and the honest limit of what the evidence supports.

`Deployed systems stay private. The reasoning does not have to.`

---

## Contact

- Email — [niyampaneru79@gmail.com](mailto:niyampaneru79@gmail.com)
- GitHub — [@Niyam-Paneru](https://github.com/Niyam-Paneru)
