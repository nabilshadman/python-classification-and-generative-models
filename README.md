# Classification and Generative Models  
This is an applied machine learning project developed that consists of two parts:  
(1) Analysis and classification of a music genre data set  
(2) Generative models and parameter inference  

The project uses Python's data science stack (i.e. numpy, pandas, matplotlib, scikit-learn, jupyter). 

## Part 1: Analysis and classification of a music genre data set  
For part 1, we use a modified version of the [GTZAN Dataset - Music Genre Classification](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification). The data set is a collections of music of 10 genres and each genre has 100 music samples of parameterised features. Our work demonstrates the implementation and evaluation of various classification algorithms. It covers models such as Logistic Regression, Support Vector Machines (SVM), Decision Trees, and Random Forests. The notebook includes data preprocessing steps, model training on a given dataset, and evaluation using performance metrics like accuracy, precision, recall, and F1-score. It provides a comparative analysis of the different classifiers, allowing users to understand the strengths and weaknesses of each model in a classification task.  


## Part 2: Generative models and parameter inference  
For part 2, we consider multivariate Gaussian distributions. We generate samples from a distribution, estimate the parameters of the model (i.e. distribution). We then carry out classification experiments on the data of two classes to find how a limited number of training samples has an impact on the classification. We also consider Gaussian mixture models (GMMs).

