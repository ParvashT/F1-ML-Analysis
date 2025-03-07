# 🏎️ F1 Championship Data Analysis & Machine Learning Predictions

![F1 Championship](https://upload.wikimedia.org/wikipedia/commons/3/33/F1_logo.svg)

## 🚀 **Project Overview**
Formula 1 (F1) is a data-driven sport where milliseconds decide the winner. This project explores **F1 race data** using **data science and machine learning** to uncover insights and predict race outcomes. Through data visualization, feature engineering, and ML modeling, we analyze the key factors influencing driver performance and race results.

---

## 📂 **Dataset Information**
The dataset includes:
- **Race details** – circuits, seasons, results
- **Driver statistics** – standings, age, experience
- **Constructor performance** – team success over seasons
- **Lap times, qualifying results, and finishing positions**

---

## 🔍 **Feature Engineering & Data Processing**
🔹 **Data Cleaning & Type Conversions**: Fixed missing values & converted date fields.  
🔹 **Outlier Detection & Removal**: Addressed skewness and anomalies in driver performance data.  
🔹 **Encoding Categorical Variables**: Used **Label Encoding** for driver & team names.  
🔹 **Feature Scaling**: Applied **MinMaxScaler**, **StandardScaler**, and **RobustScaler** for optimized ML performance.

---

## 🛠️ **Techniques, Analysis, Operations & Concepts Used**
- **Descriptive Statistics**: Used `describe()` to analyze dataset distributions, mean, variance, and percentiles.
- **Data Visualization**: Implemented **correlation heatmaps**, **distribution plots**, and **track maps** using `seaborn`, `matplotlib`, and `folium`.
- **Skewness & Normality Check**: Assessed data normality using skewness values (-1 to 1 range) and applied transformations.
- **Outlier Detection & Removal**: Applied **IQR-based filtering** to handle extreme values affecting ML performance.
- **Data Filtration**: Filtered datasets based on race completion status to avoid bias.
- **Encoding Techniques**: Used **Label Encoding** over One-Hot Encoding to efficiently handle categorical data.
- **Feature Scaling**: Experimented with **MinMaxScaler, StandardScaler, and RobustScaler** to normalize data.
- **Machine Learning Algorithms**: Implemented and compared **Logistic Regression, KNN, Decision Trees, Random Forest, SVM, Naïve Bayes, and SGD Classifier**.
- **Hyperparameter Tuning**: Optimized ML models by tweaking hyperparameters to achieve better accuracy.
- **Model Evaluation Metrics**: Used **accuracy score** to compare different classifiers' performance.

---

## 🤖 **Machine Learning Models & Accuracy**
### **ML Algorithms Used**:
✔ **Logistic Regression**  
✔ **Support Vector Machine (SVM)**  
✔ **Random Forest Classifier**  
✔ **Decision Tree Classifier**  
✔ **K-Nearest Neighbors (KNN)**  
✔ **Naïve Bayes Classifier**  

### **Model Accuracy Comparison**
| Model | Accuracy |
|---|---|
| Logistic Regression | 13.66% |
| SGD Classifier | 11.47% |
| KNN | 99.91% |
| GaussianNB | 93.27% |
| RandomForest | 99.99% |
| DecisionTree | 99.99% |

---

## ⚙️ **How to Run the Project**
### **1️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```
### **2️⃣ Run Jupyter Notebook**
```bash
jupyter notebook
```
### **3️⃣ Open & Run**
- Open `notebooks/f1-champ-eda-classification.ipynb`
- Execute all cells to reproduce results.

---

## 📌 **Results & Key Takeaways**
🎯 **F1 race outcomes can be predicted with high accuracy using ML models.**  
🎯 **Track conditions & driver experience significantly impact race performance.**  
🎯 **RandomForest & DecisionTree classifiers achieved near-perfect accuracy.**  
🎯 **Feature scaling & encoding significantly improved model predictions.**  

---

## 🔮 **Future Scope & Enhancements**
✨ **Expanding the dataset**: Integrating real-time race data for better predictions.  
✨ **Advanced Deep Learning Models**: Implementing neural networks for improved accuracy.  
✨ **Weather & Track Conditions**: Including weather impact for dynamic predictions.  
✨ **Live Race Forecasting**: Developing an interactive dashboard for real-time race predictions.  
✨ **Driver & Team Performance Analysis**: More granular insights into driver skills & team strategies.  
✨ **Pit Stop & Strategy Optimization**: Predicting the best pit stop strategies for race success.  
✨ **Car Performance Metrics**: Incorporating telemetry data to analyze car speed, aerodynamics, and fuel efficiency.  
✨ **Race Incident Analysis**: Using NLP techniques to analyze commentary and predict race outcomes based on incidents.

---

## 🏆 **Why This Project is Exciting?**
✅ **Real-world sports analytics application** – Formula 1 is highly data-driven, making it a perfect candidate for ML.  
✅ **Multi-faceted analysis** – This project explores drivers, teams, circuits, and race conditions for a holistic understanding.  
✅ **High-accuracy models** – The implemented classifiers provide near-perfect accuracy in race predictions.  
✅ **Potential for real-time forecasting** – This study can evolve into a **live race prediction model** with streaming data.  
✅ **Data-driven decision making** – Enhances strategic planning for teams and drivers, improving race outcomes.  
✅ **Scalability & Future Enhancements** – The model can integrate with IoT sensors and real-time telemetry data for more advanced predictions.  

---

## ✨ **Author & Contributions**
👨‍💻 **Parvash Choudhary Talluri**  
📌 If you found this project useful, **give it a ⭐ on GitHub!** 🚀

---
