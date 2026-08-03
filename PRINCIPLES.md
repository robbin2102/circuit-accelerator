# Principles

This documents the thinking behind breadboard — why the workshop series and this repo are designed the way they are. Written for facilitators and for founders who want to know why, not just what.

## 1. Strategy as code

A fundraising strategy that lives in a deck is dead the day after it's presented. A strategy that lives in four plain-text files — canon, raise, ICP, goals — is a **source of truth that the rest of the stack reads**:

- Use-of-funds in `raise.md` decomposes into milestones → milestones become Linear projects → your product roadmap now *derives from* your raise logic.
- Your GTM agent reads its KPI targets from the manifest instead of having them hard-coded.
- Apollo lists and outreach sequences are built from `icp.md`; the outreach agent drafts from `canon.md` + `raise.md`, so every email is automatically consistent with the current narrative.
- The data room indexes against `canon.md`. One number, one source, one place to fix it.

When strategy changes, you edit a file and everything downstream updates. When you onboard a new hire, advisor, or model, you point it at four files. Pivots become diffs.

> **Exception — the CRM layer.** The investor CRM and interaction log are the one deliberate departure from file-first: they live in **Notion as the system of record** (cohort decision, 2026-08). Relationship data needs relational views, shared access, and a warm-intro graph that plain markdown can't give. The strategy files above stay plain-text; only the CRM/pipeline moves to Notion, with `pipeline.md` kept as a mirror for agents that consume plain text.

## 2. The file is the skill, not the platform

Every agent in this repo is a plain markdown file: role, context, worked examples, definition of done. Custom GPTs, Claude Projects, and Gemini Gems all accept the same pasted text. We teach with OpenAI because the cohort has credits, but the durable skill is **authoring context** — writing an instruction file rich enough that any competent model can execute it. Platforms will change under you within the year. Files survive platform shifts; configurations don't. (The investor CRM is the deliberate exception to this — it lives in Notion as the system of record; see §1.)

## 3. Narrative is the output of the machine, not a separate track

Circuit's workshop series is judged on one metric: narrative quality. But we don't teach storytelling and AI tooling as separate subjects. The founder canon *is* the story; the agents are its production and distribution system. Every prompt, pipeline, and agent in this repo exists to generate and circulate an evidenced story. If a tool doesn't make the narrative sharper or travel further, it's not in the stack.

## 4. Evidence discipline: every claim carries its source

The rubric's first axis is claim → evidence → stakes. The repo enforces it structurally: `canon.md` requires a source column on every number, and the one rule ("no number appears anywhere that isn't in canon.md with a source") makes unsourced or contradictory claims impossible to recreate downstream. This isn't compliance theatre — investors at dinner will probe exactly the numbers you're least sure of, and a founder who can cite the provenance of every figure is rarer than a founder with good figures.

## 5. Two lenses: external panel, internal auditor

Quality has two honest measures and they must not be conflated:

- **The panel** (`panel/`) is the external lens — five agents with distinct investor mandates scoring your narrative against what the market actually underwrites. It answers: *would this story survive contact with capital?*
- **The auditor** (`skills/auditor.md`) is the internal lens — one agent, personalised by your own manifest, scoring your week against your own stated goals. It answers: *are you building the company you said you were building?*

The panel can't know your intentions; the auditor can't know the market. Together they cover what a good board does, before you have one.

## 6. Judge agents are directional, not oracular

LLM scoring is noisy. Absolute scores drift; different runs disagree. The design compensates rather than pretends otherwise: every persona anchors to the same written rubric with worked scoring examples; the model version is pinned; the meaningful signal is **week-over-week movement on your own trajectory**, not cross-team rankings; pairwise comparison ("is this stronger than last week's, and why") is weighted over absolute scores; and a human (Kitty/Lani) spot-checks a sample weekly to keep the panel calibrated. Treat panel output as pressure-testing, never as investor prediction.

## 7. Goals must be scoreable or they don't count

The auditor is only as good as `goals.md`, and founders write vague goals when allowed to. The forcing function: if a goal isn't specific enough for an agent to score, it isn't specific enough for an investor either. Same standard, both lenses. "Grow the community" is not a goal. "800 → 2,000 verified traders by 30 Sep, measured weekly at <public dashboard>" is.

## 8. Everyone defines a raise — including teams not raising

A founder who says "we're not raising" without a number has deferred a decision, not made one. Profitable-and-not-eager is a *strong* negotiating position — but only when articulated deliberately: what amount, at what milestone, would change your mind, and what does the business look like if you never take the money? `raise.md` forces that articulation. The output may legitimately be "no raise until X" — encoded, with X defined.

## 9. Depth over coverage; the workshop is the rep

70 minutes, one workflow, drilled to the point of unaided execution. Founders extrapolate breadth themselves in independent build time. Every workshop ends with something *live* — an agent running, a post published, a file committed — because the unit of learning is the shipped artifact, not the understood concept.

## 10. The machine outlives the programme

Every artifact is built to keep running after 28 August: the auditor becomes monthly board-prep, the panel becomes free rehearsal before real investor meetings, the manifest becomes the onboarding doc for every future hire and agent. The test of the programme is not Week 4. It's whether the stack is still running in October.

