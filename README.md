# Macarena Hülsken — Data Analyst

#### Technical Skills: Python (Pandas, NumPy) | SQL | Tableau | Power BI | Excel

**Location:** Adelaide, SA, Australia  
**Email:** [macarenahulsken@gmail.com](mailto:macarenahulsken@gmail.com)  
**Phone:** +61 431 212 300  
**LinkedIn:** [Macarena Hülsken](https://www.linkedin.com/in/macarena-hulsken)  
**GitHub:** [macarenahulsken](https://github.com/macarenahulsken)

---

## About Me
I am a Data Analyst passionate about sales analytics and commercial performance. Having grown up closely involved in my family’s sales business, I developed an early, hands-on understanding of business operations and the vital role data plays in driving revenue, solving operational challenges, and guiding strategic decisions.

Through intensive training at TripleTen, I gained solid technical proficiency in Python, SQL, Tableau, and statistical analysis, building end-to-end workflows to turn raw datasets into actionable insights. Having worked in collaborative and fast-paced environments, I bring strong cross-functional communication and team problem-solving skills.

## Education
* **Data Analysis Professional Certification** | TripleTen (2025 – 2026)
* **Bachelor of Science in Marketing (2 Years Completed)** | UNC – Argentina (2021 – 2023)

---

## Portfolio Projects

### 1. Commercial Performance & Profitability Analysis (2024–2025) | Andes Retail Group
🔗 **[View Live Dashboard (Tableau)](#)** | **[View Project Files](#)**

* **📌 Project Overview:** Transformed dispersed multi-country transactional data (Peru, Chile, and Colombia) into an actionable visual narrative to evaluate revenue drivers, profitability, customer behavior, and regional performance across 2024–2025.
* **🛠️ Tools & Technologies:** Tableau (Interactive Dashboards), Excel / Power Query (Data Cleaning & Wrangling), SCQA Framework.

#### 📊 Executive Summary (SCQA Framework)

**1. General Overview**
![Andes Retail General Dashboard](/assets/dashboard1_andes.png)

* **Situation:** 2024 closed with a total revenue of $2.86M and a profit margin of 35.13%, with Peru leading revenue generation ($1.14M).
* **Complication:** In 2025, the landscape contracted: revenue dropped to $2.67M (35.07% margin), representing a Year-over-Year (YoY) decline of -6.80%.
* **Question:** Which segments or regions drove this revenue decline?
* **Answer (Key Findings):** The decline is primarily explained by the Premium segment, which generated $0.20M less in 2025, matching the levels of the Standard segment. Regionally, although Peru remains the leader, it suffered a significant contraction (from $1.14M to $1.02M).

**2. Detailed Diagnostic**
![Andes Retail Detailed Dashboard](/assets/dashboard2_andes_detail.png)

* **Situation:** In 2025, the Sports and Home categories were the pillars of the business, jointly contributing approximately $1.40M, with strong seasonal volume during summer months.
* **Complication:** Three critical focus areas emerged: (1) Electronics suffered a YoY decline ($0.75M to $0.66M), (2) sales drop drastically during cold months, and (3) the Economy segment holds marginal business share.
* **Question:** What commercial actions can mitigate seasonal drops and reactivate lagging segments?
* **Answer (Strategic Recommendations):**
  * **Electronics:** Deploy retargeting campaigns and targeted promotions to stimulate demand.
  * **Seasonality:** Create a winter promotional calendar and boost the "Clothing" category (higher AOV) to offset low cold-season volume.
  * **Economy Segment:** Conduct a competitive pricing audit (benchmarking) to evaluate entry-level price positioning.

---

### 2. Commercial Performance & Unit Economics Audit | RappiPlus
🔗 **[View Code on GitHub](#)** | **[View Live Dashboard (Tableau)](#)**

* **📌 Project Overview:** Audited regional sales data and checkout conversion performance to diagnose critical gross margin losses, optimize marketing spend allocation, and evaluate a new UI checkout experience.
* **🛠️ Tools & Technologies:** SQL (Joins, Aggregations), Python (Pandas, SciPy — A/B Hypothesis Testing), Tableau (Dual-View Executive & Operational Dashboard).

#### 📊 Executive Summary

![RappiPlus Dashboard](/assets/dashboard_rappiplus.png)

* **Key Analytical Findings:**
  * **Profit Leakage:** Uncovered a **$0.48M gross margin loss** concentrated in the *Laptop* and *Jacket* categories, driven by aggressive promotional discounts pushing final sale prices below unit cost.
  * **A/B Testing:** Evaluated conversion rates between the original checkout UI and the new variant using statistical hypothesis testing in Python to determine behavioral impact.
* **Strategic Recommendations:**
  * Implement automated pricing guardrails/alerts in the ERP/POS system to block promotions that result in negative unit margins.
  * Reallocate seasonal marketing budgets toward high-margin categories and restructure discount tiers on underperforming SKUs.

---

### 3. User Behavior & Subscription Tier Analysis | ConnectaTel
🔗 **[View Code & Notebook on GitHub](#)**

* **📌 Project Overview:** Analyzed behavioral usage patterns across 4,000 telecom customers (calls, messaging, and data consumption) to identify high-value segments and optimize subscription tier structures.
* **🛠️ Tools & Technologies:** Python (Pandas, NumPy, Matplotlib, Seaborn), Data Cleaning & Imputation, Outlier Winsorization, Customer Segmentation.

#### 📊 Executive Summary

![ConnectaTel Segmentation Chart](/assets/chart_connectatel.png)

* **Data Engineering & Statistical Methodology:**
  * Merged and standardized three relational datasets (*Users, Plans, Usage*), resolving an **11.7% missing geographic data gap** via Median Imputation.
  * Applied **Winsorization** via NumPy to the top 3% of call duration outliers to prevent statistical skew while preserving "Power User" profiles.
* **Key Analytical Findings:**
  * Engineered a multi-tier segmentation framework (*Usage Tiers & Demographic Brackets*) isolating distinct user personas, including high-frequency messaging users and long-duration callers.
  * Identified a significant volume of *Basic* plan subscribers consistently exceeding their monthly allowances and paying overage fees.
* **Strategic Recommendations:**
  * Introduce a **"Basic Plus" intermediate subscription tier** priced between the Basic and Pro plans to capture mid-market demand, improve retention, and increase predictable recurring revenue (ARPU).

