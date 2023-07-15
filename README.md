# 1. Classification and Generative Models  
This is an applied machine learning project that consists of **two** parts:  

(1) Analysis and **classification** of a music genre data set  
(2) **Generative** models and parameter inference  

We use Python's data science stack (i.e. numpy, pandas, matplotlib, scikit-learn, jupyter) for this work.  

## 2. Analysis and Classification of Music Genre Dataset (Part 1)  
For part 1, we use a modified version of the [GTZAN Dataset - Music Genre Classification](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification). The dataset is a collection of music of 10 genres and each genre has 100 music samples of parameterised features. Our work demonstrates the application and evaluation of classification algorithms (e.g. Logistic Regression, Support Vector Machines). The notebook includes exploratory data analysis, data preprocessing, model training, and evaluation. It provides a comparative analysis of the classifiers, allowing users to understand the strengths and weaknesses of each model in the classification task.  


## 3. Generative Models and Parameter Inference (Part 2)  
For part 2, we shift focus to multivariate Gaussian distributions. We generate samples from a distribution and estimate the parameters of the model (i.e. distribution). We then carry out classification experiments on the data of two classes to find how a limited number of training samples has an impact on the classification. We also consider Gaussian mixture models (GMMs), where given a set of observations, we identify the GMM (i.e. find the most probable values of the parameters).  


## 4. Run Notebook
We recommend installing **Anaconda Distribution** before running the notebook as Anaconda provides a powerful package management system called Conda, which can handle complex software environments and ensures compatibility between different packages. Conda simplifies the setup process and avoids version conflicts.  

(1) Download Anaconda Distribution from this [page](https://www.anaconda.com/download) and run the installer.  

(2) Once installation is finished, launch Anaconda Navigator, which provides a graphical user interface to manage your Anaconda environment.  

(3) In Anaconda Navigator, you should see a button labeled "Launch" under the Jupyter Notebook section. Click on it to start Jupyter Notebook in your default web browser.  

(4) Navigate to the directory of this project in your system.  

(5) Open the notebook ([classification_and_generative_models.ipynb](https://github.com/nabilshadman/python-classification-and-generative-models/blob/main/classification_and_generative_models.ipynb)).   

(6) In the toolbar, click on the option "Run" and then select "Run All Cells" from the dropdown menu. The notebook will start executing each cell sequentially from top to bottom.    
