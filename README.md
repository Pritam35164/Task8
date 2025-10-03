# Customer Segmentation with K-Means

This project explores **unsupervised learning** using the classic **Mall Customers dataset**. The goal was to group customers into segments based on their **age, annual income, and spending score**.

## What I Did

1. **Loaded the dataset** and selected numerical features.
2. **Standardized the data** to bring all features to the same scale.
3. Used **PCA** to reduce dimensions and make 2D visualizations.
4. Applied the **Elbow Method** to decide the best number of clusters.
5. Trained a **K-Means model** and assigned cluster labels to each customer.
6. **Visualized clusters** with colors in 2D space.
7. Measured clustering quality with the **Silhouette Score**.

## Key Insights

* The **optimal number of clusters** was found to be around **5**.
* The **Silhouette Score** came out to ~**0.42**, showing decent but not perfect separation.
* The clusters represent **different customer segments** (e.g., high income–low spenders, low income–high spenders, etc.).

## Tools Used

* **Python**
* **Pandas, Scikit-learn**
* **Matplotlib**
* **PCA for visualization**

## Outcome

We successfully grouped customers into meaningful clusters, which can help businesses with **targeted marketing and customer insights**.
