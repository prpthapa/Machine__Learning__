# Day 36 — Student Placement Prediction with Logistic Regression

![Python](https://img.shields.io/badge/Python-3.x-blue) ![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-green) ![Day](https://img.shields.io/badge/Day-36%2F100-orange)

A binary classification model to predict student placement outcomes using CGPA and IQ score as features, built with Logistic Regression using scikit-learn.

---

## 📁 Dataset
- **File:** `placement.csv`
- **Rows:** 100 samples
- **Features:** `cgpa`, `iq`
- **Target:** `placement` — `1` (placed) / `0` (not placed)

---

## 🛠 Tech Stack
- `numpy`, `pandas` — data handling
- `matplotlib` — scatter plot visualization
- `scikit-learn` — model training, scaling, evaluation
- `mlxtend` — decision boundary visualization
- `pickle` — model serialization

---

## 🔄 Pipeline
```
1. Load & explore data (placement.csv)
2. Visualize: scatter plot of CGPA vs IQ colored by placement
3. Train/test split  →  90% train / 10% test
4. Feature scaling   →  StandardScaler
5. Train model       →  LogisticRegression()
6. Evaluate          →  accuracy_score
7. Plot              →  decision boundary (mlxtend)
8. Save model        →  pickle.dump → model.pkl
```

---

## 📈 Results
- Test accuracy: **60%**
- The decision boundary clearly separates classes along the CGPA axis
- IQ alone shows weaker predictive signal than CGPA in this dataset

---

## 🚀 Run Locally
```bash
git clone https://github.com/yourusername/day36-logistic-regression
cd day36-logistic-regression
pip install numpy pandas matplotlib scikit-learn mlxtend
jupyter notebook Day_36.ipynb
```

---

## 📂 Files
| File | Description |
|------|-------------|
| `Day_36.ipynb` | Main notebook |
| `placement.csv` | Dataset |
| `model.pkl` | Saved trained model |

---

## 🔭 Next Steps
- Try with larger datasets for better generalization
- Experiment with SVM and KNN classifiers
- Add cross-validation for more reliable accuracy estimates
- Build a Flask/Streamlit app to serve `model.pkl`
