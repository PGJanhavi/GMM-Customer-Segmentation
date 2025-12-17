# Customer Segmentation using Gaussian Mixture Model (GMM)
# 📌 Project Overview

This project demonstrates customer segmentation using a Gaussian Mixture Model (GMM) based on monthly spending behavior.
The goal is to identify distinct customer groups (e.g., regular and premium spenders) from spending data using unsupervised machine learning.

# 📊 Dataset Description

This project uses synthetically generated data:

Customer Type	Mean Spending (INR)	Std Deviation	Count
Regular Spenders	2000	300	150
Premium Spenders	6000	500	150

Total customers: 300

# 🛠️ Technologies & Libraries Used

Python

NumPy

Matplotlib

Scikit-learn (GaussianMixture)

# ⚙️ How the Code Works

Generate synthetic customer spending data

Combine and reshape data for model input

Train a Gaussian Mixture Model with 2 components

Predict cluster labels for each customer

Visualize the clusters using histograms

# 📈 Output Visualization

The final output is a histogram showing:

Segment A – Lower monthly spending customers

Segment B – Higher monthly spending customers

Each segment is modeled as a Gaussian distribution.

# 🧪 Sample Output

Two clearly separated customer segments

Visual confirmation of clustering effectiveness

Useful for marketing and customer targeting strategies

# 🚀 How to Run the Project

Install required libraries:

pip install numpy matplotlib scikit-learn

Run the Python script:

python customer_segmentation_gmm.py
