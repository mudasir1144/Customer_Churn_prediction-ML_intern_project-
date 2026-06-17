# Customer Churn Analytics Platform: Predictive Intelligence Suite

## 1. Executive Summary & Strategic Intent

This platform delivers data-driven proactive intelligence designed to maximize customer lifetime value (LTV) and neutralize churn indicators before they impact the bottom line. By operationalizing data-informed predictive frameworks, this suite identifies high-risk behavioral anomalies, dissects complex contract lifecycle correlations, and outputs clear prescriptive insights. The ultimate objective is to drive revenue insulation and optimize enterprise subscriber retention rates.



## 2. Solution Workflow Architecture

The system employs an end-to-end analytical matrix divided into structured, chronological execution phases:

```
+---------------------------+
| PHASE 1: Data Acquisition | -> Ingestion, Schema Auditing, Data Type Refinement
+---------------------------+
              |
              v
+---------------------------+
| PHASE 2: Discovery & EDA  | -> Pattern Diagnostics, Statistical Variance Analysis
+---------------------------+
              |
              v
+---------------------------+
| PHASE 3: Data Segment     | -> Tier Assignments (Low, Medium, High Value)
+---------------------------+
              |
              v
+---------------------------+
| Phase 4: Visualization    | -> Metric Plottings, Feature Distribution Mapping
+---------------------------+
              |
              v
+---------------------------+
| PHASE 5: Model Deployment | -> Logistic Regression, Predictive Insights Generation
+---------------------------+

```

---

## 3. Step-by-Step Implementation Framework

### Phase 1: Data Ingestion & Data Hygiene

During the initial initialization window, structural attributes are audited for completeness. Missing values or blank cells within strategic financial metrics are identified, and records with null variables are removed to secure data integrity.

* **Libraries Leveraged**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`.
* **Initial Data Footprint**: 7,043 customer accounts across 21 categorical and continuous variables.
* **Data Integrity Check**: Identified 11 null records within the financial metrics which were systematically removed to output a pristine clean dataset containing 7,032 operational profiles.

### Phase 2: Exploratory Data Analysis & Pattern Diagnostics

This layer evaluates foundational behavioral markers to detect root causes behind historical account closures.

* **Baseline Churn Matrix**: Analysis shows a baseline churn profile where 26.58% of the customer base has opted out, while 73.42% remains actively retained.
* **Tenure Longevity Assessment**: Data patterns establish that retained accounts display an average tenure of 37.65 months, whereas churning subscribers drop off sharply at an average duration of 17.98 months.

### Phase 3: Financial Feature Engineering & Customer Stratification

To enrich the analytical dataset, account records are run through a categorization function to group customers into value tiers based on historical financial contributions:

| Customer Segment Tier | Total Charges Parameter Boundary | Strategic Focus |
| --- | --- | --- |
| **Low Value** | Less than or equal to $401.45 | Volume optimization and automated engagement paradigms |
| **Medium Value** | Between $401.46 and $3,794.74 | Active lifecycle management and upsell campaigns |
| **High Value** | Greater than $3,794.74 | High-touch VIP account protection and proactive retention |

### Phase 4: Predictive Modeling Execution

The platform trains a Logistic Regression engine to classify active subscriber data into operational risk bands. The feature matrix undergoes classification testing to map input behaviors directly to statistical churn probability points.

---

## 4. Key Business Insights & Analytical Deliverables

Our deep-dive analytical metrics highlight several key areas for strategic intervention:

### Contractual Vulnerability Matrix

Account structures show a clear correlation between contract type and user attrition. Subscribers bound to month-to-month terms demonstrate extreme churn behavior compared to those on stable long-term agreements.

| Lifecycle Contract Type | Active Retained Base (%) | Attrition/Churn Rate (%) | Risk Exposure Status |
| --- | --- | --- | --- |
| **Month-to-month** | 57.29% | 42.71% | Critical High Risk |
| **One year** | 88.72% | 11.28% | Managed Moderate Risk |
| **Two year** | 97.15% | 2.85% | Minimal Stable Position |

### Pricing Elasticity Analysis

Subscribers who eventually churned carry an elevated average monthly premium compared to loyal customer cohorts:

* **Churned Group Average Cost**: $74.44 per month
* **Retained Group Average Cost**: $61.31 per month

This discrepancy indicates that financial friction points and uncompetitive pricing tiers act as strong catalysts for customer defection.

---

## 5. Deployment Instructions

### Prerequisites & Dependency Installation

To prepare your environment for this pipeline, install the core data science dependencies by running the command below:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```

### Running the Infrastructure Pipeline

Execute the notebook suite to reproduce the telemetry data, plots, and predictive engines:

```bash
jupyter notebook index.ipynb

```
