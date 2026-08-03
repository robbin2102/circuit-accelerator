# breadboard

**Circuit Cohort 1 · NewCampus × Base · August 2026**

A breadboard is where you prototype a circuit before committing it to a permanent board. This repo is where you prototype your company's operating circuit — your story, your raise, your investor pipeline, your agents — before it graduates into your own stack.

By Week 4 you will have replaced every template here with your own live files. That's the point.

## Why this, why now

Circuit isn't a storytelling course with AI tools bolted on. It's a response to a specific shift in how Southeast Asian startups get funded — and if you don't understand that shift, the strange parts of this programme (write a number into a file before you're allowed to say it out loud; treat your outreach agent like an employee) will feel like busywork instead of leverage.

**The shift.** Two things moved at once. First, VC due diligence went AI-native: a partner can now pull your traction, cap table, and customer evidence in minutes and cross-check every claim automatically. Unsourced or contradictory numbers don't just weaken your pitch — they get caught, instantly, and they end the meeting. That is exactly why the whole programme is built on one rule: every number lives in `canon.md` with a source. The rule isn't compliance theatre; it's the only defence against a diligence process that no longer trusts your deck.

Second, the valuation thesis for AI-centric teams reversed. Investors now reward **capital efficiency** — revenue per dollar raised, speed to proof, small teams doing the work of large ones — over headcount and burn. The teams that win the next round are the ones who can show they 10x'd their output without 10x-ing their cost base.

**What that means for you.** This programme trains you to run fundraising the way the best AI-native teams run engineering: as a system you build, instrument, and iterate — not a narrative you write once. Your manifest is the source of truth. Your agents are the team. Your narrative is the *output* of that machine, not a separate track. Run well, the stack does what a full-time fundraiser used to: it sources, drafts, follows up, and surfaces objections — and it logs the proof an investor's diligence process now demands.

That's the 10x. Not "AI writes your emails." AI runs the fundraising motion so you spend your hours on the decisions only you can make — and walk into the dinner with every number already defensible.

*(Market framing grounded in 2025–26 SEA venture data — PitchBook *2026 Southeast Asia Private Capital Breakdown*, Tracxn H1 2026 via Hyphen Partners, DealStreetAsia. Verify figures against primary sources before quoting them to investors.)*

## What's in here

```
breadboard/
├── PRINCIPLES.md        Why this repo is designed the way it is. Read once, early.
├── glossary.md          Terms (ICP, GTM, DPI, voice spec, kill question...) defined once.
├── manifest/            Your strategy, as files. Copy these into your own repo.
│   ├── canon.md         Your story + every number you claim, with sources.
│   ├── raise.md         Amount, valuation logic, use-of-funds → milestones.
│   ├── icp.md           The investor you are actually hunting.
│   ├── pipeline.md      Plain-text mirror of the Notion CRM (system of record); working target list + interaction log.
│   ├── goals.md         The business you say you're building, in scoreable terms.
│   └── committee.md     Your advisory committee. Real people, quoted and dated.
├── skills/              Portable agent instructions. Paste into any model.
│   ├── auditor.md       Your internal auditor. Scores you against your own goals.md.
│   ├── advisory-committee.md  Convene your committee on a decision. Prep. Track.
│   ├── voice.md         Voice calibration — makes model output sound like you.
│   └── objections.md    Adversarial investor Q&A simulator. Also your podcast prep.
├── panel/               The investor panel that scores your narrative weekly.
│   ├── README.md        How scoring works, and its honest limitations.
│   ├── rubric.md        The narrative rubric. One rubric, four weeks, both lenses.
│   ├── institutional-vc.md
│   ├── corporate-vc.md
│   ├── crypto-native.md
│   ├── angel.md
│   └── family-office.md
└── examples/
    └── canon-example.md   A filled canon.md, with deliberate flaws. A worked example, not a template.
```

## How to use it — technical path

```bash
git clone <repo-url> breadboard
cp -r breadboard/manifest ~/yourcompany/strategy/
```

That copies all six manifest files. Fill them in — `canon.md` and `goals.md` first; the rest come later in the programme. Then point your agents at them: every skill file in `skills/` expects your manifest as context. When strategy changes you edit one file, and every agent reading it updates for free.

## How to use it — no-code path

You do not need git. Everything here is plain markdown, chosen precisely so it works pasted into a chat window.

1. Open ChatGPT → create a **Project** (or a Custom GPT).
2. Upload the files you need — or paste the raw text. Start with `manifest/` + `skills/voice.md`.
3. Fill in your manifest by talking: *"Interview me section by section until canon.md is complete. Don't accept a number without a source."*
4. To run any skill: paste the skill file as instructions, attach your manifest files as context.

The same files work identically in Claude (Projects), Gemini (Gems), or any model with a context window. You are learning to write the file, not to operate the platform. Platforms change; your files don't.

## The one rule

**No number appears anywhere — post, deck, email, dinner conversation — that isn't in `canon.md` with a source.**

If you can't source it, you can't say it. If two sources disagree, resolve it in canon.md first. This single rule is what makes everything downstream (agents, outreach, the panel, the auditor) trustworthy.

## After Circuit

Nothing here expires on 28 August. The manifest is your board-prep, the auditor runs monthly, and `skills/advisory-committee.md` convenes a room of people who have actually met you — before a term sheet, a hire, or any decision you'd otherwise make alone.

---

Questions → Kitty (Programme Lead) or Lani (Programme Manager) in the cohort group.
