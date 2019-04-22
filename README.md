# Video-Games-Sales-Prediction 
   To accurately predict the Global Sales in Video Games.
   
# Install
This project requires python 3.6 or higher versions of python, along with these libraries :
* [Numpy](https://www.numpy.org)
* [Pandas](https://pandas.pydata.org)
* [Matplotlib](https://matplotlib.org)
* [scikit-learn](https://scikit-learn.or/stable/)
* [seaborn](https://seaborn.pydata.org/installing.html)
* [TensorFlow](https://www.tensorflow.org/install)

You will also need to have software installed to run and execute a [Jupyter Notebook](https://jupyter.org/)

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has 
the above packages and more included.

# Dataset
   The dataset is obtained from Kaggle.Here is the link,
   https://www.kaggle.com/gregorut/videogamesales
   
# Description of the repository
This repository contains 3 notebooks
  1. Data Visualization-Video Games Sales Dataset.ipynb:
      This notebook contains the code for data visualization of the given dataset.Before running this notebook make sure you have      installed seaborn.
      
  2. Linear Regression-Video Games Sales Dataset.ipynb: 
      This notebook contains implementation of the dataset using Multivariate Linear Regression.
      
  3. Linear Regression with SKlearn-Video Games Sales Dataset.ipynb:
      This notebook contains Scikit-learn implementation using Multivariate Linear Regression.
      
  4. Keras- Video Games Sales Dataset.ipynb:
      This notebook conatins Neural Network implementation using Keras. 

# Run
In the anaconda promt, navigate to the top-level project directory and run one of the following commands:

      jupyter notebook "Data Visualization-Video Games Sales Dataset.ipynb"
      
      jupyter notebook "Linear Regression-Video Games Sales Dataset.ipynb"
      
      jupyter notebook "Linear Regression with SKlearn-Video Games Sales Dataset.ipynb"
      
      jupyter notebook "Keras-Video Games Sales Dataset.ipynb"
      
This will open the Jupyter Notebook software and project file in your browser.

# Attribute information

* Rank - Ranking of overall sales
* Name - The games name
* Platform - Platform of the games release (i.e. PC,PS4, etc.)
* Year - Year of the game's release
* Genre - Genre of the game
* Publisher - Publisher of the game
* NA_Sales - Sales in North America (in millions)
* EU_Sales - Sales in Europe (in millions)
* JP_Sales - Sales in Japan (in millions)
* Other_Sales - Sales in the rest of the world (in millions)
* Global_Sales - Total worldwide sales.

# Output Variable( Desired Target)
  Global_Sales: To predict the Worldwide Sales
  
# Models Trained 
  | Training Model  | Root mean squared error |
  | ----------------| ------------------------|
  | Linear Regression | 0.0138  |
  | Using Sklearn     | 0.0216  |
  | Using Keras       | 0.0216  |
