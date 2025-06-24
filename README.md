# Task_2_Customer_Segmentation

# 🛍️ Customer Segmentation using K-Means Clustering

This project implements a **K-Means Clustering** algorithm to group retail store customers based on their purchase behavior. The aim is to identify customer segments to assist in **targeted marketing** and **business strategy development**.

---

## 📌 Project Objective

To build an unsupervised machine learning model that:

- Analyzes customer data (e.g., annual income, spending score)
- Segments customers into distinct groups
- Helps businesses understand customer behavior for personalized offers

---

## 🗃️ Dataset Overview

The dataset typically contains:

- **CustomerID**
- **Gender**
- **Age**
- **Annual Income (k$)**
- **Spending Score (1–100)**

These features are used to cluster customers based on similarities in spending patterns.

---

## 🧠 Model Summary

- **K-Means Clustering** is used for unsupervised segmentation
- Optimal number of clusters (`k`) is chosen using:
  - **Elbow Method**
  - **Silhouette Score**
- Customers are grouped into segments like:
  - High income, high spending
  - Low income, low spending
  - Average income, moderate spending, etc.

---

## 🧪 Workflow

### Data Preprocessing

- Loaded dataset using Pandas
- Handled missing values and cleaned data
- Encoded categorical variables (if needed)
- Scaled features using `StandardScaler` or `MinMaxScaler`

### Clustering Process

- Visualized clusters using:
  - Elbow plot to determine `k`
  - 2D/3D scatter plots for analysis
- Applied **KMeans** algorithm from scikit-learn
- Assigned cluster labels to each customer

### Evaluation

- Visualized cluster distribution
- Analyzed each cluster profile
- Used Silhouette Score for validation

---

## 📈 Results

- Successfully segmented customers into **k distinct groups**
- Identified business insights such as:
  - Most profitable customer groups
  - Low engagement customers for retargeting
- Data-driven strategies can now be applied to each cluster

---

## 🔍 Prediction / Application

The model can now:

- Classify new customers into existing segments
- Assist in **targeted promotions**
- Improve **customer experience** and **ROI**

---

## 🖥️ Demo Video

🎥 [Click here to watch the project demo](https://drive.google.com/file/d/1q6f9zYwzZ-90iLTXP8OFNBSDZyiKqz0d/view?usp=sharing)

---

## 🔗 LinkedIn Post

🔗 [Click here to view my LinkedIn post](https://www.linkedin.com/posts/naveena-sivaiah-91b0b6326_task-02-completed-customer-segmentation-activity-7341786570435260417-irrC?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFI9iKcBwcCFvahb-MaFocwHJSF22yC6mYE&utm_campaign=copy_link)

---

## 🧰 Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## 📌 Tags

#KMeansClustering #CustomerSegmentation #MachineLearning #UnsupervisedLearning #Python #SkillCraftTechnology #RetailAnalytics #Clustering #DataScience
