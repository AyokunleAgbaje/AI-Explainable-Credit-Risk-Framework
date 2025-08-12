# Project Credit-Xplain: An Explainable AI Framework for B2B Credit Underwriting

**Author:** Ayokunle Agbaje
---

## 🚀 Core Innovation

This project demonstrates a novel workflow that solves the "black box" problem in financial AI. It synergises a high-performance **predictive model** (built in Google Colab) with a **generative AI insight engine** (Google's NotebookLM).

The result is a system that not only automates credit risk decisions with high accuracy but also generates clear, human-readable explanations for every decision, ensuring regulatory compliance and building trust.

---

## 🛠️ Technology Stack

* **Development Environment:** Google Colab
* **Core Language:** Python 3
* **Key Libraries:**
    * `Pandas` & `Numpy` for data manipulation
    * `XGBoost` for predictive modeling
    * `SHAP` for model explainability
    * `Matplotlib` for visualizations
* **Insight & Reporting Engine:** Google's NotebookLM

---

## 📊 Project Artifacts

This repository contains all the necessary components to replicate the project:

* `Project_Credit-Xplain_Dev.ipynb`: The main Google Colab notebook containing all Python code for data generation, model training, and explanation.
* `wex_b2b_synthetic_credit_data.csv`: The high-quality synthetic dataset generated for this project.
* `global_feature_importance.png`: A plot showing the key drivers of risk across all applicants.
* `local_explanation_high_risk.png`: A detailed plot explaining the risk factors for a specific applicant.

---

##  workflow/how-to-run-the-project-arrow-11-512.png How to Run the Project

### Part 1: Model Development (Google Colab)

1.  Download the `.ipynb` notebook from this repository.
2.  Upload it to Google Colab (`colab.research.google.com`).
3.  Run the cells sequentially from top to bottom to generate the dataset, train the model, and export the explanation artifacts.

### Part 2: Interactive Analysis (NotebookLM)

1.  Download all project files from this repository into a single folder.
2.  Create a mock `credit_policy.txt` file (a template is provided in the visa documentation).
3.  Upload all files to a new project in Google's NotebookLM.
4.  Interact with the AI using natural language to query the model's logic and generate reports, as demonstrated below.

!(URL_TO_DEMO_HERE)
https://github.com/user-attachments/assets/5d6756ae-a756-4c39-b9ca-faf4cc8883ce.png
https://github.com/user-attachments/assets/cee0869f-e97f-4bff-8c5f-194bba9aad0c.png
https://github.com/user-attachments/assets/0c5c63e0-b8ee-494c-a340-f4f26ff6d8ac.png
https://github.com/user-attachments/assets/92049ae4-f1d4-4f96-9af6-2320bf708db6.png
