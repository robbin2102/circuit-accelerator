# Yieldr — Investment Memo

> Every figure below is sourced in `manifest/canon.md` and `manifest/raise.md` — no number
> appears here that isn't traceable to those files. Generated 2026-08-14 from the current
> manifest. Regenerate when canon.md/raise.md change materially; don't hand-edit numbers here.

## 1. Company

- **Company:** Yieldr
- **One-liner:** The agent stack for onchain funds — verified trading edge, agent-operated vaults.
- **Founded:** November 2025
- **Founder:** Robbin Arora — solo founder
- **Base ecosystem relationship:** Base Batches 002 — Top 5 of 900 projects, Winners Builder Track

## 2. The market thesis

Of the roughly 100M traders in crypto, the top 5% (~5M) have real, provable edge but no
infrastructure to turn it into a fund. What exists today are vaults, not funds — the
strategy-execution layer and the fund-operations layer are both missing, and a trader running a
vault directly is legally messy. Yieldr's answer: an AI agent manages the capital onchain instead,
turning individual trading edge into a fund without the legal and operational overhead of a
human-run one.

## 3. Product & roadmap

Four phases, shipping in sequence:

1. **Quant Agent** *(2026-08-30)* — reads a trader's wallet, grades edge across entry, exit, and
   sizing. Serves both the top 5% (systematizing real edge) and the other 95% (showing where
   they're leaking edge). First product to ship, on existing resources — ahead of this raise.
2. **Quant Terminal** *(Q1 2027, funded by this raise)* — demand/supply signals, agent alerts, and
   top-trader edge tracking across FOMO and pump.fun.
3. **Agent Vaults** — gated to traders who rank top-5% in their protocol or asset class, opening
   once Quant Agent reaches a critical mass of 10,000 traders. 12 vaults already gathering
   commitments ahead of that threshold.
4. **Allocation Agent** — for passive depositors, once 500 vaults are live.

## 4. Traction (as of 2026-08-14)

| Claim | Number | Notes |
|---|---|---|
| AUM live in prediction-market vaults | $100K USD | Scoped to prediction-market vaults — a different product surface than the agent-vault roadmap |
| Agent vaults (waitlist, gathering commitments) | 12 | Not yet live for outside deposits |
| Wallets whitelisted (waitlist) | 500+ | |
| Quant Agent launch date | 2026-08-30 | Wallet-based edge grading tool |
| Genesis prelaunch subscription opens | 2026-08-15 | One-time prepayment locking ~50%-lower Terminal pricing + 1x-2x token reward at TGE. Subscription service period doesn't start until Terminal ships — this is deferred revenue signaling demand, **not** recognized recurring revenue |
| Quant Agent ARR target | $120K ARR run-rate (via $10K MRR) | **Forward-looking target, not actuals** — driven by Genesis signups, which haven't opened as of this writing |

**Partnerships:** Virtuals launchpad relationship in diligence for TGE (self-reported, not yet
independently verifiable); Quant Agent wallet scanning live on Robinhood Chain alongside Base.

## 5. Founder & team

**Founder edge:** CA/CPA (ICAI AIR 32), financial-systems background from KPMG and BCG. Built
deed.so, a Solana dapp letting creators tokenize internet properties — reached $3M in trading
volume, though the team concluded it hadn't found product-market fit and moved on. Real,
disclosed, on-domain crypto-building experience, including a firsthand read on what doesn't work.
Previously founded and scaled an edtech venture to $1M ARR.

**Hiring plan (this raise):** 1 Sr Blockchain Dev, 2 AI Engineers, 1 Full-Stack Dev, 1 Marketing
Manager — 5 hires, Singapore-based, ramping in over 2-3 months post-close. Priced bottom-up
against real Singapore market compensation for 4-5yr-experience hires (NodeFlair, JobStreet, BGC
Group), not assumed.

**On team risk:** sourcing blockchain-specific technical talent without a co-founder to
parallelize recruiting is a genuine bandwidth constraint — distinct from "solo founder" as a
generic red flag, which the founder's operating history (the $1M ARR exit, the deed.so ship) is
real evidence against. The specific, narrower risk is hiring execution speed, not founder
capability. See the risk table (§9) for the second-order risk this created.

## 6. The ask

- **Amount:** $750,000 USD
- **Instrument:** SAFE + token warrant (equity SAFE with a companion warrant for pro-rata token
  allocation at TGE)
- **Valuation / cap:** $12,000,000 USD post-money — benchmarked to Carta's 2025 pre-seed median
  for $500-999K rounds ($12M), deliberately priced at the general-market median rather than the
  AI premium band ($12M-$25M) given the hiring-bandwidth risk above, even though traction is
  unusually concrete for pre-seed
- **Committed so far:** $0 — ground-up raise
- **Target close:** 2026-09
- **Runway:** ~12 months, built bottom-up from the use-of-funds table (§7), not a top-down guess

## 7. Use of funds

| Spend | $ | % | Milestone it buys |
|---|---|---|---|
| Team — 5 Singapore hires + office, hardware, opex | $515,780 | 68.8% | Quant Terminal + Agent Vault infrastructure |
| AI inference — GPT/Claude frontier model API costs | $112,500 | 15% | Agent runs live for beta cohort at scale |
| User acquisition & marketing spend | $112,500 | 15% | Toward the 10,000-trader critical mass Agent Vaults requires |
| Buffer / contingency | $9,220 | 1.2% | — |

Full team-cost sourcing and the outcome milestone (10% Terminal-beta-to-paid conversion, ~$75/mo
ARPU → $450K ARR) are in `manifest/raise.md` §2.

## 8. Milestone chain

This raise gets to **Quant Terminal public beta and $450K ARR**, proving durable PMF beyond the
initial Quant Agent cohort — that traders pay recurring subscription revenue for systematized
edge at scale, not just in an early hand-run cohort. That makes Yieldr fundable at **seed/Series A
($5M target)** by crypto-native and AI-focused institutional VCs who need revenue-backed PMF, not
just a working prototype — or profitable enough that the $450K ARR run-rate reduces urgency to
raise on a tight timeline.

## 9. Risk table

| Risk | Why it matters | Mitigant | Status |
|---|---|---|---|
| Hiring-bandwidth risk | Solo founder sourcing 5 specialized Singapore hires without a co-founder to parallelize recruiting | Founder's operating history: $1M ARR edtech exit, deed.so shipped with $3M volume — real evidence against the generic "solo founder" concern | Open — hiring not yet started |
| $450K ARR milestone rests on unproven assumptions | 10% free-to-paid conversion and $75/mo ARPU for the Terminal don't exist yet as real numbers | Genesis prelaunch prepayment (opens 2026-08-15) is a real, near-term, checkable willingness-to-pay signal — but it's deferred revenue, not recognized ARR, and validates willingness-to-pay, not the specific 10%/$75 assumptions | Open — target, not actual, as of this writing |
| Team was sized to fit the budget, not the engineering need | Cut from 6 to 5 hires after Singapore salary research showed the original plan cost 88-95% of the raise | None yet — flagged directly; may need a bigger raise or a later hire funded by early revenue if the Terminal build needs a 2nd blockchain or full-stack engineer | Open — watch item |
| deed.so didn't reach product-market fit | Founder's most direct prior crypto-building experience ended without PMF | Disclosed honestly rather than hidden; the objection is logged as the current kill question | **OPEN per canon.md objection ledger** — no sharp, rehearsed answer yet; needs one before the next investor conversation |
| Partnership claims are self-reported | Virtuals launchpad relationship (TGE path) is currently unverifiable by a third party | Relationship is explicitly logged as "in diligence," not claimed as closed | In diligence |
| Exit-path dilution math is directional | The 10x-case and founder-proceeds math (raise.md §4) assumes ~20% dilution at a future $5M raise that hasn't happened | Explicitly labeled directional, not a commitment, in raise.md | Directional only |

## 10. Revenue model

1. **Quant Terminal** — monthly subscription/pay-as-you-go pricing. Genesis prelaunch subscription
   is the first live demand signal, not yet recognized recurring revenue.
2. **Trading agents** — 50bps fee on trades placed off quant-agent alerts.
3. **Agent vaults** — 10% performance fee + 10bps trading fee (Yieldr's platform cut of each
   vault's own fee).

Unit cost to serve scales with inference/compute (15% of this raise); needs a unit-economics pass
once beta usage data exists.

## 11. Exit-path coherence

Realistic routes: strategic acquisition by consumer trading platforms building out
quant/analytics capability, or larger onchain asset managers/exchanges seeking agent-driven fund
infrastructure — alongside a token liquidity path via TGE (Virtuals launchpad, in diligence). At
$12M post-money (6.25% dilution this round) plus an assumed ~20% dilution at a future $5M raise,
founders would hold roughly ~67% after two rounds; on a $50-200M trade-sale exit, founder proceeds
remain meaningful ($33M-$134M pre-tax range). This is directional math on unconfirmed future round
terms, not a commitment (raise.md §4).
