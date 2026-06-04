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

* **Missing Value Engineering**: Missing data entries in critical score blocks (critic_score, user_score) and age classifications (rating) were systematically mapped. Missing age criteria were normalized to "Unknown" tags to preserve historical sales volume.

---

💡 Key Findings
* **Extreme Market Fragmentation**: The industry follows a strict power-law distribution. While massive blockbusters drive multi-million copy peaks, 50% of the entire industry fails to exceed 80,000 copies sold per game.

* **Regional Preference Asymmetry**: Global charts are heavily skewed by North American volume. However, the Japanese market shows a structural departure from Western consumption, favoring handheld hardware and localized genres like RPGs over home consoles.

* **Systemic Evaluation Gaps**: 51.4% of games lack critic scores, and 40.5% lack age ratings. These gaps are highly structural, caused by pre-internet release dates and publishers bypassing voluntary ESRB certification fees for niche or region-exclusive games.

---

## 🚀 Strategic Recommendations
*	**Core Focus & Timing**: Concentrate primary business operations within St. Petersburg and launch major marketing campaigns between late September and October to capture the peak annual demand. 
*	**Target High-Liquidity Segment**: Build the core portfolio around 1–2 room apartments ranging between 45 and 65 sq.m. in St. Petersburg and highly accessible inner-city towns like Gatchina, Pushkin, and Pavlovsk. 
*	**Cautious Premium Execution**: Enter the high-commission premium tier selectively, factoring in aggressive market competition and a 1.5x longer sales cycle (averaging 228 days compared to 155 days for budget properties). 

---

## 📁 Repository Structure
* 'README.md' — Project overview and executive summary (this file).
* '/data' — Anonymized raw dataset limited to 500 data entries.
* '/src' — Source code folder containing SQL script (PostGreSQL).
