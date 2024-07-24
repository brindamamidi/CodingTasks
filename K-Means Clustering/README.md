# KMeans Clustering on Country Data

## Description
This project performs KMeans clustering on a dataset of various country indicators. The primary goal is to identify patterns and group countries into clusters based on their socio-economic features. KMeans clustering is a form of unsupervised learning which is useful in identifying structure and patterns within the data.  

## Table of Contents
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
  1. Load and Preprocess Data
  2. Feature Selection
  3. Scaling the Data
  4. Determine the Optimal Number of Clusters
  5. Fit and Visualize Clusters
  6. Conclusion 
- [Credits](#credits)
  
## Installation
To run this project locally, you need to have Python installed along with the following libraries:
- pandas
- matplotlib
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas matplotlib scikit-learn
```

## Usage
### 1. Load and Preprocess Data
  - Import the dataset 'Country-data.csv'
  - Identify missing data and non-numerical columns for further preprocessing
### 2. Feature Selection
  - Create a correlation map of features and explore relationships between them
    ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/fb96422d-0faa-4f15-a0f1-349378d84fa5)
  - Identify and generate scatter plots of the features with strongest correlations (e.g. Child mortality and GDPP)
    ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/cd2ccacd-f41a-44e3-9e5f-2d962acd1f9b)
### 3. Scaling the Data
  - Determine the distrubtion of the data and scale the data
### 4. Determine the Optimal Number of Clusters
  - Plot the elbow curve and the silhouette score method
    
   ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/257a8f0b-94ac-49ee-bafa-594e90d98c0a) ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/fb2b7dce-0e2c-4594-86c5-7400cc0d9093)
  - Use the two graphs to determine the best k value
### 5. Fit and Visualise Clusters
  - Fit a KMeans model with the selected number of clusters
  - Label the groups of countries based on the clusters
  - Add the predicted cluster label column to the original dataframe
  - Determine the silhouette score
  - Visualise the clusters with selected scatter plots
    
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/fec77ca8-d8e0-4b20-a409-6dcd1a801602)
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/62d6c222-b07f-4fe7-a01e-ee89978a63ed)
  
### 6. Conclusion
  - Analyze the clusters including the strengths and limitations of the model

## Credits
This code was written by Brinda Mamidi. If you have any questions or feedback, feel free to reach out.


  

  
