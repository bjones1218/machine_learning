🛍️ Mall Customer Segmentation Using Unsupervised Learning

A machine learning project that applies clustering techniques to help mall management better understand customer behavior.

📌 Project Overview

This project uses unsupervised machine learning to segment mall customers into meaningful groups based on demographic and spending behavior.
The primary goal is to help Mall Management better understand customer purchasing patterns so they can make data-driven decisions about marketing, store placement, promotions, and customer engagement strategies.

Using K-Means clustering, this analysis identifies customer segments that differ in income, spending score, and overall visit patterns. The project includes selecting an optimal value of K = 5 based on the Elbow Method, visualizing the clusters, and providing actionable business insights.

📁 Repository Contents

Generated Data set - mallcustomers.csv

Customer Segmentation.ipynb — Full notebook including:

Data preprocessing

Exploratory analysis

K-Means modeling

Determining optimal K

Visual cluster interpretation

Insights tailored for mall management stakeholders

🧠 Machine Learning Concepts Used
✔ K-Means Clustering

Used to group customers based on similarity.

✔ Elbow Method Analysis

Evaluated several values of k to determine the optimal number of clusters (final choice: K = 5).

✔ Cluster Visualization

Visualized customer groups based on spending score and annual income to show clear segmentation.

✔ Business Interpretation

Translates technical results into stakeholder-friendly recommendations — such as identifying:

High-value customers - High income / High Spending Score

Budget shoppers - Mid Income / Mid Spending Score

Potential loyalty-program targets - Low Income / High Spending Score

Under-engaged groups that might need new strategies - High Income / Low Spending Score


🔧 Tools & Libraries

Python

Pandas

NumPy

scikit-learn

Matplotlib

Seaborn

📌 How to Run

Load in mallcustomers.csv into your coding environment

Open the .ipynb file in Jupyter Notebook / VS Code / Google Colab

Run cells sequentially

View the clustering results and plots

Explore insights at the end of the notebook

🎯 Skills Demonstrated

Unsupervised Machine Learning

Clustering Analysis

Data Visualization

Business Analytics

Stakeholder Communication

Python Data Science Workflow

👤 Author

Brian Jones
Graduate Data Science Student — Belhaven University
Aspiring Data Science & Machine Learning Professional
