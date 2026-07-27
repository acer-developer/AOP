# Baseline Engine — Common to All Three Scenarios

> The **cost base and non-BLR income are identical across all three scenarios.**
> Only BLR revenue (and any BLR-linked one-time cost) changes. This file is the
> shared spine; each scenario file layers BLR revenue on top.

## A. FY27 income — non-BLR blocks (₹ Cr)

| Block | FY27 | Basis |
|-------|-----:|-------|
| Interest Income (FD) | 1.50 | FY26 actual ₹1.48 Cr; corpus ₹26.1 Cr |
| Existing operating Sales | 0.97 | FY27 Q1 actual ₹28.5 L annualised |
| **Non-BLR income** | **2.47** | |

## B. FY27 expense (₹ Cr) — REVISED, bottom-up (27-Jul-2026)

> Rebuilt monthly (see `01_monthly_budget_fy27.md`) from actual payroll run-rate + both
> new hires + RC meeting fees + discrete board-meeting provisioning + one-time IT/branding.
> Consultant fee excluded (not yet confirmed); insurance dropped from base case.

| Component | FY27 |
|-----------|-----:|
| Booked actual (Apr-21 Jul) | 1.23 |
| Rest of July (22-31, est.) | 0.16 |
| Aug-Mar (8 months, bottom-up incl. new hires, RC fees, 3 board meetings, IT + branding one-time) | 3.95 |
| **Total expense (revised)** | **~5.34** |
| *Total expense (old flat model, for reference)* | *5.27* |

## C. Baseline net (BEFORE any BLR revenue)

**Non-BLR income 2.47 − Expense 5.34 = −₹2.87 Cr** operating loss for FY27 (revised from −₹2.80 Cr).

BLR revenue in each scenario reduces this loss.

## D. Cash / runway context — **critical board point**

| Item | ₹ | Note |
|------|--:|------|
| Bank of India FD | 25.00 Cr | ⚠️ **Appears to be the SEBI CRA minimum net-worth (₹25 Cr) — likely LOCKED, cannot be drawn without breaching registration. CONFIRM.** |
| Other Fixed Deposits | 1.11 Cr | Likely drawable |
| Operating bank + petty cash | 0.08 Cr | Drawable |
| **Drawable liquidity (ex-locked corpus)** | **~1.9 Cr** | |

- Net monthly cash burn (no BLR) ≈ **₹23 L/month** (expense − cash income).
- Against drawable liquidity of ~₹1.9 Cr → **~8 months of buffer** before touching the locked corpus, unless BLR revenue and operating Sales scale.
- The ₹25 Cr corpus makes the company **solvent**, but the business is **not yet self-sustaining on operations** — it is cushioned by FD interest. This is the core message the AOP must address.

## E. Parameters to confirm (flow into every scenario)
- [ ] Is ₹25 Cr FD the SEBI net-worth lock? (drives real runway)
- [ ] FD interest rate / whether corpus stays intact
- [ ] BLR revenue inputs (see `assumptions/03_revenue_blr_assumptions.md`)
- [ ] CTC = fully loaded cost? (see `assumptions/01_headcount_payroll.md`)
