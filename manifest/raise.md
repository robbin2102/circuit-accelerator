# raise.md — Yieldr

> **What this file is:** your raise, encoded. Amount, logic, and the milestone chain that
> justifies it. Your product roadmap derives from §3. Your outreach agent reads §1–2.
> The panel will attack §4 — write it ready to be attacked.
>
> **Not raising right now?** Fill this in anyway — see §5. "No raise until X" is a valid,
> strong answer *only* when X is defined.
>
> Last updated: 2026-08-14 by Robbin

## 1. The ask

- **Amount:** $750,000 USD
- **Instrument:** SAFE + token warrant (equity SAFE with a companion warrant for pro-rata token allocation at TGE — token-side allocation is documented separately, see note under §6)
- **Valuation / cap:** $12,000,000 USD post-money — **and the logic:**
  Benchmarked against Carta's 2025 pre-seed SAFE cap data: rounds of $500–999K carry a median cap of $12M in the general market. AI companies typically price 2–3x above that general benchmark ($12M–$25M pre-seed caps), and crypto-native investor appetite for the agent thesis is elevated right now (Virtuals Protocol ~$5B market cap; GRIFFAIN trading-agent token peaked ~$370M — directional color on narrative heat, not a direct equity comp). We could not find a disclosed equity pre-seed comp for a directly comparable named company (Griffain, Almanak, Giza, Theoriq, HeyAnon) — most raised via token/DAO structures rather than a disclosed SAFE. **$12M sits at the general-market median rather than inside the AI premium band** — a deliberately conservative price given the hiring-bandwidth risk in §2, even though the traction on hand (deployed prediction-market AUM, Base Batches Top 5/900, a pre-launch product with a dated ARR target) is unusually concrete for pre-seed and would support pricing higher.
- **Committed so far:** $0 — no signed docs yet. This is a $0-committed, ground-up raise.
- **Target close:** 2026-09
- **Runway this buys:** ~12 months, blended. This is directly derived from the use-of-funds table in §2, not a separate guess: $750,000 total spend over the ~12-month runway window = **~$62.5K/mo average burn**, consistent with the 6-hire plan (5 engineering + 1 marketing) plus 15% inference budget. Current pre-raise solo-founder burn is $5K/mo. **What's still unconfirmed is pacing, not the total:** exact per-role compensation, start dates, and whether all 6 hires begin day one or ramp in over 2–3 months — any of which shifts effective runway at the same total spend. Update this line once offers are being drafted.

## 2. Use of funds → milestones

<!-- 2026-08-14: clarified that Quant Agent itself (launching 2026-08-30, targeting $120K ARR
     run-rate by end of Aug — see canon.md traction table) ships on existing resources, ahead of
     this raise's Sep close. This raise funds the NEXT phases: Quant Terminal, Agent Vault
     infrastructure (gated to top-5% traders per canon.md), and the eventual Allocation Agent —
     not the already-shipping Quant Agent. -->

| Spend | $ | % | Milestone it buys | Proof it produces | Target date | Linear project |
|---|---|---|---|---|---|---|
| Engineering — 2 blockchain devs, 2 full-stack devs, 1 UI/UX designer (5 hires) | $525,000 | 70% | Build Quant Terminal + Agent Vault infrastructure on top of the already-shipping Quant Agent | Live Terminal beta + usage dashboard; Agent Vaults open to top-5% traders | 2027-02 *(draft — confirm hiring timeline)* | → link |
| Marketing — 1 hire + spend | $112,500 | 15% | User acquisition toward the 10,000-trader critical mass Agent Vaults requires (per canon.md origin story) | 5,000 Terminal beta users signed up | 2027-02 *(draft)* | → link |
| Inference / compute budget | $112,500 | 15% | Agent runs live for beta cohort at scale | Uptime + inference-cost dashboard | Ongoing from beta launch | → link |
| *(outcome of the above, not a separate spend line)* | — | — | 10% of Terminal beta users convert to paid, ~$75/mo avg → $37.5K MRR / $450K ARR | Revenue dashboard, ARR run-rate | 2027-08 *(6 months post-beta, draft)* | → link |

**Note on target dates:** the 2027-02 beta date and 2027-08 ARR date are back-calculated placeholders (5 months to hire+build, then 6 months to the ARR goal per §3) — not yet confirmed against an actual hiring/engineering plan. Update once the team is in place.

## 3. The milestone chain — why this round leads to the next

This raise gets us to **Quant Terminal public beta and $450K ARR**, which proves **durable product-market fit beyond the initial Quant Agent launch — that traders will pay recurring subscription revenue for systematized edge at scale, not just in an early, hand-run cohort** — which makes us fundable at **seed / Series A ($5M target)** by **crypto-native funds and AI-focused institutional VCs who need to see revenue-backed PMF, not just a working prototype** — or profitable enough that the $450K ARR run-rate reduces urgency to raise on a tight timeline.

