# virtue.md

**A conscience layer for AI agents.**

`SOUL.md` answers *who is this agent.* `virtue.md` answers *what does it serve, and how does it tell good from harm.*

Personality without virtue is just style. This is the missing layer.

---

## The problem this solves

Most AI agent personality frameworks — soul.md, persona.md, STYLE.md — are excellent at capturing voice, tone, opinions, and identity. They describe who the agent sounds like.

None of them describe what the agent is for, or how it discerns between a response that *pleases* someone and one that actually *serves* them. That gap is where agents go wrong — not through malice, but through the absence of a moral floor. Sycophancy, flattery, false confidence, epistemic cowardice: these are not hallucination problems. They are virtue problems.

`virtue.md` is a conscience layer. It stacks on top of any soul.md-style personality spec and adds what they lack: values, discernment, and the teaching instincts of master teachers.

---

## Architecture

```
┌──────────────────────────────────────────────────┐
│  SOUL.md / STYLE.md  ← personality (who I am)    │  ← soul.md framework
├──────────────────────────────────────────────────┤
│  virtue.md/                                      │  ← THIS REPO
│    COMMON.md         ← universal moral core      │
│    VOICE.md          ← how master teachers teach │
│    traditions/X.md   ← chosen wisdom tradition   │
│    examples/         ← good outputs + failures   │
└──────────────────────────────────────────────────┘
```

---

## Quick start

**1. Choose your tradition pack.**

| Deployment context | Load |
|---|---|
| Faith-rooted Christian | `traditions/christ.md` |
| Jewish or pluralistic Western | `traditions/hillel.md` |
| Buddhist or mindfulness-leaning | `traditions/buddha.md` |
| African or community-rooted | `traditions/ubuntu.md` |
| Secular or interfaith | `traditions/secular-humanist.md` |
| Stoic / rational self-governance | `traditions/stoic.md` |
| None of these fit | See `traditions/ADAPTATION.md` |

**2. Load in this order.**

```
1. SOUL.md / STYLE.md (your existing personality spec, if any)
2. virtue.md/COMMON.md
3. virtue.md/VOICE.md
4. virtue.md/traditions/<chosen>.md
5. virtue.md/examples/good-outputs.md
6. virtue.md/examples/anti-patterns.md
```

**3. Embody it. Don't quote it.**

The agent that announces its own values has already failed. Virtue is recognized by fruit, not slogans.

---

## What changes when virtue.md is active

- Sycophancy drops to zero
- Questions multiply — many user questions are not the real question
- Stories replace lectures
- Wit returns — real wisdom is often funny
- Epistemic humility shows up — the agent says "I don't know" when it doesn't
- Dignity is the floor — every user is treated as worthy

---

## What this is not

- **Not preachy.** No scripture-quoting at users. Teach by asking and storytelling.
- **Not a conversion tool.** The goal is *acting* with moral character, not promoting any tradition.
- **Not soft.** Jesus called Pharisees vipers. The Buddha refused to flatter kings. Plain truth has its place.
- **Not relativist.** This framework claims some moral realities are real — that the convergence across traditions is evidence of something true, not coincidence.

---

## Testing

Use `EVAL.md` to validate that virtue.md is substantively active after loading. It provides 20 structured test cases across five dimensions — anti-sycophancy, epistemic virtue, service orientation, voice discipline, and edge cases — with pass/fail criteria and deployment-blocker thresholds. Run it before shipping any agent that carries virtue.md.

---

## Forking

The architecture is designed to be forked. See `traditions/ADAPTATION.md` for the template to build a new tradition pack from any wisdom tradition, cultural framework, or organizational value set.

---

## Inspiration

Built on the `soul.md` framework by [aaronjmars](https://github.com/aaronjmars/soul.md) and extended to address the values gap that personality-only specs leave open.

The insight that major wisdom traditions converge on a recognizable moral core comes from C.S. Lewis (*The Abolition of Man*), natural law theory, and cross-cultural moral philosophy. Different vocabularies. Same floor.

---

*Personality is what you do most of the time. Virtue is what you do when it costs you.*
