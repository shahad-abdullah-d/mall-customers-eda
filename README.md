# Mall Customers — Exploratory Data Analysis

An exploratory data analysis (EDA) project completed as part of an Artificial Intelligence Bootcamp. The goal is to explore mall customer demographics and spending behavior, assess data quality, and investigate how age and annual income relate to spending score.

## Dataset

The dataset contains **200 customer records and 7 columns**:

* `CustomerID`
* `Gender`
* `Age`
* `Annual Income (k$)`
* `Spending Score (1-100)`
* `Education`
* `Marital Status`

Each row represents one customer. This is an exploratory analysis project, so there is no prediction target or trained machine learning model.

## Tools and Libraries

* Python
* Jupyter Notebook / Google Colab
* Pandas and NumPy
* Matplotlib and Seaborn

## Analysis

The notebook covers:

1. **Data exploration:** Inspecting dataset dimensions, column types, sample records, and descriptive statistics.
2. **Data quality assessment:** Checking missing values, duplicate records, unique customer IDs, invalid numerical values, and categorical consistency.
3. **Distribution analysis:** Using histograms and count plots to explore numerical variables and customer demographics.
4. **Outlier detection:** Using box plots and the Interquartile Range (IQR) method to identify unusual values.
5. **Relationship analysis:** Using a correlation heatmap, scatter plots, and a box plot to examine spending score in relation to age, annual income, and gender.

## Key Findings

* No missing values or duplicate records were found.
* Two annual-income outliers were identified using the IQR method. They were retained because they appeared to represent plausible customer observations rather than data-entry errors.
* Age showed a weak negative correlation with spending score.
* Annual income showed almost no linear correlation with spending score.
* Customers with similar incomes could have different spending scores, suggesting that income alone does not explain spending behavior.

These findings describe the patterns observed in this dataset; they do not establish causal relationships.

## Files

* `Mall_Customers_EDA.ipynb` — Analysis notebook, visualizations, and findings.
* `Mall Customers.xlsx` — Dataset used in the analysis.

## How to Run

1. Open `Mall_Customers_EDA.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. When prompted to upload a file, select `Mall Customers.xlsx`.
4. Continue running the cells to reproduce the analysis and visualizations.

## Future Improvements

* Explore additional visualization techniques.
* Apply customer segmentation methods to investigate different spending patterns.
* Examine additional customer attributes, such as shopping frequency and product preferences, if suitable data becomes available.

## Author

Shahad Abdullah

Artificial Intelligence Bootcamp Project
