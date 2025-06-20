
# ADR Prediction using Machine Learning

This project was developed as part of the Microsoft AI National Skilling Initiative (AINSI) Internship and focuses on predicting Adverse Drug Reactions (ADRs) from chemical compound data using machine learning.

## 🚀 Project Overview

Adverse Drug Reactions (ADRs) are one of the key challenges in drug safety. This project applies machine learning to predict potential ADRs using a dataset containing drug compounds represented in SMILES format.

## 📊 Dataset

- **Source:** Kaggle
- **File:** `adr_dataset.csv`
- **Content:** Contains chemical compounds (as SMILES) and multiple associated ADRs.
- **Purpose:** To explore patterns between chemical structure and side effects for drug safety enhancement.

## ⚙️ Technologies Used

- **Python**
- **Google Colab**
- **RDKit** – For chemical fingerprint generation
- **Scikit-learn** – For machine learning models
- **Pandas & NumPy** – Data handling
- **Matplotlib/Seaborn** – Visualization

## 🧠 Machine Learning Model

- **Algorithm:** Random Forest wrapped with MultiOutputClassifier
- **Features:** Molecular fingerprints derived from SMILES
- **Labels:** Multi-label ADR categories
- **Goal:** Predict which ADRs are likely for a given drug compound

## 📈 Results

The model showed high performance in terms of:
- Accuracy
- F1 Score (micro)
- Hamming Loss

Visual comparisons between predicted and actual ADRs supported the model’s effectiveness.

## ✅ Conclusion

This project proved the viability of using chemical fingerprints for ADR prediction. It supports safer drug development and strengthens pharmacovigilance systems.

## 🔮 Future Scope

- Use larger, more diverse datasets
- Integrate clinical, demographic, and dosage data
- Apply deep learning (e.g., GNNs or Transformers)
- Real-time deployment using cloud or edge platforms

## 📂 Repository Structure

- `adr_dataset.csv` – Dataset file
- `adr_prediction.ipynb` – Google Colab notebook
- `ADR_Prediction_Report.txt` – Model summary report
- `README.md` – Project overview
- `requirements.txt` – Required Python packages

## 👤 Contributor

- **Devarshi Hatwar**

## 📌 License

This project is created under the Microsoft AINSI Internship and is intended for academic and research purposes only.
