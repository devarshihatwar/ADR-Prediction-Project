
# ADR Prediction using Machine Learning

This project focuses on predicting Adverse Drug Reactions (ADRs) based on chemical compound data using machine learning techniques. It was developed as part of the Microsoft AI National Skilling Initiative (AINSI) internship.

## Project Overview
The aim of this project is to leverage machine learning to identify potential adverse reactions associated with specific drug compounds. The model is trained on a Kaggle-sourced dataset that includes compound IDs and reaction types.

## Dataset
- Source: [Kaggle ADR Dataset](https://www.kaggle.com)
- File: `adr_dataset.csv`
- Description: Contains drug compounds and their associated adverse reactions.

## Technologies Used
- Python
- Pandas
- RDKit (for chemical fingerprinting)
- Scikit-learn
- Matplotlib/Seaborn (for visualization)
- Google Colab (development)

## Machine Learning Model
- Algorithm: Random Forest with MultiOutputClassifier
- Input: Chemical fingerprints generated from compound IDs
- Output: Predicted reaction types

## Results
The model achieved good accuracy in identifying potential ADRs. It demonstrates the power of AI in pharmacovigilance.

## Deployment
This project can be further deployed in clinical decision-making systems or integrated into drug safety tools for pharmaceutical companies.

## Contributors
- Devarshi Hatwar

## License
This project is for educational purposes under the AINSI Internship Program.
