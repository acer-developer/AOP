# Monthly Budget — FY27 (Bottom-Up, Rebuilt 27-Jul-2026)

> Built from actual Zoho Books payroll run-rate (last 4 booked months) + both confirmed
> new hires + management-confirmed RC fees, IT budget, and branding budget. Consultant
> fee excluded (not yet confirmed). Insurance dropped from base case. Board sitting fees
> moved from a smoothed monthly average to discrete per-meeting provisioning.

## 1. Payroll — actual run-rate (last 4 booked months, from `data/actuals/05_payroll_runrate.csv`)

| Month | Payroll booked |
|-------|---------------:|
| Mar-2026 | 23,82,131 |
| Apr-2026 | 23,85,409 |
| May-2026 | 23,82,454 |
| Jun-2026 | 27,33,224 |
| Jul-2026 | not yet booked (partial month) |
| **Apr-Jun avg (existing team, pre-new-hires)** | **~25,00,362 / month** |

Two new hires, additive from their join dates:

| Hire | Monthly cost | Active from |
|------|-------------:|-------------|
| New Hire A | 3,75,000 | 24-Jul-2026 (joined) |
| New Hire B | 4,16,667 | 01-Aug-2026 (joining) |

**Total payroll run-rate, Aug-2026 onward (existing avg + both hires fully active): ₹32,92,029/month**

## 2. Other recurring opex (rent, professional, travel, admin, tech, regulatory, depreciation — excl. payroll and sitting fees)

Derived from FY27-to-date actuals (`data/actuals/04_expense_breakdown_fy27.csv`), Apr-21Jul:
Total booked (₹1,23,28,026) − payroll-linked (₹74,98,522) − sitting fees (₹5,50,000) = ₹42,79,504 over ~3.7 months
→ **~₹11,56,623/month**

## 3. New cost lines (management input, 27-Jul-2026)

| Item | Type | Amount |
|------|------|-------:|
| RC meeting fees | Recurring, monthly | ₹20,000 × 10-12 meetings ≈ ₹2.0-2.4 L (mid **₹2.2 L/month**) |
| Board meeting sitting fees | Discrete, per meeting | **₹5.5 L/meeting** ⚠️ proxy from FY27-to-date booked figure — confirm exact rate |
| IT infrastructure upgrade | One-time | **₹3.0 L** (booked Aug) |
| Branding budget | One-time (spend window: now-Dec) | **₹2.5 L** (booked Aug for modeling; can be phased) |
| Consultant fee/case | Excluded | Not yet confirmed |
| Insurance | Dropped | Removed from base case |

## 4. Board meeting cadence

3 meetings remain in FY27, quarterly, starting with **Aug-1-2026** (1 meeting already booked in the Apr-21Jul actuals):

| Meeting | Approx month |
|---------|-------------|
| Q1 (already booked in actuals) | Jun/Jul-2026 |
| Q2 | **Aug-1-2026** |
| Q3 | ~Nov-2026 |
| Q4 | ~Feb-2027 |

## 5. Monthly budget, Aug-2026 to Mar-2027 (₹ L)

| Month | Payroll | Other opex | RC fees | Board meeting | One-time (IT+Branding) | **Total** |
|-------|--------:|-----------:|--------:|---------------:|------------------------:|----------:|
| Aug-2026 | 32.92 | 11.57 | 2.20 | 5.50 | 5.50 | **57.69** |
| Sep-2026 | 32.92 | 11.57 | 2.20 | — | — | **46.69** |
| Oct-2026 | 32.92 | 11.57 | 2.20 | — | — | **46.69** |
| Nov-2026 | 32.92 | 11.57 | 2.20 | 5.50 | — | **52.19** |
| Dec-2026 | 32.92 | 11.57 | 2.20 | — | — | **46.69** |
| Jan-2027 | 32.92 | 11.57 | 2.20 | — | — | **46.69** |
| Feb-2027 | 32.92 | 11.57 | 2.20 | 5.50 | — | **52.19** |
| Mar-2027 | 32.92 | 11.57 | 2.20 | — | — | **46.69** |
| **Aug-Mar total (8 mo)** | | | | | | **₹3.95 Cr** |

## 6. Full FY27 total expense (revised)

| Component | ₹ Cr |
|-----------|-----:|
| Booked actual (Apr-1 to Jul-21) | 1.23 |
| Rest of July (Jul-22 to Jul-31, ~10 days, est.) | 0.16 |
| Aug-2026 to Mar-2027 (bottom-up, above) | 3.95 |
| **FY27 total expense (revised)** | **~5.34** |
| *FY27 total expense (old flat-run-rate model)* | *5.27* |

The revised figure is **~₹7 L higher** than the old flat model — RC fees (not previously
modeled, ~₹17-18 L over 8 months) and one-time IT/branding (₹5.5 L) are added, partially
offset by dropping insurance and excluding the (still-unconfirmed) consultant fee.

## 7. What's still open
- [ ] Exact per-meeting board sitting-fee rate (proxied at ₹5.5 L/meeting)
- [ ] Consultant fee per case — once known, add as a variable cost line (scales with case volume, so it should be modeled per-case, not as a flat monthly number)
- [ ] Whether branding spend is booked as one lump in Aug or phased Aug-Dec (modeled as one lump for simplicity; doesn't change the annual total)

---

## UPDATE 27-Jul-2026 — branding buffer, ongoing branding, good-to-have

- **Branding buffer:** ₹5 to 10 L (modelled **₹7.5 L**) one-time in the BLR-launch month, so the launch-month one-time is IT ₹3 L + branding ₹7.5 L = **₹10.5 L**.
- **Ongoing branding:** **₹2 L per month** while BLR is live (S1 from Nov, S2 from Feb).
- **BLR initial fee:** confirmed **2.5 bps** (was 3 bps).
- **Labels:** Payroll shown as **Employee Expense**, Board meetings as **Secretarial Expense**.
- **Good-to-have, kept out of the base plan:** Insurance, Festival celebration/gifts, Employee appraisal.
