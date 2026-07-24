# Indian CRA Industry Structure & Regulation

> Compiled 24-Jul-2026. Primary/reliable sources fetched and linked. Estimates and
> unverifiable items flagged explicitly. This file explains **what the "BLR licence"
> in our scenarios actually is** and **why ACER's ₹25 Cr FD is a regulatory lock.**

---

## 1. The "BLR licence" = RBI ECAI accreditation (this is the swing factor in the AOP)

- SEBI registration lets a CRA rate **securities** (bonds, CP, etc.).
- To do **Bank Loan Ratings (BLR)** that banks can use for **Basel regulatory-capital** purposes, the CRA must **separately be accredited by the RBI as an ECAI** (External Credit Assessment Institution). Under RBI's Basel framework (standardised approach, effective for Indian banks from ~March 2008), banks size credit-risk capital using ECAI ratings — which creates the regulatory *pull* for every bank borrower to get rated.
- **So a freshly SEBI-registered CRA cannot have its bank-loan ratings used by banks until RBI grants ECAI accreditation.** This is the licence our three scenarios turn on (live by Oct / by Jan / not this FY).

Sources: [CRISIL Bank Loan Ratings methodology (PDF)](https://www.crisilratings.com/mnt/winshare/Ratings/SectorMethodology/MethodologyDocs/criteria/CRISILs%20Bank%20Loan%20Ratings.pdf) (defines BLR; RBI Basel II / ECAI context); [KPMG — Basel III standardised approach for Indian banks (2026)](https://kpmg.com/in/en/insights/2026/05/basel-III-standardised-approach-for-Indian-banks.html).
⚠️ *Not independently confirmed against a single verbatim RBI circular — verify the RBI Master Circular on Basel III Capital Regulations before board use.*

**Why BLR is the volume engine:** unlike bond ratings (only companies tapping capital markets), *any* company borrowing from banks is a BLR candidate — a vastly larger pool of mid-corporates and SMEs. Small Indian CRAs (Infomerics, Acuité, ex-Brickwork) are all **BLR-led**. This is *directionally* confirmed but **no citable rupee/percentage share of BLR vs bonds was found** — do not quote a specific % in the deck.

---

## 2. SEBI requirements to operate as a CRA — confirms our ₹25 Cr FD lock

- **Minimum net worth: ₹25 crore**, to be maintained **at all times**. Raised from ₹5 crore by the **SEBI (CRA)(Amendment) Regulations, 2018** (existing CRAs given 3 years to comply).
- Applicant must be a company with rating as a main object (Reg. 5); promoter categories restricted (Reg. 4); promoter must hold ≥26% for 3 years; **10% cap on cross-shareholding** between rival CRAs.

Sources: [taxguru — SEBI (CRA)(Amendment) Regulations 2018](https://taxguru.in/sebi/securities-exchange-board-india-credit-rating-agencies-amendment-regulations-2018.html) (₹25 Cr + 3-year window); [taxguru — SEBI (CRA) Regulations 1999](https://taxguru.in/sebi/securities-exchange-board-india-credit-rating-agencies-regulations-1999.html) (original ₹5 Cr text, promoter/registration rules); [SEBI consolidated regulation PDF](https://www.sebi.gov.in/acts/CreditRatingAgencies.pdf); [Business Standard — 2018 SEBI norms / 10% cross-holding cap](https://www.business-standard.com/amp/article/pti-stories/sebi-puts-10-cross-shareholding-cap-in-rating-agencies-118060501213_1.html).

> **⭐ Direct link to our AOP:** ACER's ₹25.0 Cr Bank of India FD is almost certainly this
> **SEBI minimum net worth** — it must be maintained at all times, so it is **NOT freely
> drawable** for operations. This confirms the runway note in
> [`../model/00_baseline_cost_engine.md`](../model/00_baseline_cost_engine.md): true
> drawable liquidity is the *other* ~₹1.9 Cr, not the ₹26 Cr headline. (Anyone quoting
> ₹5 Cr is citing the superseded 1999 figure.)

---

## 3. Revenue model — issuer-pays, two components

- **Issuer-pays:** the rated entity pays the CRA.
- **Initial Rating Fee (IRF):** charged at first rating, priced as a % of the debt/issue amount.
- **Annual Surveillance Fee (ASF):** recurring, charged while the rating is outstanding — this is the **compounding annuity** that makes a mature rating book valuable.

Indicative (⚠️ **secondary/unfetched — verify against live CRA fee disclosures before quoting**): IRF ≈ 0.05–0.10% of issue amount, min ~₹2–3 lakh; ASF ≈ 35–70% of IRF. Source: [smallcase — how Indian CRAs make money](https://www.smallcase.com/blog/how-indian-credit-rating-agencies-make-money-and-why-it-matters/); each CRA publishes a SEBI-mandated fee schedule, e.g. [Brickwork BLR fee disclosure](https://www.brickworkratings.com/BLR-FeeDisclosure.aspx).

---

## 4. Industry size & market share

- **No official aggregate exists.** Group revenues bundle non-rating businesses. A defensible **pure-rating-industry estimate is ~₹1,800–2,200 Cr** (analyst-derived, not a sourced fact).
- **CRISIL leads with ~60%+ share**, then ICRA and CARE. (Brokerage estimate, not a SEBI figure.) The recognised universe: CRISIL, ICRA, CARE, India Ratings (Fitch), Acuité, Infomerics, + new entrants.

Sources: [screener.in/CRISIL/consolidated](https://www.screener.in/company/CRISIL/consolidated/); [smallcase blog](https://www.smallcase.com/blog/how-indian-credit-rating-agencies-make-money-and-why-it-matters/); [aliceblueonline — CRISIL vs ICRA (~60% share)](https://aliceblueonline.com/crisil-vs-icra-best-credit-rating-stocks/); [equitymaster — CARE vs CRISIL vs ICRA](https://www.equitymaster.com/detail.asp?date=10/17/2024&story=5&title=Best-Credit-Rating-Stock-CARE-Ratings-vs-CRISIL-vs-ICRA).

---

## 5. Recent industry backdrop (2024–2026)

- **New entrants:** the industry is now ~9 SEBI-recognised CRAs, incl. recent entrants. Source: [fatakpay — CRAs in India](https://www.fatakpay.com/blog/credit-score/credit-rating-agencies-in-india/). ⚠️ *Cross-check ACER's own registration timeline against SEBI's intermediary registry.*
- **Credit growth tailwind:** India Ratings projects bank credit growth **13–13.5% in FY26**; ICRA sees **~11–11.7%**. Sources: [Business Standard — India Ratings FY26 credit growth](https://www.business-standard.com/finance/news/india-ratings-sees-credit-growth-at-13-13-5-pc-in-fy26-nbfcs-to-drag-125062600946_1.html).
- **Peer momentum:** CARE Q4 FY25 PAT +77% YoY; CRISIL Q4 (Dec-24) PAT +6.9% YoY. Sources: [Business Standard — CARE Q4](https://www.business-standard.com/amp/markets/capital-market-news/care-ratings-soars-as-q4-pat-rallies-77-yoy-to-rs-43-cr-declares-dividend-of-rs-11-sh-125051300512_1.html); [Business Standard — CRISIL Q4](https://www.business-standard.com/markets/capital-market-news/crisil-jumps-after-q4-pat-rises-6-9-yoy-125021101224_1.html).

---

## 6. Could-not-verify list (do not present as sourced facts)
1. A single official "total CRA industry revenue" number (does not exist).
2. Precise market shares by rating volume from a regulator (only ~60% brokerage estimate).
3. Exact BLR vs bonds share of revenue/volume for any CRA.
4. A verbatim RBI circular requiring separate ECAI accreditation for a new CRA (inferred from framework).
5. Specific IRF/ASF bps and ticket sizes (structure verified; magnitudes indicative).
