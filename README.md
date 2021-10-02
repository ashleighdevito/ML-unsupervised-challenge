# ML-unsupervised-challenge

This project utlized machine learning to determine if it is possible to categorize cryptocurrencies based on similar characteristics.  

Data is read into Panas and the data is prepped for algorithms by:

    retaining only actively traded cryptocurrencies
    removing null values
    including cryptocurrencies that have been practically mined to a value of at least one coin
    converting all values to numeric
    standardizing the data through scaling
    
The number of dimensions are then reduced through a PCA model.

Final dimensions are reduced to two through a t_SNE, which are then plotted to investigate if there are clusters.

A cluster analysis is then performed by plotting an elbow plot to determine an optimal number of clusters using k-Means.

Results indicate it is impractical to categorize the various types of cryptocurrency.
    
