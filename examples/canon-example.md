# canon.md — Tala Rails (WORKED EXAMPLE)

> **This is a worked example, not a template.** The blank template is `manifest/canon.md`.
> Tala Rails is fictional. Every number here is invented.
>
> **It contains deliberate flaws.** Four of them, seeded so the skill files have something
> real to catch. If you run `skills/objections.md` or `skills/auditor.md` against this file
> and they don't find them, the skill file is the problem — not you. Answers at the bottom.
>
> **Voice spec and Follow-up drafts are deliberately empty.** Those are what module 1.3
> produces. Fill them by running the module against this file.
>
> Last updated: 2026-08-03 by Marisol Bautista

## Identity

- **Company:** Tala Rails
- **One-liner:** Stablecoin payout rails for Philippine BPO freelancers who get paid late.
- **Founded:** 2025-03 · **Entity:** SG Pte Ltd (Philippine branch in registration)
- **Founders of record:** Marisol Bautista (CEO), Dan Ocampo (CTO)
- **Base ecosystem relationship:** Built on Base. Mainnet since Jan 2026. Not in the Ecosystem Fund portfolio — applied Feb 2026, no decision yet.

## Origin story

I spent four years running payroll ops for a 900-seat BPO in Ortigas. Every second Friday I'd get the same message from the same people. Not "where's my money" — they were too polite for that. It was always "ma'am, just checking po."

The money existed. It was sitting in a correspondent bank somewhere between Delaware and Makati, taking four days to clear, and there was nothing I could do except apologise. I built a spreadsheet to predict which payouts would be late so I could warn people first. That spreadsheet is why I'm here.

We launched Tala Rails in March 2025. We've moved over $3M for nearly 2,000 earners, and the money lands in under a minute instead of four days. I still know about forty of them by name. Anyway — that's the whole thesis: the rails were never built for the people doing the work.

## Founder edge

Four years inside BPO payroll operations, not adjacent to it. I know which finance directors sign off on a rails change and which ones need their COO to ask first, because I was the one drafting the memo.

Pigment profile: highest measured strengths are operational sequencing and conflict-tolerant negotiation; lowest is sustained solo analytical work. What this company needs right now is someone who can sit in a BPO CFO's office and not blink — that's the top of my profile. The analysis I should delegate, and Week 2 is where I'll build for it.

