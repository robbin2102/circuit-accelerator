# raise.md — Yieldr

> **What this file is:** your raise, encoded. Amount, logic, and the milestone chain that
> justifies it. Your product roadmap derives from §3. Your outreach agent reads §1–2.
> The panel will attack §4 — write it ready to be attacked.
>
> **Not raising right now?** Fill this in anyway — see §5. "No raise until X" is a valid,
> strong answer *only* when X is defined.
>
> Last updated: 2026-08-10 by Robbin

## 1. The ask

- **Amount:** $750,000 USD
- **Instrument:** SAFE + token warrant (equity SAFE with a companion warrant for pro-rata token allocation at TGE — token-side allocation is documented separately, see note under §6)
- **Valuation / cap:** $12,000,000 USD post-money — **and the logic:**
  Benchmarked against Carta's 2025 pre-seed SAFE cap data: rounds of $500–999K carry a median cap of $12M in the general market. AI companies typically price 2–3x above that general benchmark ($12M–$25M pre-seed caps), and crypto-native investor appetite for the agent thesis is elevated right now (Virtuals Protocol ~$5B market cap; GRIFFAIN trading-agent token peaked ~$370M — directional color on narrative heat, not a direct equity comp). We could not find a disclosed equity pre-seed comp for a directly comparable named company (Griffain, Almanak, Giza, Theoriq, HeyAnon) — most raised via token/DAO structures rather than a disclosed SAFE. **$12M sits at the general-market median rather than inside the AI premium band** — a deliberately conservative price given solo-founder execution risk, even though live AUM + Base Batches Top 5/900 traction is unusually concrete for pre-seed and would support pricing higher.
- **Committed so far:** $0 — no signed docs yet. This is a $0-committed, ground-up raise.
- **Target close:** 2026-09
- **Runway this buys:** ~12 months, blended. Current solo-founder burn is $5K/mo; post-close burn rises sharply once the 5-person eng team (§2) is hired. Assuming ~$55–60K/mo average burn once fully staffed, $750K funds roughly 12 months — enough to cover the beta launch + 6-month ARR proof window in §3. **This blended-burn estimate is a placeholder — confirm actual fully-loaded hiring costs (geography, seniority) once offers are being drafted, and update this line.**

## 2. Use of funds → milestones

| Spend | $ | % | Milestone it buys | Proof it produces | Target date | Linear project |
|---|---|---|---|---|---|---|
| Engineering team — 2 blockchain devs, 2 full-stack devs, 1 UI/UX designer | $525,000 | 70% | Ship quant agent + terminal to public beta | Live public beta product + usage dashboard | 2027-02 *(draft — confirm hiring timeline)* | → link |
| Marketing | $112,500 | 15% | Beta user acquisition | 5,000 public beta users signed up | 2027-02 *(draft)* | → link |
| Inference / compute budget | $112,500 | 15% | Agent runs live for beta cohort at scale | Uptime + inference-cost dashboard for quant agent serving beta users | Ongoing from beta launch | → link |
| *(outcome of the above, not a separate spend line)* | — | — | 10% of beta users convert to paid, ~$75/mo avg → $37.5K MRR / $450K ARR | Revenue dashboard, ARR run-rate | 2027-08 *(6 months post-beta, draft)* | → link |

**Note on target dates:** the 2027-02 beta date and 2027-08 ARR date are back-calculated placeholders (5 months to hire+build, then 6 months to the ARR goal per §3) — not yet confirmed against an actual hiring/engineering plan. Update once the team is in place.

## 3. The milestone chain — why this round leads to the next

This raise gets us to **quant agent + terminal public beta launch and $450K ARR**, which proves **early product-market fit for the quant agent — that traders will pay recurring subscription revenue for systematized edge, not just watch a demo** — which makes us fundable at **seed / Series A ($5M target)** by **crypto-native funds and AI-focused institutional VCs who need to see revenue-backed PMF, not just a working prototype** — or profitable enough that the $450K ARR run-rate reduces urgency to raise on a tight timeline.

**Weakest link (self-identified):** the chain assumes a 10% free-to-paid conversion rate and $75/mo average spend on a product that doesn't exist yet. Both numbers are unvalidated assumptions, not evidence — see the Attack My Chain critique below.

## 4. Exit-path coherence (SEA reality check)

- **Realistic exit routes for this company:** Strategic acquisition or investment by consumer trading platforms building out quant/analytics capability (e.g. Fomo, Pump.fun-adjacent trading apps), or by larger onchain asset managers/exchanges seeking agent-driven fund infrastructure. Separately, a token liquidity path exists via TGE (in-diligence relationship with Virtuals launchpad — see `canon.md` Partnerships) — this is a return path for token holders that runs alongside, not instead of, an equity exit.
- **Does the cap table you're building survive that exit?** At $12M post-money (6.25% dilution this round) plus an assumed ~20% dilution at the next $5M raise, founders would hold roughly ~67% and total investor dilution ~33% after two rounds. On a $50–200M trade-sale exit, founder proceeds remain meaningful ($33M–$134M pre-tax range on the low/high ends) — the cap table survives. This is directional math on unconfirmed future round terms, not a commitment.
- **What does the 10x case require to be true?** On $12M invested capital, a 10x outcome requires roughly a $120M+ exit or token valuation. That requires either (a) ARR scaling well beyond the $450K beta milestone — into the $10–20M+ range via the trading-fee and vault performance-fee revenue lines in §7, not subscription alone — or (b) a successful TGE that gives token holders a liquid return path independent of an equity acquirer.

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

1. **Quant terminal** — monthly subscription or pay-as-you-go inference pricing. This is the near-term revenue line the beta-launch ARR milestone (§2/§3) is built on.
2. **Trading agents** — 50 bps fee on trades placed off quant-agent alerts.
3. **Agent vaults (onchain funds)** — 10% performance fee on vault returns + 10 bps trading fee. This is the line closest to the current live product (2 live agent vaults, $100K AUM per `canon.md`).

**Unit cost to serve:** the main variable cost is inference/compute (15% of this raise, §2) — cost scales roughly with active-user count and query volume. At 10x scale (e.g. 50K beta users), inference cost must show operating leverage — via model efficiency, caching, or usage-tiered pricing — or the subscription margin erodes. This isn't modeled yet; needs a unit-economics pass once beta usage data exists.
