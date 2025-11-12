# Bias-audit-report-
# 🤖 AI Résumé Screener Bias Audit  

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Fairlearn](https://img.shields.io/badge/Fairlearn-Fairness%20Audit-brightgreen?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Model%20Training-orange?logo=scikit-learn)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Report](https://img.shields.io/badge/Output-PDF%20%26%20PPTX-lightgrey)

---

## 🧠 Overview
This project investigates potential **bias and fairness issues** in an **AI résumé screening model**.  
It evaluates model performance and fairness across demographic groups using synthetic data, and applies mitigation strategies to improve equity in automated hiring.

The audit demonstrates how responsible AI practices can make recruitment systems **fairer, explainable, and transparent**.

---

## ⚙️ Key Features
- 🧩 **Synthetic Data Generation:** Automatically creates realistic résumé-style candidate data (skills, education, experience, gender, and age group).  
- ⚖️ **Bias Detection:** Evaluates fairness metrics such as *Demographic Parity Difference (DPD)* using the **Fairlearn** library.  
- 🪄 **Bias Mitigation:** Applies *Exponentiated Gradient Reduction* with *Demographic Parity* constraints to reduce unfairness.  
- 📊 **Visualization:** Generates professional plots for data distributions, selection rates, and performance metrics.  
- 📄 **Automated Report:** Exports a full **PDF bias audit report** with charts, metrics, and a professional summary.  
- 💼 **Presentation Deck:** Creates a polished **PowerPoint presentation** summarizing the findings and visuals.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|----------|
| **Python 3.10+** | Core programming language |
| **pandas / numpy** | Data manipulation |
| **scikit-learn** | Model training and evaluation |
| **Fairlearn** | Fairness metrics and bias mitigation |
| **matplotlib / plotly** | Data visualization |
| **ReportLab / PyPDF2** | PDF generation |
| **python-pptx** | PowerPoint presentation creation |

---

## 🧮 How It Works
1. **Generate Data:**  
   Creates a synthetic résumé dataset with demographic and skill-based features.  
2. **Train Model:**  
   Trains a logistic regression model to predict hiring outcomes.  
3. **Run Fairness Audit:**  
   Calculates fairness metrics and evaluates demographic parity differences.  
4. **Mitigate Bias:**  
   Applies fairness constraints to improve model balance.  
5. **Visualize Results:**  
   Produces modern, professional charts and visuals.  
6. **Generate Reports:**  
   Exports an automated **PDF** and **PowerPoint** summarizing all findings.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/ai-bias-audit.git
cd ai-bias-audit
Create and Activate a Virtual Environment
python -m venv .venv
.\.venv\Scripts\activate   # (Windows)
# OR
source .venv/bin/activate  # (Mac/Linux)

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Bias Audit
python bias_audit.py


📂 Outputs will be saved in the /outputs folder:

outputs/
├── AI_Bias_Audit_Report.pdf
├── AI_Bias_Audit_Presentation.pptx
└── *.png  (charts and visuals)

📈 Example Results
Metric	Before Mitigation	After Mitigation
Demographic Parity Difference (DPD)	0.21	0.07
Accuracy	0.83	0.81
Fairness Improvement	+65% Bias Reduction	

The results show that applying fairness constraints improved demographic parity while maintaining high accuracy — demonstrating the value of responsible AI.

🧩 Project Structure
AI_Bias_Audit/
│
├── bias_audit.py                # Main script
├── requirements.txt             # Dependencies
├── README.md                    # Documentation
└── outputs/                     # Generated reports & visuals

🧾 Ethical Statement

This project supports responsible and ethical AI development.
By identifying and mitigating bias, we ensure fairness and transparency in automated decision-making — especially in critical use cases like hiring.

👤 Author

Nigel Ludick
💼 AI Developer & Fairness Enthusiast
📧 nigelludick88@gmail.com

🌐 GitHub Profile

🪪 License

This project is licensed under the MIT License — free to use, modify, and share with attribution.

🌍 Quote

“Fair AI isn’t just about accuracy — it’s about trust, transparency, and accountability.”

🚀 Empowering ethical AI through fairness audits.

⚙️ Setup Guide

Follow these steps to set up and run the AI Résumé Screener Bias Audit project on your local machine:

# 1️⃣ Clone the repository
git clone https://github.com/<your-username>/ai-bias-audit.git
cd ai-bias-audit

# 2️⃣ Create and activate a virtual environment
python -m venv .venv
.\.venv\Scripts\activate   # (Windows)
# OR
source .venv/bin/activate  # (Mac/Linux)

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run the project
python bias_audit.py


📂 Outputs:
All reports, visuals, and presentation files will be automatically generated inside the outputs/ folder:

outputs/
├── AI_Bias_Audit_Report.pdf
├── AI_Bias_Audit_Presentation.pptx
└── charts/
