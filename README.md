# ISRO-project
I'm working on garbage volume estimation using multi view images project under ISRO. 
I am exploring various algorithms for image classification. 

# k-NN Algorithm
I have currently tried out k-NN algorithm on MNIST data set using scikit-learn. K-NN algorithm is a supervised machine learning algorithm. This means the model requires no training, and can get right to classifying data.
To classify some given data point, p, a K-NN model will first compare p to every other point it has available in its data base using some distance metric.
Two points with smaller distance between them are more similar than two points with a larger distance between them. This is the central idea behind K-NN.
This process will return an unordered array, where each entry in the array holds the distance between p and one of the n data points in the models data base.
k is some arbitrary value selected (usually between 3–11) that tells the model how many most similar points to p it should consider when classifying p. The model will then take those k most similar values, and use a voting technique to decide how to classify p, as exemplified by the image below.

# about scikit-learn
Scikit-learn (formerly scikits.learn) is a free software machine learning library for the Python programming language.It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.
The sklearn.datasets package embeds some small toy datasets as introduced in the Getting Started section.
sklearn.neighbors provides functionality for unsupervised and supervised neighbors-based learning methods. 
The sklearn.metrics module includes score functions, performance metrics and pairwise metrics and distance computations.
	
	
	
	
	
