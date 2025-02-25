# Advanced-EDA-For-Genomic-Data-Analysis

This project aims to perform advanced exploratory data analysis (EDA) on genomic data to identify genetic variations using various visualization techniques. The goal is to gain insights into the underlying patterns and relationships within the genomic data, which can aid in understanding genetic variations and their implications.

Key Components:

File Upload and Data Preparation:

The project allows users to upload their own CSV files containing genomic data. In the absence of a file upload, synthetic data is generated for demonstration purposes, comprising 10 gene features, a target variable, and additional demographic columns (Age, Gender, Ethnicity).

Data Preview and Summary Statistics:

A comprehensive preview of the dataset is provided, including the shape of the data and summary statistics for numeric columns. This step helps users get an initial understanding of the dataset's structure and basic statistics.

Correlation Heatmap:

A correlation matrix is computed and visualized using a heatmap, showcasing the relationships between different numeric features in the dataset. This visualization highlights the strength and direction of correlations between gene features.

Basic EDA:

Essential exploratory data analysis is performed to check for missing values and analyze the class distribution of the target variable. Additionally, the distribution of single nucleotide polymorphisms (SNPs) is visualized to identify variations within specific genes.

Dimensionality Reduction and Visualization:

Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) are applied to reduce the dimensionality of the genomic data. The results are visualized in scatter plots, enabling users to observe patterns and clusters within the data based on the target variable.

Machine Learning Model:

A Random Forest classifier is trained on the genomic data to predict the target variable. The model's performance is evaluated using accuracy scores and a classification report, providing insights into its effectiveness and potential applications.

Conclusion: Through advanced EDA, visualization, and machine learning, this project offers a comprehensive approach to analyzing genomic data. The visualizations and model help in identifying genetic variations, understanding data patterns, and making informed decisions based on the analysis
