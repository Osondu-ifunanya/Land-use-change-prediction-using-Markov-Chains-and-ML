# Land Use Change Prediction using Markov Chains and Machine Learning

This project simulates and predicts land use/land cover (LULC) changes using a hybrid approach combining Markov chain transition probabilities with a Random Forest classifier trained on environmental features.

## 🔍 Overview
- **Synthetic data** generation for LULC maps at two time steps (T1 and T2)
- **Markov chain** model to compute land use transition probabilities
- **Machine Learning** model (Random Forest) to predict future LULC (T3)
- **Environmental variables** include slope, elevation, and road proximity
- Results exported to Excel for visualization and analysis

## 📦 Output
- Excel file: `land_use_change_markov_ml.xlsx`
- Contains:
  - Environmental predictors
  - Land use at T1 and T2
  - Predicted land use at T3

## 🧠 Requirements
- Python 3.7+
- numpy
- pandas
- scikit-learn

Install dependencies using:

```bash
pip install numpy pandas scikit-learn
