# Sophare AI - Global Pay Equity Data Analytics and Correlation Modeling 

**Data-Driven Benchmarking & Financial Correlation Analysis**
As the lead for data analysis and quality on this capstone project, I developed a production-ready intelligence platform that standardizes gender pay gap (GPG) reporting across the United Kingdom, Ireland, and France. My work focused on transforming heterogeneous regulatory disclosures into a unified analytical framework to help investors and policymakers identify genuine equity leaders.

**🚀 Key Insights & Impact**
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

I translated my analytical findings into a production-ready React 18.2 dashboard, using Recharts to make complex equity data accessible to non-technical stakeholders.
Interactive Visual Modules
Market Overview: I built summary cards and Bar Charts to visualize the distribution of A–F grades across a country’s entire reporting population.
Company Profile Engine: I designed a search module that generates Line Charts for 2017–2024 pay gap trends and Diverging Bar Charts to compare raw metrics like hourly vs. bonus gaps.
Industry Heatmaps: I developed a visual heatmap to represent industry-level performance, allowing users to instantly identify sectors with the highest pay disparities.
Quartile Distribution: I implemented Stacked Bar Charts to visualize the gender breakdown within four distinct pay quartiles for every company.
