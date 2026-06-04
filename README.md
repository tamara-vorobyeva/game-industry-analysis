# 📊 Video Game Industry Study

## 📌 Business Case Overview
The client - a game developing company - plans to use these insights to evaluate multiple hypotheses, specifically exploring how game ratings impact overall ROI.

## 🎯 Project Objectives 
- Conduct a study of the video game industry from 2000 to 2013, focusing on the RPG (Role-playing games) segment across major platforms, game genres, and received scores.📌 

## 🔗 Quick Links
* 🛠 **[View SQL Data Cleaning & Analysis Script](src/data-cleansing-analysis)**
* 🔍 **[dataset](https://github.com/tamara-vorobyeva/game-industry-analysis/blob/main/data/dataset.csv)**

---

## 🛠 Tech Stack
* **Data Processing & Engineering** (Python / Pandas): Handled dataset normalization, and casting data types (converting regional sales streams and user scores from strings to floats).

* **Analytical Modeling** (Jupyter Notebook): Utilized for exploratory data analysis (EDA), missing value tracking, and cross-sectional pivot tables across global sales territories.

---

## 🔍 Research Approach 
* **Data Cleaning & Scope**: Cleaned a dataset of 16,956 records, filtering out records missing essential identifiers (names, genres, release years). The final analysis explicitly scopes the 2000–2013 window, centering on the Role-Playing Game (RPG) segment.

* **Methodological Segmentation**: Segmented software sales by core economic regions: North America (na_sales), Europe (eu_sales), and Japan (jp_sales). Missing sales entries were handled via custom multi-index imputation grouped by year_of_release and platform.

* **Missing Value Engineering**: Missing entries in essential data (critic_score, user_score) and age classifications (rating) were systematically mapped. Missing age criteria were normalized to "Unknown" tags to preserve historical sales volume.

---

💡 Key Findings
* **Extreme Market Fragmentation**: The industry follows a strict power-law distribution. While massive blockbusters drive multi-million copy peaks, 50% of the entire industry fails to exceed 80,000 copies sold per game.

* **Regional Preference Asymmetry**: Global charts are heavily skewed by North American volume. However, the Japanese market shows a structural departure from Western consumption, favoring handheld hardware and localized genres like RPGs over home consoles.

* **Systemic Evaluation Gaps**: 51.4% of games lack critic scores, and 40.5% lack age ratings. These gaps are highly structural, caused by pre-internet release dates and publishers bypassing voluntary ESRB certification fees for niche or region-exclusive games.

---

## 🚀 Strategic Recommendations

* **Dataset Specifics**: The final dataset includes 16,432 rows and 11,421 unique game titles. The duplicate titles are due to industry specifics (multi-platform releases), so these rows were kept as valid for further analysis.

* **Score Distribution**: The majority of games received average-to-high ratings from both critics and users.

* **Top Platforms by Game Count**: The technologically advanced DS (2,110 games) and PS2 (2,044 games) lead the ranking. They are followed by Wii (1,261) and PSP (1,126), platforms that once disrupted the market with their innovativeness.
---

## 📁 Repository Structure
* 'README.md' — Project overview and executive summary (this file).
* '/data' — Anonymized raw dataset limited to 500 data entries.
* '/src' — Source code folder containing python script (Jupyter Notebook).
