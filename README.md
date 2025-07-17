# 🛍️ Customer Segmentation using Unsupervised Learning

This project was developed as part of **INTELLIHACK 5.0 – Machine Learning Hackathon** by our team **The Code Rushers**. The objective was to segment e-commerce customers based on behavioral data using unsupervised learning techniques.

---

## 🚀 Problem Statement

You are provided with an e-commerce customer dataset containing behavioral features. The goal is to identify **three hidden customer segments**:
- **Bargain Hunters**
- **High Spenders**
- **Window Shoppers**

Using clustering algorithms, we aimed to find distinct patterns and classify customers based on:
- Total Purchases
- Average Cart Value
- Total Time Spent on Platform
- Product Clicks
- Discount Usage

---

## 📊 Key Steps

1. **Exploratory Data Analysis (EDA)**  
   - Statistical summaries  
   - Histogram, box plot, and density plots  
   - Scatter plots, pair plots, and correlation heatmaps  

2. **Clustering Algorithms**  
   - **K-Means Clustering** (Selected model)  
   - Agglomerative Clustering (for comparison)

3. **Evaluation Metrics**  
   - Silhouette Score  
   - Davies-Bouldin Score  
   - Calinski-Harabasz Score  

4. **Dimensionality Reduction**  
   - PCA for 2D visualization of clusters

5. **Cluster Interpretation**  
   - Assigning meaningful labels based on customer behavior

---

## 🧠 Technologies Used

- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

---

## 📂 Repository Structure
├── customer_segmentation.ipynb # Complete Jupyter Notebook with code & analysis
├── Q2.pdf # Final report submitted for the hackathon
├── README.md # Project description

---

## 📈 Results

- **K-Means** performed best with a Silhouette Score of **0.613** and clear visual cluster separation.
- Each cluster was mapped to a business-meaningful segment.
- Insights can support personalized marketing and customer targeting strategies.

- ### 🖼️ PCA Cluster Visualization

![Customer Segmentation PCA](output8.png)

---

## 👥 Team: The Code Rushers

Each team member solved one of four different ML problems.  
This problem — **Customer Segmentation** — was handled by me.

---

## 📄 License

This project is for academic and learning purposes only.
