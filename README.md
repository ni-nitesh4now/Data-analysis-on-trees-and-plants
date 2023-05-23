# Data-analysis-and-Clustering-on-trees-and-plants

This repository contains Python scripts for data analysis and clustering using various techniques. It demonstrates the use of libraries like pandas, numpy, matplotlib, scikit-learn, and scikit-fuzzy.

## Prerequisites

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- scikit-fuzzy

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/username/repo.git
   cd repo
   ```

2. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   ```

## Usage

### Data Expansion and Preprocessing

1. Prepare the dataset:

   - Make sure the data CSV files (`data2.csv`, `expanded_dataset.csv`, `expanded_dataset2.csv`) are present in the same directory as the scripts.

2. Run the scripts:

   - `data_expansion_1.py`: Performs data scaling, random perturbations, and synthetic data generation on `data2.csv` to create `expanded_dataset.csv`.
   - `data_expansion_2.py`: Performs additional data scaling, random perturbations, and synthetic data generation on `expanded_dataset.csv` to create `expanded_dataset2.csv`.

3. The expanded datasets will be saved as `expanded_dataset.csv` and `expanded_dataset2.csv` respectively.

### Linear Regression

1. Prepare the dataset:

   - Make sure the `expanded_dataset2.csv` file is present in the same directory as the script.

2. Run the script:

   ```shell
   python linear_regression.py
   ```

3. The script will perform linear regression on the input features (Area, Temperature, Humidity, CS) and target variable (O2). It will generate a scatter plot of the actual vs. predicted O2 production and display the mean squared error and R-squared value.

### K-means Clustering

1. Prepare the dataset:

   - Make sure the `data2.csv` file is present in the same directory as the script.

2. Run the script:

   ```shell
   python kmeans_clustering.py
   ```

3. The script will perform k-means clustering on the features (Area, Temperature, Humidity, CS, O2) and generate a scatter plot showing the clusters. The names of the data points will be displayed near each point.

### Hierarchical Clustering

1. Prepare the dataset:

   - Make sure the `data2.csv` file is present in the same directory as the script.

2. Run the script:

   ```shell
   python hierarchical_clustering.py
   ```

3. The script will perform hierarchical clustering on the features (Area, Temperature, Humidity, CS, O2) and generate a dendrogram visualization.

### Fuzzy C-means Clustering

1. Prepare the dataset:

   - Make sure the `data2.csv` file is present in the same directory as the script.

2. Run the script:

   ```shell
   python fuzzy_cmeans_clustering.py
   ```

3. The script will perform fuzzy c-means clustering on the features (Area, Temperature, Humidity, CS, O2) and generate a scatter plot showing the clusters.

### DBSCAN Clustering

1. Prepare the dataset:

   - Make sure the `data2.csv` file is present in the same directory as the script.

2. Run the script:

   ```shell
   python dbscan_clustering.py
   ```

3. The script will perform DBSCAN clustering on the features (Area, Temperature, Humidity, CS, O2
