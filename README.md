# Data Mining Exam Files

This folder contains files related to the Data Mining exam. The materials included here are intended for reference and use for the exam.

## Authors
- Stefano Baroni (steba@itu.dk)
- Matteo Mormile (matmo@itu.dk or matteo.mormile@mail.polimi.it)

## Contents
- **Motor_Vehicle_Collisions-Crashes.csv**: Original dataset **not** included, to be downloaded at the following link: https://catalog.data.gov/dataset/motor-vehicle-collisions-crash

- **DataMiningExam.ipynb**: This file includes the code use for Data Mining exam.

- **processed_data.csv**: Dataset after data preparation processing.

- **reconstructed_data.csv**: Contains collision data after applying Random Forest Classification on unspecified values of processed_data.csv.

- **PCA_Components.npy**: This file contains the data about the first 9 components extracted with PCA from reconstructed_data.csv.

- **PCA_Components_Sampled.npy**: Contains the data about the first 9 components extracted with PCA from the first 15000 rows of reconstructed_data.csv.

- **Encoded_Data.npy**: Containts the first 15000 encoded rows of reconstructed_data.csv.

- **interactive_graph.html**: Interactive graph of K-Means clustering using first 3 principal components.

- **interactive_graph_medoids.html**: Interactive graph of K-Medoids clustering using first 3 principal components.
