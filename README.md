Missing Value Imputation:


1. Mean Imputation
When to Use:
Use when the data is normally distributed and does not have significant outliers.

Why:
It's simple, fast, and works well when all values are centered around the mean. However, it can distort data variability and be misleading in the presence of outliers.

2. Median Imputation
When to Use:
Suitable when data is skewed or contains outliers.

Why:
Median is a more robust statistic than mean—it is not affected by extreme values, making it better for maintaining realistic distributions in such cases.

3. Mode Imputation
When to Use:
Best for categorical or categorical-like numeric data (e.g., 1/0, rating scores) where values are repeated.

Why:
Helps maintain the most common pattern in the dataset, but can create bias if one value is overly frequent.

4. K-Nearest Neighbors (KNN) Imputation
When to Use:
Use when you have multiple related features (i.e., features are correlated) and moderate-sized datasets.

Why:
KNN captures local structure in the data and imputes missing values by looking at similar instances. It’s more intelligent than simple statistics, but requires scaling and can be computationally intensive.

5. Regression-Based Imputation
When to Use:
Recommended when the feature with missing values is strongly correlated with other variables.

| Method     | Math Concept          | Robust to Outliers | Uses Other Features | Best For             |
| ---------- | --------------------- | ------------------ | ------------------- | -------------------- |
| Mean       | Arithmetic Mean       | ❌                  | ❌                   | Normal distributions |
| Median     | Middle Value (Sorted) | ✅                  | ❌                   | Skewed/Outlier-prone |
| Mode       | Most Frequent Value   | ✅                  | ❌                   | Categorical/Discrete |
| KNN        | Distance Averaging    | ✅                  | ✅                   | Multivariate data    |
| Regression | Predictive Modeling   | ⚠️ Model-dependent | ✅                   | Predictable features |