**Weakest link (updated 2026-08-14):** the $450K ARR milestone still rests on a 10% free-to-paid conversion and $75/mo ARPU assumption for the Terminal, which doesn't exist yet. That's now partially de-risked by a real, near-term, checkable data point: a Genesis prelaunch subscription opens 2026-08-15, targeting $10K MRR-equivalent by end of August ($120K ARR run-rate) — as a solo founder, before any of this raise's hires are in place. **Important nuance on what this number actually is:** Genesis subscribers pay once now to lock a price ~50% below eventual public Terminal pricing plus a 1x–2x token reward at TGE; the subscription service period (and Yieldr's revenue recognition) doesn't start until Quant Terminal ships in Q1 2027. So the $120K figure is prepaid/deferred revenue signaling demand, not recurring revenue landing in the bank now — don't present it to investors as equivalent to a live $120K ARR SaaS business. It's still real evidence the willingness-to-pay assumption holds; it does not yet validate the Terminal-specific 10%/$75 numbers, since Quant Agent and Terminal are different products at different price points. **As of this writing the $120K figure is a target, not an actual — update this section the moment real Week 1/Week 4 numbers are in.**

**On team risk:** the hiring plan (5 engineering + 1 marketing in this window) is a genuine bandwidth constraint for one founder — sourcing blockchain-specific technical talent without a co-founder to parallelize recruiting is real, independent of founder quality. That's distinct from "solo founder" as a generic red flag: the founder's operating history (scaled an edtech venture to $1M ARR, shipped deed.so with $3M in volume) is real evidence against the generic version of that concern. The specific, narrower risk is hiring execution speed, not founder capability.

## 4. Exit-path coherence (SEA reality check)

- **Realistic exit routes for this company:** Strategic acquisition or investment by consumer trading platforms building out quant/analytics capability (e.g. Fomo, Pump.fun-adjacent trading apps), or by larger onchain asset managers/exchanges seeking agent-driven fund infrastructure. Separately, a token liquidity path exists via TGE (in-diligence relationship with Virtuals launchpad — see `canon.md` Partnerships) — this is a return path for token holders that runs alongside, not instead of, an equity exit.
- **Does the cap table you're building survive that exit?** At $12M post-money (6.25% dilution this round) plus an assumed ~20% dilution at the next $5M raise, founders would hold roughly ~67% and total investor dilution ~33% after two rounds. On a $50–200M trade-sale exit, founder proceeds remain meaningful ($33M–$134M pre-tax range on the low/high ends) — the cap table survives. This is directional math on unconfirmed future round terms, not a commitment.
- **What does the 10x case require to be true?** On $12M invested capital, a 10x outcome requires roughly a $120M+ exit or token valuation. That requires either (a) ARR scaling well beyond the $450K Terminal milestone — into the $10–20M+ range via the trading-fee and vault performance-fee revenue lines in §7, not subscription alone — or (b) a successful TGE that gives token holders a liquid return path independent of an equity acquirer.

## 5. If not raising now

N/A — actively raising this round (§1).

## 6. Dilution ledger

| Holder | % now | % post-round |
|---|---|---|
| Founders | 90% | 84.375% |
| ESOP | 10% | 9.375% |
| Prior investors | 0% | 0% |
| This round | — | 6.25% |

**Note:** this table covers equity only. The token-warrant component of the instrument (§1) grants investors pro-rata token allocation at TGE — that allocation is tracked separately in future token-allocation documentation and is not reflected in the equity percentages above.

## 7. Revenue model

Three revenue streams, tied to product releases:

1. **Quant terminal** — monthly subscription or pay-as-you-go inference pricing. This is the near-term revenue line the beta-launch ARR milestone (§2/§3) is built on. The Genesis prelaunch subscription (opening 2026-08-15 — one-time prepayment locking a discounted price + token reward, ahead of Terminal's Q1 2027 launch) is the first live read on demand for this line, not yet recognized recurring revenue.
2. **Trading agents** — 50 bps fee on trades placed off quant-agent alerts.
3. **Agent vaults (onchain funds)** — 10% performance fee on vault returns + 10 bps trading fee — Yieldr's platform cut of each vault's own fee (individual vaults may charge depositors more; 10% is what Yieldr takes of that).

**Note:** current live traction ($100K AUM in prediction-market vaults, per `canon.md`) is a different product surface from these three lines — it's evidence of live capital deployment and operational capability, not a direct proof point for the Terminal/trading-agent/vault revenue model above.

**Unit cost to serve:** the main variable cost is inference/compute (15% of this raise, §2) — cost scales roughly with active-user count and query volume. At 10x scale (e.g. 50K beta users), inference cost must show operating leverage — via model efficiency, caching, or usage-tiered pricing — or the subscription margin erodes. This isn't modeled yet; needs a unit-economics pass once beta usage data exists.
