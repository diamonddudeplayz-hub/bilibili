# Valuation — What's Priced In

**As of 2026-11-16. ADR US$12.73 / HK$104.10.**
Anchored to authoritative figures (Yahoo): **Market cap US$5.25B, Enterprise Value US$3.07B.**

## The core point: a price target is NOT what's priced in
- **Current price = what the market will pay today.** PT = what an analyst thinks it's worth *if* their EPS forecast *and* target multiple both come true.
- The gap between price (104) and PT (~165–176) is the market saying: *"I don't believe the earnings, or I won't pay that multiple, or I need to be paid to wait for the China risk."*
- The Q3 print (24 Nov) is judged against **consensus estimates** (the EPS bar). The **price** applies a skeptical *multiple* on top. These are **two different dials** — BILI can beat the earnings bar and still be cheap to the PT, because the beat moves `E` while the re-rate of the multiple is a separate, macro-gated event.

## What US$12.73 actually embeds
Net cash is **42% of the market cap** (US$2.18B of US$5.25B). You pay **US$3.07B EV (≈ RMB 20.3B)** for the operating business.

| Metric | On Darren FY27 (11.12) | On consensus FY27 (~8.5) |
|---|---|---|
| Forward P/E (incl. cash) | **7.6x** | 9.9x |
| **Ex-cash P/E** | **4.4x** | **5.8x** |

(For reference: MS 10.9x, JPM 9.7x, HSBC 8.8x on their own FY27 EPS.)

## Reverse-DCF — the China discount in basis points
EV/FCF of ~4–5x implies, if FCF **never grows again**, a discount rate of:
| Basis | EV/FCF | Implied zero-growth WACC |
|---|---|---|
| FY26E FCF 4,000 | 5.1x | **19.7%** |
| FY27E FCF 5,200 | 3.9x | **25.6%** |

Darren's DCF uses **12.2% WACC** → a no-growth business should trade **8.2x** FCF. The market pays ~4–5x.
**→ The market is pricing BILI's cash flows to decline, or applying a ~20% China risk premium.** The ~8pt gap between the market's implied ~20% and a normal ~12% *is* the China discount, quantified. The company isn't priced as broken — the **discount rate on Chinese cash flows** is elevated.

## Bridge from 104 to the PTs = multiple, not earnings
- Price 104 ≈ [street FY27 EPS ~HK$10] × **~10x**.
- PT ~165–176 ≈ the *same* EPS × **~16–18x** (JPM explicitly 16x; HSBC ~17x; MS DCF implies ~18x).
- **The move from 104 to PT is almost entirely the multiple (10x → ~17x) — the re-rate — not the earnings.** The earnings are already roughly in consensus.
- Note: net cash is so large (~HK$42/sh, 42% of cap) that how you treat it swings the target materially; the street PTs appear to haircut it or apply the multiple to a blended figure (16–18x + full net cash on our FX math would give HK$200+).

## Resolution of the paradox
"Priced for pessimism" ≠ "wrong." The ~20% implied discount rate reflects real China risk (VIE, geopolitics, the ex-China-mandate exodus — Western active money still absent per Goldman). So:
- **Downside** protected by the cheapness (4–6x ex-cash) + earnings compounding — you win on `E` even if the multiple stays at 10x.
- **Upside** to the PTs needs the discount to compress (the Goldman southbound re-rate call).
- You're paid to wait either way; you need at least one dial (earnings *or* multiple) to turn, and you have two.

## TODO
- [ ] Formalise reverse-DCF block in the model (implied growth & WACC across a price grid, next to the forward DCF).
- [ ] Re-check FY26 FCF: H1'26 was only RMB 995M (AI capex front-load) — FY26E 4,000 needs ~3,000 in H2. Watch for the DCF floor.
