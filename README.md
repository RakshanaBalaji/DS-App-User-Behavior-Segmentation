# 📱 App User Behavior Segmentation & Prediction

## 📌 Problem Statement
Analyze and segment mobile app users based on their behavior and predict high-engagement users using machine learning.

---

## 📊 Dataset
The dataset contains user-level app usage data including:
- App Usage Time
- Screen Time
- Battery Drain
- Data Usage
- Number of Apps Installed
- Device Model
- Age & Gender

---

## ⚙️ Steps Performed

### 🔹 1. Data Cleaning
- Checked missing values
- Removed duplicates

### 🔹 2. Feature Engineering (Key Highlight 🔥)
Created new features:
- Engagement Score
- Power User Score
- Efficiency Score
- Screen Usage Ratio
- Premium Device Flag

---

### 🔹 3. Data Preprocessing
- Encoding categorical variables
- Feature scaling using StandardScaler

---

## 🤖 Machine Learning Models

### 🔸 Unsupervised Learning
- K-Means Clustering
- Hierarchical Clustering

### 🔸 Supervised Learning
- Logistic Regression
- Random Forest Classifier

---

## 📏 Model Evaluation
- Elbow Method for optimal clusters
- Silhouette Score for cluster validation
- Accuracy score for classification

---

## 📊 Visualizations

### 🔹 Elbow Method
![Elbow Method](/Images/elbow_plot.png)

### 🔹 Cluster Distribution
![Cluster Plot](/Images/cluster_plot.png)

### 🔹 PCA Visualization
![PCA](/Images/pca_plot.png)

---

## 🔍 Key Insights

- Identified high-value (power) users
- Detected low-engagement users for re-targeting
- Found patterns in data usage and app behavior

---

## 💡 Business Impact

- 🎯 Targeted marketing campaigns
- 📈 Improve user retention
- 💰 Identify premium users
- ⚡ Optimize app performance

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🚀 Future Improvements
- Deploy using Streamlit
- Integrate real-time data
- Add deep learning models

---

## 👨‍💻 Author
Rakshana R
