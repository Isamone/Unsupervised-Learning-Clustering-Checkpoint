Project Objective
In this checkpoint project, you’ll work with the “Credit Card Dataset for Clustering” from Kaggle to perform customer segmentation, which is essential for developing targeted marketing strategies.

📊 Dataset Overview
The dataset contains usage behavior of ~9,000 active credit card holders over a 6-month period.

It is simplified for learning purposes and includes variables related to user behavior such as spending patterns, payment habits, and credit usage.

📎 Dataset Link:
Credit Card Dataset for Clustering (Google Drive)

🧾 Key Columns Explained
Column	Description
CUST_ID	Unique ID for each credit card holder (categorical, may be dropped later)
BALANCE_FREQUENCY	Frequency of balance update (0 = low, 1 = high)
PURCHASES	Total amount spent on purchases
CASH_ADVANCE	Cash advances taken by the user
CREDIT_LIMIT	Maximum credit limit available to the user
PAYMENTS	Total payments made by the user

ℹ️ Project Instructions
1. Data Exploration
Import the dataset and explore its structure (.head(), .info(), .describe()).

Identify data types, missing values, and basic statistics.

2. Data Preparation
Handle missing or corrupted values.

Remove duplicates.

Encode categorical variables (if applicable).

Handle outliers using techniques like IQR or Z-score.

Select relevant features (e.g., PURCHASES, CREDIT_LIMIT, etc.).

(Optional) Normalize/scale data if needed.

3. Hierarchical Clustering
Apply agglomerative hierarchical clustering using features like PURCHASES and CREDIT_LIMIT.

Visualize clusters using a dendrogram.

Determine the number of clusters visually.

4. K-Means Clustering
Apply K-Means clustering to segment customers.

Plot the clusters using two relevant features.

5. Determine Optimal k
Use the Elbow Method to find the optimal number of clusters.

Re-train K-Means using the optimal k value and re-plot.

6. Results Interpretation
Compare results from both clustering methods.

Describe the characteristics of each cluster (e.g., high spenders vs low spenders).

Suggest marketing strategies for each customer segment.
