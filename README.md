# Sophare AI - Global Pay Equity Data Analytics and Correlation Modeling 

**Data-Driven Benchmarking & Financial Correlation Analysis**
As the lead for data analysis and quality on this capstone project, I developed a production-ready intelligence platform that standardizes gender pay gap (GPG) reporting across the United Kingdom, Ireland, and France. My work focused on transforming heterogeneous regulatory disclosures into a unified analytical framework to help investors and policymakers identify genuine equity leaders.

# 🚀 Key Insights & Impact
During this project, I moved beyond simple data processing to uncover the structural drivers of pay inequality:

**The "Bonus Gap" Signal:** I identified that bonus gaps remain significantly larger than hourly pay gaps (averaging 15–21% in the UK). My analysis showed that while hourly gaps are narrowing, bonus inequality is actually widening in markets like Ireland.

**Representation as a Predictor:** Through correlation analysis, I proved that female representation in top-quartile roles is the single strongest predictor of a lower overall pay gap.

**Market Realities (The Null Finding):** I conducted a rigorous study of 183 NYSE-listed companies and found no systematic evidence that pay equity currently predicts stock performance. I positioned this "null finding" as a strategic asset for Sophare AI, establishing their credibility as an evidence-based partner that values scientific integrity over marketing narratives.

# 🛠️ What I Built

**1. Multi-Country Data Pipeline**
I engineered an ETL pipeline to harmonize three distinct regulatory ecosystems covering over 57,000 companies.

**Harmonization:** Standardized different identifiers (EmployerID vs. SIREN) and translated French metrics into a unified English schema.

**Adaptive Scoring:** I developed country-specific weighted models—including an 8-component framework for the UK—to account for varying data maturity across jurisdictions.

**Standardization:** I successfully mapped these diverse datasets to a single 0–100 scale with unified A–F letter grades.

**2. Statistical Research & Data Analysis Framework**

I led the investigation into whether a company’s commitment to pay equity translates into tangible market value. My work moved beyond simple data processing to uncover the structural drivers of pay inequality through rigorous statistical testing and interactive visualization.

**Methodology & Quality Assurance**

**Spearman Rank Correlations:** I conducted 81 statistical tests across cross-sectional and predictive time windows to investigate equity-performance relationships.

**Rigorous QA:** I implemented a multi-stage QA framework, including outlier detection for percentage metrics (enforcing $-100\% \le x \le 100\%$) and VIF analysis to ensure the stability of our scoring models.

**The "Null Finding":** My research on 183 NYSE-listed companies revealed that markets do not currently price gender pay equity into stock valuations. I positioned this finding as a strategic asset for Sophare AI, building scientific credibility by avoiding unsupported "ESG marketing" narratives.

**Key Analytical Insights**

**The Bonus Gap Signal:** I identified that mean bonus gaps (ranging from 15–21% in the UK) remain significantly larger than hourly pay gaps. In Ireland, I discovered that bonus gaps actually widened from 23% in 2022 to nearly 28% in 2024.

**Representation as a Predictor:** My analysis proved a strong negative correlation between female representation in top-quartile roles and overall pay disparities, confirming that leadership diversity is a primary driver of equity.

**Longitudinal Trends:** I tracked the UK's steady reduction in hourly pay disparities, which decreased from 14.34% in 2017 to 12.00% in 2024.

**4. Data Visualization & Dashboard Design**

In addition to the production dashboard, I developed a suite of advanced data visualizations to perform deep-dive exploratory analysis and sectoral benchmarking. These visualizations allowed me to move from raw data to the specific insights that drive Sophare AI’s scoring methodology.

**Exploratory Data Analysis (EDA) - UK, France, & Ireland**
I used Python (Matplotlib & Seaborn) to build a statistical "brain" for the project, visualizing the underlying drivers of pay inequality:

**National Trend Analysis:** I created Time-Series Plots to track the steady decline of the UK mean hourly pay gap from 14.34% in 2017 to 12.00% in 2024, confirming a slow but persistent move toward wage equality.

**Distribution & Outlier Detection:** I utilized Boxplots to quantify the spread of hourly and bonus gaps, identifying extreme outliers in sectors like Finance and Education.

**Correlation Heatmaps:** I developed a Feature Correlation Matrix that visually linked pay gaps to quartile representation. This proved a strong negative correlation: as the share of women in the Top Pay Quartile rises, the overall pay gap consistently falls.

**Metric Relationships:** I built Scatter Plots comparing mean vs. median hourly gaps, validating that both metrics serve as consistent indicators of systemic pay disparity.


**Tableau Sectoral Benchmarking (UK)**

To provide a more granular, comparative view of the UK market, I designed a Tableau Dashboard focused on six major industry sectors: Education, Finance, Tech, Health, Arts, and Public Administration:

**Sectoral Bubble Charts:** I engineered Individual Bubble Charts for each sector, allowing for a side-by-side comparison of company-level inequality patterns. Each bubble represents a firm, sized and colored to highlight its deviation from the sector average.

**Outlier Investigation:** The dashboard revealed "crazy" insights, such as the Education sector—despite being female-dominated—exhibiting some of the most severe pay gap outliers (up to ~100%), often due to high-level administrative pay disparities.

**Public vs. Private Comparison:** I used these visualizations to contrast the rigid pay structures of Public Administration with the more volatile, high-bonus environments of the Financial and Insurance sectors.

**Technical Implementation**

**Statistical Logic:** All EDA visualizations were sensitivity-checked, ensuring that reporting anomalies (like the 2019 data dip) did not bias the long-term trend analysis.

**Interactivity:** The Tableau dashboard includes dynamic filters that let users drill down from a high-level sector overview to individual company performance rankings.

# 💻 Technical Stack
**Data Science:** Python (Pandas, NumPy, SciPy), Jupyter Notebooks.

**Full-Stack API:** FastAPI (Backend), DynamoDB (NoSQL storage for pre-computed aggregations).

**Visualization:** React 18.2, Material-UI, and Recharts for interactive trend analysis.

**Cloud Infrastructure:** Deployed via AWS Lambda and API Gateway for serverless scalability.
