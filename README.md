#  Task02-Mall Customer Segmentation Using K-Means, PCA & t-SNE

## Objective

The purpose of this project is to help a shopping mall understand **different types of customers** based on:
- How much they earn
- How much they spend

By grouping similar customers, the mall can:
- Offer better and more personalized deals
- Improve customer satisfaction
- Increase overall sales


##  Dataset

- Filename: `Mall_Customers.csv`
- Records: 200 customers
- Columns:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

##  What we Did

1. **Explored the data** using charts and graphs
2. **Cleaned the data** by:
   - Removing `CustomerID`
   - Converting `Gender` to numbers
   - Scaling values using StandardScaler
3. **Applied K-Means Clustering** to divide customers into **5 groups**
4. **Visualized the clusters** using:
   - **PCA** (Principal Component Analysis)
   - **t-SNE** (t-distributed Stochastic Neighbor Embedding)
5. **Analyzed each customer group** and suggested **marketing strategies**

## Visual Techniques Used

- **Histograms** for age, income, and spending score
- **Scatter plots** to see relationships between features
- **PCA** and **t-SNE** to visually see how different customer groups are

## Results and Insights

We used **K-Means** to create 5 clusters (customer segments).  
Then we visualized these segments using **PCA** and **t-SNE**.

Each group had a unique spending pattern:

| Cluster | Income Level | Spending Score | Profile Description                 | Suggested Strategy                                       |
|---------|--------------|----------------|-------------------------------------|----------------------------------------------------------|
| 0       | High         | High           | Wealthy & high spenders             | VIP programs, luxury promotions                          |
| 1       | Low          | High           | Young, trend-focused                | Flash sales, influencer ads                              |
| 2       | Medium       | Medium         | Average shoppers                    | Loyalty rewards, seasonal bundles                        |
| 3       | High         | Low            | Rich but cautious                   | Trust-focused branding, quality-focused promotions       |
| 4       | Low          | Low            | Budget-conscious                    | Discounts, referral programs, student-friendly offers    |


## ✅ Final Conclusion

We used K-Means to find **5 groups of similar customers**.  
Then, using PCA and t-SNE graphs, we could **clearly see the differences** between each group.

This helped us:
- Understand customer behaviors
- Create **custom marketing plans** for each segment

With this insight, the mall can now **target each group in a smarter way** — offering the right deals to the right customers.

##  📌 Tools Used

- Python (Jupyter Notebook)
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (KMeans, PCA, t-SNE, preprocessing)

---
📨 Submitted as part of the DeveloperHub Internship Program
