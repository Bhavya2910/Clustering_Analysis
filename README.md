# Clustering Analysis

This project conducts a comprehensive clustering analysis on the well-known Iris dataset employing diverse clustering techniques, including K-Means, Hierarchical, and Spectral Clustering. The investigation encompasses the assessment of clustering performance metrics across different preprocessing methods and explores the impact of varying the number of clusters.

The primary goal is to gain insights into the dataset's inherent structures and patterns, providing a valuable exploration of clustering methodologies and their effectiveness in uncovering meaningful groupings within the Iris dataset.

## **Key Features**
Utilizes PyCaret and scikit-learn for seamless clustering setup and analysis.

Evaluates clustering performance using metrics such as silhouette, Calinski-Harabasz, and Davies-Bouldin scores.

Explores the influence of different preprocessing methods and varying cluster counts on the clustering results.

## **Results**
![image](https://github.com/Bhavya2910/Clustering_Analysis/assets/99804770/e1f7b7d8-89ac-498a-a497-03757fe81a1d)

## **Prerequisites**
Make sure to install the necessary libraries before running the script by executing the following command:

```bash
pip install pycaret
```

## Code Overview
### 1. Importing Libraries
The required libraries are imported, including pandas, numpy, pycaret, and several scikit-learn modules.
### 2. Loading Dataset
The Iris dataset is loaded using scikit-learn's load_iris function, and a pandas DataFrame is created from the dataset.
### 3. Clustering Setup
The PyCaret library is used to set up the clustering environment (clu_setup) for subsequent analysis.
### 4. Model Evaluation 
Model Evaluation Function computes silhouette, Calinski-Harabasz, and Davies-Bouldin scores for a given clustering model.
### 5. Clustering Parameters
Lists of clusters and preprocessing methods are defined for the analysis.
### 6. Results DataFrames
Separate DataFrames are initialized to store results for each clustering technique: kmeans_results_df, hierarchical_results_df, and spectral_results_df.
### 7. Clustering Analysis Loop
The script performs clustering analysis for each technique and stores the results in the respective DataFrames. The analysis includes varying preprocessing methods and the number of clusters.
### 8. Combining Results
The results from each technique are combined into a single DataFrame (combined_transposed_df) with a separator DataFrame (separator_df) between them.
### 9. Saving Results
The combined results are saved to a CSV file named combined_results_transposed.csv.

## **How to Run**
Install the required libraries using pip install pycaret.

Run the script.

Review the combined transposed results saved in combined_results_transposed.csv.


Feel free to customize the script for different datasets, clustering techniques, or preprocessing methods.
