# KMeans Clustering on Country Data

## Description
This project performs KMeans clustering on a dataset of various country indicators. The primary goal is to identify patterns and group countries into clusters based on their socio-economic features. KMeans clustering is a form of unsupervised learning which is useful in identifying structure and patterns within the data.  

## Table of Contents
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
  - [1. Load and Preprocess Data](#1-load-and-preprocess-data)
  - [2. Feature Selection](#2-feature-selection)
  - [3. Scaling the Data](#3-scale-data)
  - [4. Determine the Optimal Number of Clusters](#4-determine-optimal-clusters)
  - [5. Fit and Visualize Clusters](#5-fit-and-visualize-clusters)
  - [6. Conclusion](#6-conclusion) 
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
#1-load-and-preprocess-data
  - Import the dataset 'Country-data.csv'
  - Identify missing data and non-numerical columns for further preprocessing
2. Feature Selection
  - Create a correlation map of features and explore relationships between them
  - Identify and generate scatter plots of the features with strongest correlations (e.g. Child mortality and GDPP)
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/aac8be71-046c-420e-8a95-6f99c5e65137)
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/12cea7c3-35bf-4a6c-a25f-1b498bdda0b4)
3. Scaling the Data
  - Determine the distrubtion of the data and scale the data
4. Determine the Optimal Number of Clusters
  - Plot the elbow curve:
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/7c3763f2-700c-46e4-829c-b37c49b9afef)
  - Plot the silhouette score method:
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/27f08524-6e4e-4263-a7d3-f8c8f8e6644f)
  - Use the two graphs to determine the best k value
5. Fit and Visualise Clusters
  - Fit a KMeans model with the selected number of clusters
  - Label the groups of countries based on the clusters
  - Add the predicted cluster label column to the original dataframe
  - Determine the silhouette score
  - Visualise the clusters with selected scatter plots
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/b06627c1-507b-4561-ab55-4e246e717014)
  ![image](https://github.com/brindamamidi/CodingTasks/assets/164925546/39a202b1-9f54-4714-911f-c5a7efaa6167)
6. Conclusion
  - Analyze the clusters including the strengths and limitations of the model

## Credits
This code was written by Brinda Mamidi. If you have any questions or feedback, feel free to reach out.


  

  
