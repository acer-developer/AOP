# Cost Base Assumptions (FY27)

> Derived from actual booked expense in Zoho Books, Apr-2026 to 21-Jul-2026, plus new hires.

## 1. Baseline operating expense run-rate (excl. new hires)

| Month (FY27) | Total expense booked |
|--------------|---------------------:|
| Apr-2026 | 36,42,942 |
| May-2026 | 33,03,380 |
| Jun-2026 | 46,26,264 (lumpy month) |
| **Q1 avg** | **~38,57,529 / month** |

**Baseline annualised operating expense ≈ ₹4.6 Cr/year** (before new hires).

## 2. Expense structure (FY27 to date)

Salary is the single largest line (~58% of total). Key fixed/semi-fixed heads:

| Head | FY27 to-date | Nature |
|------|-------------:|--------|
| Salary + PF + Gratuity + ESI + EDLI | ~75,00,000 | Payroll (fixed) |
| Rent | 14,64,980 | Fixed |
| Board Sitting Fees | 5,50,000 | Semi-fixed |
| Professional / Legal | 6,01,112 | Semi-variable |
| Technology (IT, data, subscriptions) | ~5,21,893 | Semi-fixed |
| Travel | 3,69,737 | Variable |
| Regulatory (SEBI/CRA, MCA/ROC) | 1,39,283 | Fixed |
| Depreciation | 1,90,221 | Non-cash |

## 3. FY27 full-year cost projection — REVISED (superseded, see `../model/01_monthly_budget_fy27.md`)

> The flat "9 months × Q1 average" projection below undercounted two things: RC meeting
> fees (not previously modeled) and board sitting fees, which are lumpy/quarterly, not
> evenly spread across months. The monthly budget file rebuilds this bottom-up; this
> section is kept for audit trail only.

| Component | Amount |
|-----------|-------:|
| Q1 actual (Apr-Jun) | 1,15,72,586 |
| Baseline Jul-Mar (9 mo × ~38.6 L) | ~3,47,17,761 |
| **Baseline FY27 (no new hires)** | **~4,62,90,347** |
| + New hires incremental (see headcount) | + 64,27,000 |
| **FY27 total expense (old flat model)** | **~5,27,17,000 (₹5.27 Cr)** |
| **FY27 total expense (revised, bottom-up)** | **~5,34,00,000 (₹5.34 Cr)** — see monthly budget |

> This cost base is **common to all three BLR scenarios**. The scenarios differ only on the **revenue** side (BLR licence timing). Minor scenario-specific cost deltas (e.g. BLR-linked compliance/tech spend) are called out per scenario.

## 4. New cost lines added this pass (from management input, 27-Jul-2026)

| Item | Treatment | Amount | Basis |
|------|-----------|-------:|-------|
| **RC (Rating Committee) meeting fees** | Recurring, monthly | ₹20,000/meeting × 10–12 meetings/month ≈ **₹2.0–2.4 L/month** (mid ₹2.2 L) | Management input. Some meetings carry 2 cases; each meeting draws 3 executor-members away from casework — a capacity cost as well as a cash cost. |
| **Board meetings** | Discrete, per meeting | **₹5.5 L/meeting** (proxy = FY27-to-date booked sitting fees for 1 meeting) ⚠️ confirm exact per-meeting rate with Company Secretary | 3 more meetings in FY27 (Aug-1, then 2 more quarterly — ~Nov, ~Feb), on top of the 1 already booked in the ₹5.5 L to-date figure. **Not previously provisioned as a discrete line** — was being smoothed into the flat monthly average, which understates it since meetings are lumpy, not monthly. |
| **IT infrastructure upgrade** | One-time | **₹3.0 L** | Management input, booked once (Aug) |
| **Branding budget** | One-time, spend window till Dec | **₹2.5 L** (mid of ₹2–3 L range) | Management input |
| **Consultant fee (per case)** | Excluded for now | — | Not yet available; model runs without it. Add once the per-case consultant fee is confirmed — see open item in scenario files. |
| **Insurance** | Dropped from base case | — | Removed per management instruction |

## 5. To confirm with Finance
- [ ] Exact board sitting-fee rate per meeting (currently proxied at ₹5.5 L — may be lower if the booked figure includes committee fees beyond the board meeting itself)
- [ ] Consultant fee per case (still open — excluded from model until provided)
- [ ] Treat Jun-2026 spike as recurring or one-off? (affects run-rate)
