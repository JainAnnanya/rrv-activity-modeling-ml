# CS513 Data Mining Project
[Link to the fitness dataset](https://catalog.data.gov/dataset/data-from-a-randomized-controlled-trial-of-positive-outcome-expectancies-during-high-inten-9219d)

AGData.csv is the original Actigraph dataset. RRVData.csv is the original RRV dataset.

AGData_clean.csv is the cleaned Actigraph data. RRVData_clean.csv is the cleaned RRV data.

MergedData_clean.csv is the merged AGData_clean.csv and RRVData_clean.csv.

MergedData_model.csv is just MergedData_clean.csv but made easier to work with for most of the models.

MergedData_clusters_improved.csv is MergedData_model.csv but made easier to work with for K-Means Clustering.

The ANN model is in ANN.ipynb. The CART model is in CART.ipynb. The MiniSOM model is in SOM.ipynb. The SVM model is in SVM.ipynb. The KNN and NB models are in fitness_models.ipynb.

kmeans_clustering_and_SummaryStats.ipynb has the K-means clustering model and visualizations.

fitness_eda.ipynb is our exploratory data analysis file.