# Customer Segmentation Using K-Means Clustering

## Project Overview

This project performs customer segmentation analysis using **K-Means Clustering** on customer data. The goal is to divide customers into distinct segments based on their **Age**, **Annual Income**, and **Spending Score**. These insights can help tailor marketing strategies and enhance customer engagement.

The dataset is sourced from Kaggle and contains the following features:
- **CustomerID**: Unique ID for each customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income**: Annual income in thousands of dollars
- **Spending Score**: Score assigned by the mall based on customer behavior and spending nature

---

## Project Workflow

1. **Data Collection and Analysis**  
   - Load and explore the dataset for basic information, including missing values, data types, and summary statistics.
   - Conduct exploratory data analysis (EDA) to understand customer demographics and spending patterns.

2. **Feature Engineering for Clustering**
   - **Income-Spending Clustering**: Segment customers based on their annual income and spending score.
   - **Age-Spending Clustering**: Segment customers based on their age and spending score.
   - **Age-Income-Spending Clustering**: Segment customers based on all three features—age, annual income, and spending score.

3. **Elbow Method for Optimal Cluster Selection**
   - Use the **Elbow Method** to determine the optimal number of clusters for each feature combination.

4. **Visualization and Interpretation**
   - Plot the clusters in **2D** and **3D** to visualize how customers are segmented.
   - Use Power BI to create an interactive report for a deeper understanding of each customer segment.

5. **Exporting Clustered Data**
   - Export the data with cluster labels as a CSV file to be used in Power BI for further analysis and reporting.

---

## Project Structure

```
├── Customer_Segmentation.ipynb     # Jupyter Notebook containing all code and analysis
├── Clustered_Customers.csv         # Exported CSV with cluster labels for each segmentation
├── README.md                       # Project documentation (this file)
└── PowerBI_Report.pbix             # Power BI report with interactive visuals
```

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Segmentation.git
   cd Customer-Segmentation
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Segmentation.ipynb
   ```

4. Open `PowerBI_Report.pbix` in Power BI to explore the interactive visuals.

---

## Key Findings

1. **Income-Spending Clusters**:
   - Identifies groups based on income and spending behavior.
   - Insights into customer purchasing power and spending habits.

2. **Age-Spending Clusters**:
   - Identifies age groups with varying spending scores.
   - Highlights young high spenders, older low spenders, etc.

3. **Age-Income-Spending Clusters**:
   - Combines all three features to create more comprehensive segments.
   - Offers deeper insights into complex relationships between age, income, and spending.

---

## Visualizations in Power BI

The Power BI report contains the following visuals for interactive analysis:
- **Cluster Counts**: Overview of the number of customers in each segment.
- **Income vs. Spending Score**: Scatter plots to show income-spending clusters.
- **Age vs. Spending Score**: Scatter plots for age-spending clusters.
- **3D Scatter Plot**: Age, income, and spending score clusters in 3D.
- **Demographic Analysis**: Gender and age distributions across clusters.

These visuals help uncover insights into customer demographics, spending behavior, and potential target segments.

---

## Future Enhancements

- Apply clustering techniques like **Hierarchical Clustering** or **DBSCAN** for comparison.
- Include additional customer data for more accurate segmentation.
- Develop predictive models to anticipate customer spending trends.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Dataset from Kaggle: [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

This template should provide a good structure for your project documentation on GitHub.
