# Network Classification with Machine Learning

In this project, **network traffic data collected via Wireshark** was preprocessed and analyzed using various classification models to predict network protocols. The most successful model was then integrated into an **interactive user application** for protocol prediction.

## Project Overview

- 🧪 Supervised machine learning was applied to classify network protocols based on flow features.
- 🧹 Raw data was cleaned, encoded, and normalized.
- 📊 Five different classification algorithms were compared.
- 🎯 The best-performing model was selected and used in an interactive protocol prediction app (via Jupyter Notebook).

---

## Technologies Used

- Python  
- Jupyter Notebook  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Wireshark (for raw data collection)

---

##  Models Compared

| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Naive Bayes        | 0.785    | 0.708     | 0.785  | 0.745    |
| Decision Tree      | 0.929    | 0.924     | 0.929  | 0.920    |
| Random Forest      | 0.929    | 0.924     | 0.929  | 0.920    |
| Logistic Regression| 0.779    | 0.697     | 0.779  | 0.735    |
| Gradient Boosting  | 0.927    | 0.920     | 0.927  | 0.916    |

*Based on the evaluation metrics, Decision Tree and Random Forest performed similarly well, but **Random Forest** was selected for its better generalization and ensemble-based strength.*

---

## 📈 Visualization

Four bar charts were used to compare the models:
- ✅ Accuracy
- 🎯 Precision
- 🔁 Recall
- 🧮 F1 Score



---

##  User Interaction

A Jupyter Notebook application allows users to:
- Upload or enter network flow data
- Use the trained Random Forest model to classify the protocol
- View prediction output and model confidence

---

##  Data

- Collected with **Wireshark**
- Exported and saved in `CSV` format (`time.csv`)
- Preprocessed and cleaned for model training

---

##  Running the Project

1. Clone the repo:
   ```bash
   git clone https://github.com/gokcendilek/Network_Classification.git

