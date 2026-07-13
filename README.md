# SAFE-MFI: Operational AI Safety Framework for Trustworthy Machine Learning

## Overview

SAFE-MFI (**Safety Assurance Framework for Explainable Microfinance Intelligence**) is a lifecycle-oriented framework for operationalizing AI safety in high-stakes machine learning systems. Rather than proposing a new predictive algorithm, SAFE-MFI integrates explainability, fairness evaluation, governance, human oversight, auditability, and continuous monitoring throughout the machine learning lifecycle.

The framework is validated using a credit risk assessment case study involving multiple supervised learning algorithms. While the experimental evaluation focuses on financial services, the framework is designed to be transferable to other safety-critical domains including healthcare, insurance, cybersecurity, and public administration.

This repository accompanies the research paper:

> **Operationalizing AI Safety in High-Stakes Machine Learning: The SAFE-MFI Framework for Trustworthy Credit Risk Assessment**

---

# Research Objectives

The SAFE-MFI framework was developed to address four research questions:

* Can AI safety mechanisms be integrated into machine learning without reducing predictive performance?
* How can explainability and fairness be operationalized throughout the AI lifecycle?
* How can governance and accountability be embedded into routine machine learning engineering?
* How can continuous monitoring improve the long-term trustworthiness of deployed AI systems?

---

# Repository Structure

```
data/            Synthetic datasets
notebooks/       End-to-end experimental workflow
src/             Python implementation
models/          Trained machine learning models
outputs/         Experimental results
figures/         Figures used in the paper
governance/      AI governance mappings
reports/         Research paper and supporting documents
docs/            Additional documentation
```

---

# Experimental Workflow

The notebooks should be executed in the following order:

1. 01_EDA.ipynb
2. 02_Preprocessing.ipynb
3. 03_Model_Training.ipynb
4. 04_Model_Evaluation.ipynb
5. 05_SHAP.ipynb
6. 06_Fairness.ipynb
7. 07_Operational_AI_Safety.ipynb

Running the notebooks sequentially reproduces the experimental results reported in the paper.

---

# Machine Learning Models

The following supervised learning algorithms were evaluated:

* Logistic Regression
* Random Forest
* XGBoost
* LightGBM
* CatBoost

Performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

---

# Operational AI Safety Components

SAFE-MFI incorporates:

* Data assurance
* Feature engineering
* Model validation
* Explainability (SHAP)
* Fairness evaluation
* Governance documentation
* Human oversight
* Audit logging
* Continuous drift monitoring
* Deployment readiness assessment

---

# AI Governance Alignment

The framework operationalizes principles from:

* NIST AI Risk Management Framework (AI RMF)
* ISO/IEC 42001
* OECD AI Principles
* European Union AI Act

Detailed mappings are available in the `governance/` directory.

---

# Reproducibility

To reproduce the reported experiments:

```bash
git clone <repository-url>
cd SAFE-MFI

pip install -r requirements.txt

jupyter notebook
```

Execute the notebooks in numerical order.

---

# Supplementary Material

The repository includes supplementary artefacts referenced in the paper, including:

* Model Cards
* AI Impact Assessment
* Audit Logs
* Governance Dashboard
* Deployment Checklist
* Drift Monitoring Reports
* SHAP Analyses
* Fairness Reports
* Confusion Matrices
* Precision–Recall Curves

---

# Citation

If you use this repository in your research, please cite the accompanying paper using the information provided in `CITATION.cff`.

---

# License

This project is released under the MIT License.

---

# Contact

**Aniebiet Friday Ebong**
ekscellence@yahoo.com

For questions, collaborations, or feedback regarding SAFE-MFI, please open an issue in this repository or contact the author through the details provided in the accompanying publication.
