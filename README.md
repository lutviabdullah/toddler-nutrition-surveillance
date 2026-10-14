# Nutritional Surveillance & Faltering Growth Analysis (May - July 2026)

**Live Interactive Dashboards:** 
* [📊 View July 2026 Dashboard](https://public.tableau.com/app/profile/lutvi.abdullah/viz/PemantauanStatusBalita-July2026/Dashboard1)
* [📉 View June 2026 Dashboard](https://public.tableau.com/app/profile/lutvi.abdullah/viz/PemantauanStatusGiziBalita-June2026/Dashboard1)
* [📈 View May 2026 Dashboard](https://public.tableau.com/app/profile/lutvi.abdullah/viz/PemantauanStatusBalita-May2026/Dashboard1)

## Executive Summary
This project analyzes the nutritional status of toddlers across a full quarter of surveillance (May, June, and July) to monitor stunting indicators (TB/U) and acute malnutrition (BB/TB) based on WHO Z-Score standards. 

While short-term localized interventions demonstrated a consistent, month-over-month positive impact on acute weight gain, the visualized data uncovers a critical, systemic public health crisis: severe **faltering growth** as children transition from infancy into their preschool years.

![Dashboard Preview](dashboard_july.png) *(Note: Ensure your best screenshot is named dashboard_july.png or update the image link accordingly)*

## Key Public Health Insights

### 1. The Faltering Growth Crisis (The Structural Gap)
By grouping continuous age data into targeted epidemiological cohorts, the quarterly dashboard reveals an alarming structural decline. Infants (0-11 months) maintain a median Z-score close to the WHO normal baseline. However, nutritional status drops sharply during the weaning phase (12-23 months) and continues to plummet, hitting an absolute low in the **48-59 months** cohort across all three observed months.
* **Policy Implication:** Current nutritional safety nets are failing older toddlers. Health interventions and maternal education must aggressively target the 12-23 month post-weaning window to prevent this severe preschool nutritional deficit before it becomes irreversible stunting.

### 2. Consistent Intervention Success (The 3-Month Trajectory)
Analyzing the month-over-month weight gain data (Naik Berat Badan) reveals the immediate, compounding effectiveness of recent Posyandu (community health post) monitoring and supplementary feeding programs (PMT).
* **May:** The baseline showed a critical deficit, with **143** children failing to gain weight (Tidak Naik) compared to only 93 who successfully did (Naik).
* **June:** The gap closed significantly, reducing the failing cohort to **129**, while successful weight gains rose to 109.
* **July:** The trend fully reversed. A record **139** children successfully gained weight, crushing the failing cohort down to just **96**.
* **Impact:** This 3-month continuous improvement proves that acute short-term interventions are actively working, highlighting the importance of sustained strategic execution at the community level.

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
