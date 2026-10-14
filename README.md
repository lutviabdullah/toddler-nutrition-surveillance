# Nutritional Surveillance & Faltering Growth Analysis (June - July 2026)

**Live Interactive Dashboards:** 
* [📊 View July 2026 Dashboard](https://public.tableau.com/app/profile/lutvi.abdullah/viz/PemantauanStatusBalita-July2026/Dashboard1)
* [📉 View June 2026 Dashboard](https://public.tableau.com/app/profile/lutvi.abdullah/viz/PemantauanStatusGiziBalita-June2026/Dashboard1)
* [📈 View May 2026 Dashboard](https://public.tableau.com/app/profile/lutvi.abdullah/viz/PemantauanStatusBalita-May2026/Dashboard1)

## Executive Summary
This project analyzes the nutritional status of toddlers across two months of surveillance (June and July) to monitor stunting indicators (TB/U) and acute malnutrition (BB/TB) based on WHO Z-Score standards. 

While short-term localized interventions showed positive results in monthly weight gain, the visualized data uncovers a critical, systemic public health crisis: severe **faltering growth** as children transition from infancy into their preschool years.

![Dashboard Preview](dashboard_july.png)

## Key Public Health Insights

### 1. The Faltering Growth Crisis (The Structural Gap)
By grouping continuous age data into targeted epidemiological cohorts, the dashboard reveals an alarming structural decline. Infants (0-11 months) maintain a median Z-score close to the WHO normal baseline. However, nutritional status drops sharply during the weaning phase (12-23 months) and continues to plummet, hitting an absolute low in the **48-59 months** cohort.
* **Policy Implication:** Current nutritional safety nets are failing older toddlers. Health interventions and maternal education must aggressively target the 12-23 month post-weaning window to prevent this severe preschool nutritional deficit before it becomes irreversible stunting.

### 2. Short-Term Intervention Success (June vs. July)
Comparing the month-over-month data reveals the immediate effectiveness of recent Posyandu (community health post) monitoring and supplementary feeding programs (PMT).
* **June:** The baseline showed a negative ratio, with 129 children failing to gain weight (Tidak Naik) compared to 109 who did (Naik).
* **July:** The trend reversed significantly. **139 children successfully gained weight**, reducing the failing cohort to 96. This proves that while structural long-term growth issues remain, acute short-term interventions are actively working.

## Methodology & Technical Approach
* **Data Visualization:** Tableau Public
* **Clinical Standards:** WHO Child Growth Standards (Z-scores for Weight-for-Height and Height-for-Age).
* **Analytical Architecture:** 
  * **Data Transformation:** Converted noisy continuous age variables into discrete, actionable epidemiological bins for accurate trend analysis.
  * **Clinical UI/UX:** Applied medical color psychology (Red for critical/negative, Green for positive) to intuitively flag at-risk populations, enabling rapid executive decision-making.
  * **Metric Standardization:** Eliminated misleading aggregated volume metrics in favor of standardized clinical deviation scores (Z-Scores) to ensure strict medical and epidemiological accuracy.

## About the Author
**Lutvi Abdullah**
*Circular Strategist | Public Health Nutrition - Data Analyst*
Dedicated to bridging advanced data analytics with public health policy, sustainable food systems, and targeted nutritional interventions.
