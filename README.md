# 🧠 Unsupervised Learning – Customer Segmentation

This project applies a series of **unsupervised learning and exploratory data analysis (EDA) tasks** to a customer segmentation dataset.  
It demonstrates **data cleaning, feature engineering, visualization, dimensionality reduction, and clustering** techniques for segmenting customers based on their spending patterns and demographics.

---

## 🎯 Objectives

1. **Understand the dataset** through descriptive statistics and data visualization.  
2. **Clean and prepare** the data for modeling (handle missing values, duplicates, outliers).  
3. **Engineer new features** such as age groups, spending levels, and ratios.  
4. **Apply dimensionality reduction** (PCA, t-SNE) to visualize customer patterns.  
5. **Perform clustering** (K-Means & Hierarchical) to discover customer segments.  
6. **Evaluate and profile clusters** to identify actionable insights.

---

## 🛠️ Skills & Techniques Demonstrated

- **Data Wrangling:** handling missing values, filtering, binning, encoding  
- **Feature Engineering:** quantile bucketing, ratios, flagging high-value customers  
- **Visualization:** histograms, scatter plots, boxplots, correlation heatmaps  
- **Dimensionality Reduction:** PCA explained variance, 2D embedding with t-SNE  
- **Clustering:** K-Means, elbow method, silhouette score, hierarchical dendrogram  
- **Cluster Profiling:** comparing sizes, demographics, and spending  
- **Exporting Results:** saving labeled data for further analysis  

---

## 📝 Project Structure

### Part A — Load & Basic EDA (Tasks 1–8)
- Load data into a Pandas DataFrame  
- Inspect shape, column names, and dtypes  
- Count unique values per column and list top 10 frequent categories  
- Detect missing or unrealistic values  
- Describe numeric columns (mean, median, std, quartiles)  
- Convert `Age` into bins (Young, Adult, Senior) and show group counts  

### Part B — Data Cleaning & Filtering (Tasks 9–15)
- Drop rows with missing key values  
- Remove duplicates  
- Filter out records where Age < 18  
- Replace missing numeric values with the mean  
- Bucket customers into spending categories (quantiles)  
- Scale numeric features  

### Part C — Aggregation & Feature Engineering (Tasks 16–22)
- Group by gender and compute average income  
- Create new ratio features (e.g., income-to-age)  
- Flag “high-value” customers  
- Compute correlations and pivot tables  

### Part D — Visualizations (Tasks 23–27)
- Histogram of Age  
- Bar chart of spending by Gender  
- Scatter plot of Annual Income vs. Spending Score  
- Boxplot of spending by age bins  
- Correlation heatmap  

### Part E — Dimensionality Reduction (Tasks 28–31)
- PCA on standardized income and spending  
- Plot explained variance and 2D PCA scatter colored by Gender  
- Run t-SNE and plot 2D embedding  
- Compare PCA vs. t-SNE clustering clarity  

### Part F — Clustering & Evaluation (Tasks 32–40)
- K-Means for k=2–10; elbow curve & silhouette scores  
- Plot final clusters  
- Hierarchical clustering & dendrogram  
- Cut dendrogram at k clusters and compare with K-Means  
- Profile clusters (average Age, Income, Spending Score)  
- Check cluster sizes and stability  
- Run K-Means with different random states  
- Export dataset with cluster labels to CSV  

---

## 📈 Key Insights

- PCA gives an overview of variance but t-SNE highlights clearer non-linear cluster separations.  
- Clusters can be profiled to reveal **high-income, high-spending customers** vs. **low-spending groups**.  
- Some clusters were small and may need merging or re-evaluation of k.  

---



