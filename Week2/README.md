# Cab Company Data Analysis: Hypotheses & Insights

This report evaluates 7 key hypotheses using integrated datasets of cab rides, customer demographics, transaction details, and city-level statistics.

---

## Hypothesis 1: Seasonal Usage Patterns

**Statement:**  
*The number of cab rides increases during certain months of the year (e.g., holidays or summer months).*

**Findings:**  
- Ride volume consistently increases from **August to December** across all years.
- **December** has the highest ride count every year (2016–2018).
- Suggests **seasonal demand peaks** likely tied to **holidays and year-end travel**.

**Conclusion:** Supported

---

## Hypothesis 2: Company Performance

**Statement:**  
*One company (e.g., Pink Cab or Yellow Cab) consistently generates higher profit margins.*

**Findings:**  
- **Yellow Cab** has **higher average profit ($160 vs $63)** and **higher margin (30% vs 17%)** than Pink Cab.
- Yellow Cab also dominates in **total ride volume**, especially among both genders.

**Conclusion:** Strongly Supported

---

## Hypothesis 3: Income-Based Spending

**Statement:**  
*High-income customers tend to spend more per trip than low-income customers.*

**Findings:**  
- **Average price charged** and **profit per ride** is **very similar** across all income segments.
- No meaningful difference between low, middle, and high-income segments.

**Conclusion:** Not Supported

---

## Hypothesis 4: City Penetration vs Profitability

**Statement:**  
*Cities with higher user penetration tend to be more profitable on a per-ride basis.*

**Findings:**  
- Correlation between **user penetration** and **profit**: **−0.22**
- Cities with **low penetration** like New York have **high profit**, while cities with **high penetration** like Boston have **low profit**.

**Conclusion:** Not Supported

---

## Hypothesis 5: Trip Type vs Payment Mode

**Statement:**  
*High-value trips are more likely to be paid by card than cash.*

**Findings:**  
- Around **59%** of both **high-value** and **typical trips** are paid by card.
- **No major difference** in payment preference between trip types.

**Conclusion:** Not Supported

---

## Hypothesis 6: Weekend Behavior by Income Group

**Statement:**  
*High-income users are more active on weekends compared to low-income users.*

**Findings:**  
- All income segments show **~59% weekday vs ~41% weekend usage**.
- **No significant variation** between income groups.

**Conclusion:** Not Supported

---

## Hypothesis 7: Multi-Factor Profitability Model

**Statement:**  
*Profit per ride is influenced by multiple factors: distance, income level, company, and city.*

**Findings:**  
- Regression coefficients reveal:
  - **City** and **Company (Yellow Cab)** are **strongest predictors** of profit.
  - **Distance (KM Travelled)** positively contributes.
  - **Income segment** has minimal impact.

**Conclusion:** Strongly Supported

---

## Summary Table

| Hypothesis No. | Topic                               | Conclusion        |
|----------------|-------------------------------------|-------------------|
| 1              | Seasonal Usage                      | Supported         |
| 2              | Company Profitability               | Supported         |
| 3              | Income-Based Spending               | Not Supported     |
| 4              | City Penetration vs Profitability   | Not Supported     |
| 5              | Trip Type vs Payment Mode           | Not Supported     |
| 6              | Weekend Usage by Income             | Not Supported     |
| 7              | Multi-Factor Profitability Model    | Supported         |