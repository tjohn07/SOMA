# SOMA  
### System for Observing and Modeling Alignment  

SOMA is a personal data-science project that integrates wearable, physiological, and contextual data — from heart rate and glucose to mood, sleep, and daily rhythms — to discover patterns of alignment between body, mind, and environment.

---

## 📁 Project Structure
SOMA/
├── data/ # Raw & cleaned input data (Garmin, Strava, CGM, manual logs)
├── notebooks/ # Exploratory analysis and pipeline development
├── feature_engineering/ # Feature extraction scripts
├── modeling/ # ML models, clustering, predictive analysis
├── narrative/ # Generative + interpretive summaries (Abacus AI)
├── utils/ # Helper functions, constants, config handling
├── outputs/ # Results, reports, visualizations
└── config.yaml # Project configuration file

---

## 🧩 Core Objectives
1. **Integrate** data from multiple sources (Garmin/Strava, Dexcom/Stelo, manual logs)  
2. **Engineer** features for physiological state detection (stress, recovery, flow)  
3. **Cluster & Classify** behavioral and physiological patterns  
4. **Generate** natural-language interpretations using Abacus AI  

---

## 🤖 Abacus AI Integration
SOMA provides structured data, configuration prompts, and contextual metadata to Abacus AI for automated code generation and analysis workflows.

**Primary instruction for Abacus AI:**
> “Given this README and config.yaml, write modular, well-commented Python scripts for ingestion, feature engineering, clustering, and natural-language generation.”

---

_Last updated: 2025-11-17_
