# PRAMAN: Unlocking Societal Trends in Aadhaar 🇮🇳
> **"Evidence-Based Governance"** | UIDAI Hackathon 2024

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Hackathon_Submission-green)

## 📜 About The Project
**PRAMAN** (Sanskrit for *Proof* or *Evidence*) is an advanced analytics engine designed to transform raw Aadhaar transaction logs into actionable governance intelligence.

While Aadhaar data is vast, administrative decision-making often suffers from "Insight Latency." PRAMAN bridges this gap by moving beyond simple counting to **predictive diagnostics**. It identifies hidden migration patterns, predicts infrastructure stress, and detects statistical anomalies in real-time.

---

## 🚀 The P.R.A.M.A.N. Framework
Our approach is built on six core analytical pillars:

* **P - Periodic Trend Analysis:** Distinguishing between daily noise and long-term structural shifts.
* **R - Rolling-Average Smoothing:** Using 7-Day Rolling Means to reveal true enrolment trajectories.
* **A - Administrative Stress Finding:** Identifying "Red Zone" districts where demand exceeds capacity.
* **M - Multi-Demographic Segmentation:** Tracking inclusivity (Age 0-5, Gender) to ensure no one is left behind.
* **A - Annual & Seasonal Benchmarking:** Comparing Year-over-Year (YoY) growth.
* **N - Noise Reduction:** Filtering anomalies to detect potential fraud or system errors.

---

## 📂 Repository Structure
Here is how the project is organized:

```bash
PRAMAN-UIDAI/
│
├── final_code.ipynb       # 🧠 MAIN ENGINE: Run this file for full analysis.
│                          # Contains Data Cleaning, Stress Logic, and Visualizations.
│
├── content/               # 💾 DATASETS: Place your raw UIDAI .xls files here.
│   ├── api_data_aadhar_enrolment_merged.xls
│   ├── api_data_aadhar_demographic_merged.xls
│   └── aadhaar_biometric_merged.xls
│
├── graph/                 # 📊 VISUALIZATION OUTPUTS:
│   ├── enrolment_heatmap.html    # Interactive map of saturation
│   ├── migration_clusters.html   # Visualizing "Magnet" districts
│   └── stress_prediction.html    # Resource allocation forecast
│
└── README.md              # 📄 Project Documentation
```


## 🛠️ How to Run the Analysis

### Run Locally 

#### 1. Clone the Repository
```bash
git clone https://github.com/kishorprajapati1212/uidai_hackthon.git
cd uidai_hackthon
```

#### 2. Install Dependencies

- Ensure Python 3.8+ is installed.

```bash
 pip install pandas numpy matplotlib seaborn folium
```
#### 3. Launch Jupyter Notebook

```bash
 jupyter notebook
```

#### 4. Run the Analysis
Open final_code.ipynb
Click Run → Run All

## 🔍 Key Insights & Capabilities

### 1️⃣ Stress Finding Engine 🚨

We don’t just count enrolments — we measure pressure.

#### Logic
- Biometrics Load → 1.5× weight
- Demographics Load → 1.0× weight

#### Stress Score
Stress Score = (1.5 × Biometric Updates) + (1.0 × Demographic Updates)

#### Automated Recommendations
- High Biometric Load → Deploy Iris / Fingerprint Scanners
- High Demographic Load → Deploy Data Entry Operators

---

### 2️⃣ Migration Proxy Tracking 🌍

#### Problem
Census migration data updates every 10 years.

#### Solution
Use Address Updates as a real-time migration proxy.

#### Result
- Identifies Migrant Magnet Districts
- Flags districts with address updates > 5× state average
- Example: Surat, Bengaluru

---

### 3️⃣ Anomaly Detection System 🛡️

#### Security Logic
- 7-Day Rolling Average
- Volatility Threshold Check

#### Alerts
- Flags impossible spikes (e.g. 300% growth in 24 hours)
- Triggers fraud audits & investigations

---

## 📊 Visualizations

Generated automatically inside the graph/ folder:

- heatmap.html  
  → Geospatial stress & enrolment saturation

- migration.html  
  → Inter-state & intra-state migration flows

(All files are interactive HTML visualizations)

## Team Member:-
- Prajapati Kishor Jayeshbhai

