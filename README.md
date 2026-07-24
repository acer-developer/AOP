# ACER Credit Rating — FY27 Annual Operating Plan (AOP)

> **Motto:** *Plan from the numbers, not around them.*
> Every figure in this repo is either a **booked actual** from Zoho Books or a
> **clearly-labelled assumption**. Nothing is invented. Where an input is not yet
> confirmed, it is marked `TBD` / ⚠️ so it can never be mistaken for an actual.

This repository is the working model and board pack for the FY27 (Apr-2026 → Mar-2027)
Annual Operating Plan. It is structured around **three BLR-licence scenarios** on a
single shared cost base.

## The three scenarios

| Scenario | BLR licence live | BLR months in FY27 |
|----------|------------------|:------------------:|
| **1** | by 1-Oct-2026 | 6 |
| **2** | by 1-Jan-2027 | 3 |
| **3** | No BLR in FY27 | 0 |

The cost base and non-BLR income are **identical** across scenarios; only BLR
revenue timing changes. See [`model/scenario_comparison.md`](model/scenario_comparison.md).

## Headline (from actuals)

- FD corpus **₹26.1 Cr** (₹25.0 Cr likely SEBI net-worth lock — to confirm)
- FY26 income was **95% FD interest**; operating Sales only ₹8 L
- FY27 Q1 Sales **₹28.5 L** — a real inflection (3.5× all of FY26)
- Common FY27 cost base **₹5.27 Cr** (incl. two new hires, ₹95 L/yr)
- Structural gap for BLR + Sales to close: **₹2.80 Cr**

## Repository structure

```
AOP/
├── README.md                      ← you are here (motto + structure)
├── board/
│   ├── AOP_board_presentation.html ← the board deck (open in any browser; 9 slides, self-contained)
│   ├── 00_executive_summary.md    ← the board-facing one-pager
│   └── acer_vs_peers_reality_check.md ← is ACER's plan acceptable vs peers?
├── research/
│   ├── cra_peer_financials.md     ← peer CRA annual + Q3/Q4 revenue (deep-linked, verified)
│   ├── industry_and_regulation.md ← BLR = RBI-ECAI; SEBI ₹25 Cr net worth
│   └── peer_benchmark_data.csv    ← peer figures as data
├── model/
│   ├── 00_baseline_cost_engine.md ← shared cost + non-BLR income + runway
│   ├── scenario_1_blr_by_oct.md   ← S1: BLR live Oct (6 months)
│   ├── scenario_2_blr_by_jan.md   ← S2: BLR live Jan (3 months)
│   ├── scenario_3_no_blr_fy27.md  ← S3: no BLR this year
│   └── scenario_comparison.md     ← side-by-side + decision framing
├── assumptions/
│   ├── 01_headcount_payroll.md    ← existing payroll + 2 new hires (names withheld)
│   ├── 02_cost_assumptions.md     ← cost base derivation
│   └── 03_revenue_blr_assumptions.md ← BLR revenue INPUTS (⚠️ to confirm)
└── data/
    └── actuals/                   ← source numbers exported from Zoho Books
        ├── 01_pl_summary_by_fy.csv
        ├── 02_monthly_income_expense.csv
        ├── 03_income_split_fd_vs_sales.csv
        ├── 04_expense_breakdown_fy27.csv
        ├── 05_payroll_runrate.csv
        └── 06_balance_sheet_cash_fd.csv
```

## How to use

1. Read `board/00_executive_summary.md` for the board narrative.
2. Read `board/acer_vs_peers_reality_check.md` for whether the plan is realistic vs peers.
3. Read `model/scenario_comparison.md` for the scenario side-by-side.
4. Read `research/` for the verified peer + regulatory evidence base (all deep-linked to filings).
5. To finalise numbers, fill the confirmed BLR inputs in
   `assumptions/03_revenue_blr_assumptions.md` — they flow into S1 and S2.

## Peer benchmark headline (verified from filings)

- Smallest established peer (Acuité) earns ~₹55 Cr; Infomerics ₹91 Cr; CARE Ratings ₹360 Cr; CRISIL Ratings ₹909 Cr. **ACER's ~₹1 Cr operating revenue is ~2% of the smallest peer** — true inception stage.
- Profitable CRAs spend **43–54% of revenue on people and still earn 27–56% margins**. ACER's payroll is ~360% of its operating revenue today — a deliberate pre-BLR investment.
- **"BLR licence" = RBI ECAI accreditation**, required *separately* after SEBI registration before banks can use ACER's bank-loan ratings. This is the swing factor across the three scenarios.
- **Verdict:** strategy is sound and industry-validated (BLR-led is exactly how small CRAs scale); FY27 is unavoidably an investment year; the ₹95 L hire bet is acceptable *conditional on BLR timing*.

## Data provenance

All actuals sourced from **Zoho Books Analytics** workspace, joining the
*Accrual Transactions* and *Accounts* tables (P&L base type = Income / Expense),
as of **~21-Jul-2026**. FY convention = Indian fiscal year (Apr → Mar).

## Open items before the board pack is final
- [ ] BLR per-mandate revenue + volume ramp
- [ ] Confirm ₹25 Cr FD = SEBI CRA minimum net-worth (locked)
- [ ] Confirm quoted CTC is fully-loaded cost
- [ ] Any BLR one-time set-up cost / FY27 capex