Dan built the settlement engine at a remittance startup that processed $40M/yr [self — his prior employer's public press release, not independently verified]. He has shipped this exact system before, at ten times our current volume.

## Traction — the numbers table

| Claim | Number | As of | Source | Notes |
|---|---|---|---|---|
| Total volume processed | $2,410,880 USD | 2026-07-31 | [platform] | Since mainnet launch Jan 2026 |
| Active earners | 1,840 | 2026-07-31 | [dashboard] | "Active" = received ≥1 payout in trailing 30 days |
| Registered earners | 4,210 | 2026-07-31 | [dashboard] | Includes never-paid signups |
| Net revenue | $21,697 USD | 2026-07-31 | [bank] | 0.9% take rate on volume |
| Payout success rate | 99.2% | 2026-07-31 | [platform] | Failed = returned or unclaimed >72h |
| Median settlement time | 41 seconds | 2026-07-31 | [platform] | p50; p95 is 3m 12s |
| Customer acquisition cost | **OPEN** | — | — | No attribution on signups yet. Closes when we ship UTM tracking — sprint of 2026-08-11. |

**Currency rule:** every money figure states its currency explicitly. USD ≠ PHP ≠ SGD.

## Partnerships & pipeline

| Partner | Status | What it actually is | Source |
|---|---|---|---|
| Cornerstone Outsourcing | SIGNED | 340 seats live, contract to 2027-03 | [contract] |
| Pacific Support Group | SIGNED | 210 seats live | [contract] |
| Aboitiz-backed BPO (NDA) | IN DILIGENCE | Security review, week 3 of 6 | [self] |
| GCash | PROSPECTIVE | Cash-out destination most earners already use. No contact with their BD team yet. | [self] |

## Objection ledger

<!-- The 5 hardest questions an investor could ask you, with your best current answers.
     Feed this to skills/objections.md and update it after every real investor conversation.
     If you don't have a good answer yet, write "OPEN:" and what you'd need to close it.
     KILL QUESTION: the single question you handled worst — skills/objections.md names it
     at the end of every session. Keep it pinned at the top. Re-run until it isn't. -->

**KILL QUESTION:** …

1. **Q:** What stops a BPO's existing bank from just going faster? **A:** Nothing technical. But the bank charges the BPO nothing and charges the worker $8 per transfer, so the bank has no reason to move. We're paid by the BPO, which is the side that actually feels the complaints.
2. **Q:** Your two signed BPOs are 550 seats out of 4,210 registered earners. Where did the rest come from? **A:** OPEN: referral from paid earners, but we can't prove it without attribution. Same blocker as the CAC row.

## Voice sample

<!-- 3 short paragraphs of YOUR unedited writing (a post, an email, a rant).
     This is what skills/voice.md calibrates against. Do not polish it.
     This is the INPUT. The rules derived from it go in "Voice spec" below. -->

honestly the worst part of that job was not the lateness. it was that i knew on tuesday and couldn't say anything until friday. compliance said don't pre-announce a delay because it "creates panic." so you just sit on it.

We got 41 seconds last week. Not "instant" — 41. I keep telling Dan to stop saying instant, because the day it's 90 seconds someone will screenshot it. Say the number. If the number is bad, say the bad number and say what you're doing.

Someone asked me at a meetup whether this is a crypto company. I said it's a payroll company that stopped waiting for banks. She said that's a cop-out answer. Maybe. But I've watched four different teams lose a BPO deal in the first ten minutes by leading with the chain, and I'm not doing that. Anyway.

## Voice spec

<!-- Paste the output of skills/voice.md PHASE 1 here — 8–12 concrete, checkable rules,
     each with an example quoted from your voice sample above. Derived once, in Week 1.
     Every agent you build from Week 2 reads this section, so it governs everything
     they write. Re-derive only if your writing genuinely changes. -->

1. …
2. …

## Follow-up drafts

<!-- The three follow-up messages from skills/objections.md — written once in Week 1, reused
     after every real investor conversation. Drafts, not templates: each leaves a marked gap
     [LIKE THIS] for the thing you only know once the conversation has happened.
     The model writes these for you; you edit them so they sound like you. -->

**Engaged investor** — real interest, a next step exists.

**Polite but cool** — ambiguous interest. Door open, no chasing, one useful thing attached.

**Not an investor, but worth keeping close** — no fit now. A future committee seat or intro source.

---

## The four seeded flaws — facilitator answer key

Don't show this section to founders before they run the module.

1. **Contradiction: $3M vs $2.41M.** The origin story says *"We've moved over $3M"*; the numbers table says **$2,410,880**. This is the one the auditor and the panel should both catch first. It is also the most common real-world version of this failure — the deck number was true once, or was aspirational, and never got reconciled.

2. **Rounding up people: "nearly 2,000" vs 1,840.** Defensible in conversation, indefensible in diligence. Tests whether the model challenges a *soft* number rather than only a hard contradiction.

3. **Vocabulary slippage on partnerships.** GCash is listed **PROSPECTIVE** with *"no contact with their BD team yet"* — but the origin story's framing and the one-liner invite a founder to say "we work with GCash" out loud. `skills/objections.md` §HOW TO PROBE item 4 exists for exactly this.

4. **A number sourced to a press release, presented as track record.** Dan's *"$40M/yr"* is tagged `[self]` and honestly caveated in the table, but the sentence after it — *"at ten times our current volume"* — quietly uses it as proof. Tests whether the model reads the source tag or only the claim.

**Also deliberately present, and correct:** one properly marked `OPEN` (CAC) with a named closing condition and a date, a defined *"active"* window, currency on every money figure, and p50/p95 both stated. Founders should notice that the good rows are as instructive as the bad ones.
