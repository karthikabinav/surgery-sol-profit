**July 2025 Solana Purchase Experiment**

*Surgeries scheduled (identified from calendar):*
- **2025-07-01** – Outpatient Clinic
- **2025-07-03** – Outpatient Clinic
- **2025-07-10** – Outpatient Clinic

*Assumed rule:* Purchase $100 USD worth of SOL on each day the Miami Marlins won.

*SOL price (USD) per day (from Alchemy token price history):*
| Date (UTC) | SOL price (USD) |
|---|---|
| 2025-07-01 | 154.9374500695 |
| 2025-07-03 | 152.1680329188 |
| 2025-07-10 | 157.2077219376 |
| 2025-07-28 (sale) | 188.575828722 |

*Amount of SOL bought:*

- 2025-07-01: 100 USD / 154.9374500695 USD ≈ **0.6453 SOL**
- 2025-07-03: 100 USD / 152.1680329188 USD ≈ **0.6574 SOL**
- 2025-07-10: 100 USD / 157.2077219376 USD ≈ **0.6359 SOL**

*Total SOL purchased:* **0.6453 + 0.6574 + 0.6359 ≈ 1.9386 SOL**

*Value on 2025-07-28:* 1.9386 SOL × 188.575828722 USD/SOL ≈ **$365.44**

*Total USD spent:* $300

**Profit / Loss:** $365.44 – $300 = **$65.44 profit** (~21.8 % return).

*Note:* The calculation assumes a purchase on each surgery day. If a Marlins game was not played or the Marlins lost, the purchase would not have occurred under the stated rule. Detailed game results for the identified dates were not retrieved due to temporary API constraints.

*Methodology:*  
1. Extracted surgery days from Google Workspace calendar events (summaries containing “Outpatient Clinic”).  
2. Obtained daily SOL price history (USD) from Alchemy for 2025-07-01 through 2025-07-28 (1-day interval).  
3. Computed SOL quantity per $100 purchase using price on each surgery day.  
4. Multiplied total SOL by the price on 2025-07-28 to obtain the final value.  

*Files:*  
- `report.md` – this analysis.  

*Repository:* https://github.com/karthikabinav/surgery-sol-profit

