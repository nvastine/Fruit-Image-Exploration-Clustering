# Fruit-Image-Exploration-Clustering
This was my final project for CU Boulder's DTSA 5510 Unsupervised Algorithm in Machine Learning course.

The project goal was to classify fruit images from [this Fruit Classification Set](https://www.kaggle.com/datasets/sshikamaru/fruit-recognition/data) using clustering methods. The project compared manual feature reduction methods on the result of classification, comparing isolating greyscale value/intensity information to an approach based on color histograms. 

After manual feature reduction, the datasets were scaled and further reduced using PCA to explain 90% of data variance.

K-means clustering analysis compared results of the two reduction methods, then compared to an agglomerative clustering method. Further hyperparameter tuning was performed to identify the k-means elbow number of clusters.

Finally results were visualized using PCA plots and random image sampling.
