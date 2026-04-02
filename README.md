# mall-customer-clustering-K-Mean-
Unsupervised Learning project using K-Means Clustering to segment customers based on annual income and spending scores.
# Mall Customer Segmentation: K-Means Clustering 🛍️

## 📋 Project Overview

This project applies Unsupervised Machine Learning to a retail dataset to perform **Customer Segmentation**. By analyzing annual income and spending scores, I implemented a K-Means clustering algorithm to group customers into distinct "personas." This type of analysis helps businesses create targeted marketing strategies for different customer groups.

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** * **Scikit-Learn:** KMeans clustering algorithm.
    * **Pandas/NumPy:** Data cleaning and array manipulation.
    * **Plotly/Matplotlib/Seaborn:** Advanced 2D and 3D data visualization.

## 🧪 Methodology

### 1. Exploratory Data Analysis (EDA)
I started by visualizing the distribution of ages, incomes, and spending scores to identify any immediate patterns or outliers.

### 2. The Elbow Method
To find the optimal number of clusters ($K$), I used the **Elbow Method**. By plotting the Within-Cluster Sum of Squares (WCSS) against different values of $K$, I identified the "elbow" point where adding more clusters no longer significantly improves the model.



### 3. K-Means Implementation
I trained the model using the optimal $K$ value to segment the customers into specific groups (e.g., "High Income/Low Spenders" vs. "Low Income/High Spenders").

## 📈 Visualizing the Clusters

One of the highlights of this project is the **3D Cluster Visualization**. Using `Plotly`, I created an interactive 3D scatter plot that allows for the exploration of customer segments across three dimensions: Age, Annual Income, and Spending Score.



## 💡 Business Insights

The model successfully identified 5 primary customer segments:
1. **Target Group:** High Income, High Spending.
2. **Sensible:** High Income, Low Spending.
3. **Careless:** Low Income, High Spending.
4. **Standard:** Average Income, Average Spending.
5. **Frugal:** Low Income, Low Spending.

---

## 📂 Repository Contents

* **[Analysis Notebook](./mall-customers-k-means-clustering(1).ipynb):** Full clustering analysis and interactive visualizations.
* **[Dataset](./Mall_Customers.csv):** The source dataset containing customer demographics.
