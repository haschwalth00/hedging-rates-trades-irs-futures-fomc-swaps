# USD Rates Trade Hedging – Citi Sales & Trading Simulation

## Overview

This project was completed as part of the **Citi Bank Markets Sales & Trading Virtual Work Experience**. The task involved evaluating the risk exposures of three USD interest rate trades and selecting **appropriate hedges** using futures, swaps, and curve strategies. Each trade is assessed for its sensitivity to **interest rate moves**, **FOMC policy expectations**, and **inflation risk**, followed by a justification for the optimal hedge.

## Author

**Vanshwardhan Singh**

## Objective

To demonstrate understanding of:
- Risk analysis for fixed income trades (IRS, FOMC swaps, bond futures)
- Macro and monetary policy exposure
- Hedging strategies with consideration of curve structure, timing, and product matching
- Professional reasoning to defend hedge selection and reject alternatives

---

## 🔹 Trade 1 – BlueFort Paid 10Y USD IRS

- **Risk:** Citi is receiving fixed 10Y. If yields rise, received fixed loses value.
- **Exposure:** High to inflation and hawkish Fed tone.
- **Chosen Hedge:** **Sell 10Y Treasury Bond Futures**
  - Offsets rising yields with gains from falling bond prices.
- **Why Not Others:**
  - Buy 10Y futures increases exposure.
  - Pay 5Y IRS doesn’t match 10Y duration.
  - Receive more 10Y IRS worsens risk.

---

## 🔹 Trade 2 – Castleton Received 1Y Fwd 1Y USD IRS (3m1y)

- **Risk:** Citi is paying 3m1y. If short-term rates fall, the position loses value.
- **Exposure:** Medium to inflation/FOMC tone.
- **Chosen Hedge:** **Receive March FOMC Swap**
  - Directly hedges around the March decision window.
- **Why Not Others:**
  - Receive 2Y IRS mismatches timing and forward structure.
  - 1s2s spread adds unnecessary curve shape exposure.

---

## 🔹 Trade 3 – USD Rates Options Desk Received March 2022 FOMC Swap

- **Risk:** Citi is paying March FOMC. Fed hiking more than expected hurts this view.
- **Exposure:** Very high – pure play on March Fed outcome.
- **Chosen Hedge:** **Receive May 2022 FOMC Swap**
  - Closely correlated but allows for tactical expression without fully neutralizing view.
- **Why Not Others:**
  - Receive March = cancels trade entirely.
  - Receive Dec 2021 = priced, irrelevant to March view.

---

## Files

- `Trade_Idea_Pay_Fixed_10Y_IRS.docx`: Trade strategy reference for 10Y swap exposure
- `Product Explanations.pdf`: Summary of IRS, FOMC swaps, and futures for context

## Disclaimer

> This is an educational project completed as part of the **Citi Markets Sales & Trading Simulation**. All scenarios are fictional and used for demonstration purposes only.
