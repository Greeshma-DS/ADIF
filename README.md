# ADIF: Autonomous Decision Intelligence Framework

## Overview

ADIF (Autonomous Decision Intelligence Framework) is an end-to-end Decision Intelligence framework that combines Machine Learning, Causal AI, Counterfactual Reasoning, and Large Language Models (LLMs) to transform raw business data into actionable recommendations.

The framework integrates:

* Root Cause Discovery (XGBoost + SHAP)
* Causal Discovery (PC Algorithm)
* Causal Inference (DoWhy)
* Counterfactual Reasoning
* LLM-Assisted Decision Support (Llama 3.1)

The objective is to move beyond traditional predictive analytics and provide causally-informed business recommendations for enterprise decision-making.

---

## Architecture

ADIF consists of the following layers:

1. Data Engineering Layer
2. Root Cause Discovery Engine
3. Causal Discovery Layer
4. Causal Inference Layer
5. Counterfactual Reasoning Layer
6. LLM Decision Intelligence Layer

---

## Datasets

This repository does not include the original datasets because they exceed GitHub file size limits.

### Online Retail II Dataset

Download:

https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

### Instacart Market Basket Dataset

Download:

https://www.kaggle.com/competitions/instacart-market-basket-analysis/data

After downloading:

data/
├── online_retail/
└── instacart/

---

## Project Structure

ADIF/

├── notebooks/

├── results/

│   ├── figures/

│   ├── tables/

│   └── reports/

├── README.md

└── .gitignore

---

## Key Results

### Online Retail II

* Order Change identified as dominant predictive driver
* Feature Importance: 63.42%
* Quantity Change causal effect (ATE): 0.59748

### Instacart

* Orders identified as dominant predictive driver
* Feature Importance: 93.16%
* Positive causal impact on reorder behavior

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* SHAP
* Causal Learn
* DoWhy
* NetworkX
* Matplotlib
* Seaborn
* Ollama
* Llama 3.1

---

## Installation

```bash
git clone https://github.com/Greeshma-DS/ADIF.git

cd ADIF

pip install -r requirements.txt
```

---

## Research Paper

This repository accompanies the research paper:

"ADIF: An Autonomous Decision Intelligence Framework Integrating Root Cause Discovery, Causal Inference, Counterfactual Reasoning, and LLM-Assisted Decision Support for Retail Analytics"

---

## Author

Greeshma Chanduri
Sampath Kokkonda

University of New Haven

MS DATA SCIENCE

---

## Citation

If you use this work, please cite the associated research paper.

## License

MIT License
