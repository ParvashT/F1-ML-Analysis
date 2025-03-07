# 🏎️ F1 Championship Data Analysis & Machine Learning Predictions

![F1 Championship](https://automobilist.com/cdn/shop/collections/ATM_Collection_OracleRedBullRacing.jpg?v=1700837625&width=2048)

## 📌 Project Overview
Formula 1 (F1) racing is a data-rich sport, and analyzing historical race data can help in predicting future race outcomes. This project applies **Exploratory Data Analysis (EDA)** and **Machine Learning** techniques to analyze and predict F1 race results based on historical data.

---

## 📊 Dataset Information
- The dataset contains information on **F1 races, drivers, constructors, lap times, results, and standings**.
- Data preprocessing was performed to handle missing values, convert data types, and filter relevant race records.
- **Feature Engineering** was applied to extract meaningful insights and improve model performance.

---

## 🔬 Project Workflow
1. **Importing the Data**
2. **Feature Engineering & Data Preprocessing**
   - Data type conversions (e.g., converting dates)
   - Handling missing values
   - Encoding categorical features (Label Encoding)
3. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation heatmaps
   - Outlier detection & skewness correction
4. **Data Visualization**
   - **F1 Track Map:** Using Folium to visualize race tracks globally
   - **Heatmaps & Density Plots:** Understanding correlations & distributions
5. **Machine Learning Models**
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - K-Nearest Neighbors (KNN)
   - Gaussian Naïve Bayes
   - Stochastic Gradient Descent (SGD)
6. **Model Evaluation & Comparison**
   - Accuracy comparison of different models
   - StandardScaler, MinMaxScaler & RobustScaler applied for better performance

---

## 🌍 F1 Track Locations
The **global F1 race track map** was created using `folium`, showing all circuits used in the dataset.

![Screenshot 2025-03-07 013524](https://github.com/user-attachments/assets/230ceadd-0dcc-412a-88e3-b3e15b05e156)

---

## 🔥 Exploratory Data Analysis (EDA) & Feature Engineering
### **1️⃣ Correlation Heatmap**
A **heatmap** was generated to show correlations between features.

![bd703dc4-756b-48bc-bfa5-11fb5ec4e85c](https://github.com/user-attachments/assets/23658ac7-e969-49e5-a169-ce59a5f5604d)


### **2️⃣ Density Distribution of Key Features**
Density plots were created to analyze the distribution of features such as lap times, driver standings, positions, and speeds.

![a23a25b7-f400-43e9-8362-ecf1b98b2916](https://github.com/user-attachments/assets/8d110801-057f-41af-8629-54686303def1)


---

## 🤖 Machine Learning Model Performance
Different classification algorithms were evaluated for predicting race results. Below is a **comparison of model accuracy**:

### **Without Scaling**
| Model                        | Accuracy (%) |
|------------------------------|-------------|
| Logistic Regression          | 13.66       |
| SGD Classifier               | 11.47       |
| K-Nearest Neighbors (KNN)    | 99.91       |
| Gaussian Naïve Bayes         | 93.27       |
| Random Forest Classifier     | 99.99       |
| Decision Tree Classifier     | 99.99       |

### **MinMaxScaler Performance**
| Model                        | Accuracy (%) |
|------------------------------|-------------|
| Logistic Regression          | 99.96       |
| SGD Classifier               | 98.64       |
| Random Forest Classifier     | 99.99       |
| K-Nearest Neighbors (KNN)    | 99.99       |
| Gaussian Naïve Bayes         | 99.99       |
| Decision Tree Classifier     | 99.99       |

### **StandardScaler Performance**
| Model                        | Accuracy (%) |
|------------------------------|-------------|
| Logistic Regression          | 99.99       |
| SGD Classifier               | 98.87       |
| Random Forest Classifier     | 99.99       |
| K-Nearest Neighbors (KNN)    | 99.99       |
| Gaussian Naïve Bayes         | 99.99       |
| Decision Tree Classifier     | 99.99       |

### **RobustScaler Performance**
| Model                        | Accuracy (%) |
|------------------------------|-------------|
| Logistic Regression          | 99.99       |
| SGD Classifier               | 98.99       |
| Random Forest Classifier     | 99.99       |
| K-Nearest Neighbors (KNN)    | 99.99       |
| Gaussian Naïve Bayes         | 99.99       |
| Decision Tree Classifier     | 99.99       |


---

## 📊 Modeling the Data
Data modeling involved selecting and training multiple machine learning models to predict F1 race results.

![ebf6505a-016c-434b-825d-06942458a7ce](https://github.com/user-attachments/assets/0e2cd34d-cedb-4d80-b665-82b105be9b91)


---

## 🔄 Feature Scaling Techniques
### **1️⃣ MinMaxScaler**
Each value in a feature is transformed by subtracting the minimum value and dividing by the range (max-min). This scaler **preserves the shape of the original distribution**.

![d356ff52-5788-478c-b3b9-15abe8c71927](https://github.com/user-attachments/assets/e44a301d-aa81-46ae-8ea1-b1c67d042080)


### **2️⃣ StandardScaler**
Removes the mean and scales each feature to unit variance. This method is **sensitive to outliers**.

![21fa9016-9121-413c-9439-455ba4813573](https://github.com/user-attachments/assets/6938c47b-045e-436b-9f4b-081433baf4c4)


### **3️⃣ RobustScaler**
Uses statistics robust to outliers by scaling data based on the **interquartile range (IQR)**.

![64a09056-3527-4d01-b8e6-74f3118752ab](https://github.com/user-attachments/assets/0033854f-bc31-44e1-934b-e387d265b815)


---

## 🚀 How to Run This Project
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/ParvashT/F1-ML-Analysis.git
cd F1-ML-Analysis
```

### **2️⃣ Install Required Libraries**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run Jupyter Notebook**
```bash
jupyter notebook
```
- Open `notebooks/f1-champ-eda-classification.ipynb` and execute the cells.

---

## 📌 Key Findings & Insights
- **KNN and Random Forest performed exceptionally well**, achieving nearly **100% accuracy**.
- **Logistic Regression & SGD struggled** due to the complexity of F1 race data.
- **Feature Engineering played a crucial role** in improving model predictions.
- **Tracks and race locations impact performance significantly**, as seen in our EDA visualizations.

---

## 📈 Future Scope
- Fine-tuning models to **reduce overfitting**.
- Testing with **Deep Learning models** (e.g., Neural Networks).
- Expanding dataset with **real-time race data** for live predictions.

---

## 👨‍💻 Author
Developed by **Parvash Choudhary Talluri** 🚀🏎️  
Master's in Data Science, UMass Dartmouth

📌 **GitHub:** [ParvashT](https://github.com/ParvashT)  
📌 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/parvash-choudhary-talluri)

---

### **📢 If you find this project helpful, don’t forget to ⭐ star the repo!**

















