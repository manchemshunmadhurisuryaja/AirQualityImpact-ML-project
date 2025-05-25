

# 🌫️ Air Quality Impact on Human Health Classification using Optimized Neural Networks and Feature Engineering

This repository presents a machine learning framework that classifies the impact of air pollution on human health using optimized neural networks and advanced feature extraction techniques such as ANOVA, MRMR, Chi-Square, and Kruskal-Wallis tests.

---

## 📌 Project Overview

Air pollution, with pollutants like NO₂, SO₂, PM2.5, and PM10, poses significant threats to human health and the environment. This project applies machine learning models—including an optimized neural network—to classify and predict the effects of air quality with high accuracy. Feature engineering techniques ensure only the most impactful data are used, improving efficiency and interpretability.

---

## 💡 Techniques Used

* **Feature Engineering:** ANOVA, MRMR, Chi-Square Test, Kruskal-Wallis Test
* **Models:** Optimized Neural Network, Support Vector Machine (SVM), Logistic Regression, Naive Bayes
* **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score

---

## 📊 Dataset

* **Rows:** 27,874
* **Columns:** 43 (includes pollutant levels, weather data, geographic info)
* **Focus Features:** PM2.5, PM10, CO, NO₂, Temperature, Wind, Humidity, etc.
* **Target Variables:** Actual vs. Predicted air quality classification

---

## 📈 Key Results

| Model                | Accuracy (%) |
| -------------------- | ------------ |
| Logistic Regression  | \~95%        |
| Naive Bayes          | \~94%        |
| SVM                  | \~96%        |
| Optimized Neural Net | **98.4%**    |

* Optimal number of features: **15**
* ANOVA feature selection provided the highest model accuracy

---

## 📁 Folder Structure

* `Dataset/` – Raw and cleaned data
* `Results/` – Performance graphs, feature importance plots
* `Documentation/` – Abstract, implementation, results, conclusion
* `Presentation/` – Final PPT

---

## 🛠️ How to Reproduce

This project was implemented using **MATLAB's GUI tools (Classification Learner & Neural Network App)** and requires:

1. Importing the dataset into MATLAB
2. Applying feature selection techniques (ANOVA, etc.)
3. Training models using Classification Learner and custom Neural Network App
4. Comparing evaluation metrics (accuracy, precision, recall)
5. Exporting confusion matrices and result plots

---

## 🔐 License

This project and its contents (including results and methodology) are protected under academic research rights.

🔒 No part of this work may be reused, copied, or published without explicit permission from the authors.

This repository is shared for academic demonstration only. The research paper associated with this project is not uploaded to prevent unauthorized use.

---

