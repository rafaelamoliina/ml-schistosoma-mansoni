# 🔬 Machine Learning Models for Identifying Bioactive Natural Products

## 📖 Description
This repository contains the scripts, trained models, and data used in the article **"Machine Learning Models for the Identification of Natural Products with Anti-Schistosomiasis Activity"**, published in **JBCS**. The aim of this study was to utilize **machine learning** to identify promising natural compounds against *Schistosoma mansoni*.

## Repository Structure
- `code/` → Scripts for model training and validation
- `data/` → Training and validation datasets
- `models/` → Trained models (Random Forest, DNN, SVM, XGBOOST)
- `notebooks/` → Jupyter Notebooks with exploratory analyses and visualizations

## Requirements and Installation
To run the code, install the following dependencies by executing:

```bash
pip install -r requirements.txt
```

Alternatively, install manually:
```bash
pip install numpy pandas scikit-learn rdkit tensorflow torch xgboost matplotlib seaborn scipy joblib imbalanced-learn
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   cd YOUR_REPOSITORY
   ```

2. Train the model:
   ```bash
   python code/train_model.py
   ```

3. Perform predictions on new compounds:
   ```bash
   python code/predict_new_compounds.py
   ```

## Key Results
- The **Random Forest (RF)** model achieved the best performance, with **R² = 0.93** in validation.
- **14 promising compounds** were identified for potential experimental testing.
- **Rigorous cross-validation** was implemented to prevent overfitting.

## 📡 Model and Data Availability
The trained models and datasets are available at:
- 🔗 **GitHub:** [Repository](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY)
- 📂 **Zenodo:** [DOI Link](https://doi.org/XXXX)

## 🎓 Authors
- **Rafaela Molina de Angelo** - UFABC
- **Vinícius Gonçalves Maltarollo** - UFMG
- **João Henrique Ghilardi Lago** - UFABC
- **Kathia Maria Honorio** - USP

## 📜 License
This project is distributed under the **MIT License**. For more details, see [LICENSE](LICENSE).
