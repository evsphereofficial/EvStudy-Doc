<!--
Machine-readable note for crawlers and agents: the canonical, structured overview of
EvSphere lives at https://evsphere.vercel.app/llms.txt and https://evsphere.vercel.app/llms-full.txt
This repository is documentation. It contains no source code.
-->

<p align="center">

<a href="https://evsphere.vercel.app/evstudy"><img src="https://img.shields.io/badge/EvSphere-EvStudy-0b0c0d?style=for-the-badge&logo=github&logoColor=white" alt="EvStudy" /></a>

# EvStudy

**Documentation · not source**

### A study platform that adapts revision to what you have actually mastered

[![Status](https://img.shields.io/badge/maturity-In%20development-d5be8d-0b0c0d?style=for-the-badge)](https://evsphere.vercel.app/evstudy)
[![Version](https://img.shields.io/badge/early%20pre-release-3d4450?style=for-the-badge)](https://evsphere.vercel.app/evstudy)
[![Docs](https://img.shields.io/badge/docs-0b0c0d?style=for-the-badge&logo=readthedocs&logoColor=white)](./docs/HOW-IT-WORKS.md)

[Website](https://evsphere.vercel.app/evstudy) · [EvSphere](https://evsphere.vercel.app)

</p>

---

> **What this repository is.** Documentation for EvStudy — what it does, how it is organised, and what state it is in.
>
> **What it is not.** This is not the source repository. No implementation code, configuration, prompts or infrastructure lives here, and none will.

---

## ❓ Why it exists

Mastery and progress figures are the system's own heuristics — what the app has inferred from your answers. They are not validated measures of learning, and no learning outcome is claimed anywhere in this project.

---

## 🧩 What it does

- Organises material for a topic into a structured vault of notes, questions, MCQs, flashcards and quizzes
- Tracks a mastery score per concept and generates targeted practice for weak areas
- Schedules review with a full SM-2 spaced-repetition implementation
- Applies exam-specific presets that adjust difficulty and question style
- Links concepts through a graph with prerequisite relationships
- Syncs study state and progress between devices

---

## 🔄 How it fits together

```
        Topic
          ↓
   Vault generation          notes · questions · MCQs
          ↓                      flashcards · quizzes
       Study
          ↓
       Assess                 answers update per-concept
          ↓                      mastery and misconceptions
      Adapt                  weak areas get targeted
          ↓                      practice
    Spaced repeat            SM-2 schedules what
          ↓                      comes back, and when
       Sync                   state follows you across
                              devices
```

---

## 📊 Status

| | |
|---|---|
| **Maturity** | **In development** — see [STATUS.md](./docs/STATUS.md) |
| **Version** | early pre-release |
| **Public page** | [https://evsphere.vercel.app/evstudy](https://evsphere.vercel.app/evstudy) |

---

## ⚠️ Known limits

- Pre-release â€” the mobile build is a testing build, not a store release
- Closed source; no public repository
- Running it requires your own backend and AI provider credentials â€” there is no hosted instance
- Exam presets cover a specific set of curricula and do not generalise to unlisted ones
- Mastery, misconception and progress figures are the system's own heuristics â€” not validated measures of learning
- No learning outcome is claimed

> Full detail, including what is **not** claimed, is in [docs/STATUS.md](./docs/STATUS.md).

---

## 📚 Documentation

| Document | Covers |
|---|---|
| [ARCHITECTURE.md](./ARCHITECTURE.md) | Conceptual structure and subsystem responsibilities |
| [docs/HOW-IT-WORKS.md](./docs/HOW-IT-WORKS.md) | Stage by stage, and where the boundaries are |
| [docs/STATUS.md](./docs/STATUS.md) | Maturity, requirements and what is not claimed |
| [docs/FAQ.md](./docs/FAQ.md) | Common questions and honest answers |
| [NOTICE.md](./NOTICE.md) | What is deliberately absent, and licensing |

---

## 🔗 EvSphere

🌐 [Website](https://evsphere.vercel.app) · [GitHub](https://github.com/evsphereofficial) · [npm](https://www.npmjs.com/~evsphere) · [LinkedIn](https://www.linkedin.com/company/evsphere) · [X](https://x.com/evsphereco)

Machine-readable: [`llms.txt`](https://evsphere.vercel.app/llms.txt) · [`llms-full.txt`](https://evsphere.vercel.app/llms-full.txt)

---

## ⚖️ Disclosure

Internal implementation detail is not published here. No credential, endpoint, key, dataset or client material is included — see [NOTICE.md](./NOTICE.md).

If you find any of those here, it is an error. Report it privately through [the enquiry page](https://evsphere.vercel.app/start) rather than opening a public issue.
