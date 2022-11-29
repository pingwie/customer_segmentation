# Customer Segmentation
Differentiating potential customers is an essential task for organizations. It helps them to increase their revenue and tailor their services to the right customers, while helping them to understand why certain segments of people do not use their services.

Marketing campaigns are more effective the more targeted they are to potential customers. Targeted marketing is the process of identifying customers and promoting products and services through media to reach the right group of potential customers. This type of marketing is based on segmentation..
## Table of contents
1. [Project](#project)
2. [Dataset](#dataset)
3. [Files](#files)
4. [Libraries](#libraries)
5. [Results](#results)

## Project <a name="project"></a>
In this project we are going to use real data from Arvato Financial Solutions GmbH, to find potential customers for a mail order company.  
This project consists of two phases.  
In the first phase, we aim to create a customer segmentation using unsupervised learning.  
In the second phase, our goal is to predict the response to the mail-order campaign using unsupervised learning.

## Dataset <a name="dataset"></a>
In this project we are going to use real data from *Arvato Financial Solutions GmbH*, to find potential customers for a mail order company.
We have 3 sets of data:  
Demographics data for customers of the mail-order company.  
Demographics data for the general population of Germany.
Demographics data for individuals who were targets of a marketing campaign: `mailout_train.csv` and `mailout_test.csv`  
A couple of additional files are included, which provide information on the demographic information contained in the datasets: `DIAS Attributes - Values 2017.xlsx` and `DIAS Information Levels - Attributes 2017.xlsx`.  

## Files <a name="files"></a>
| - proyect_notebook.ipynb # The main jupyter notebook  with ETL pipeline, the model and evaluation.  
| - readme.md  

## Libraries used <a name="libraries"></a>
1. Numpy
2. Pandas
3. Sckit-Learn
4. Matplotlib
5. Seaborn
5. hermetrics
6. XGBoost


## Results <a name="results"></a>
The main findins of the code can be found at the post avaible [here](https://medium.com/@pingwie/customer-segmentation-366f3a407012).  
This project was part of a kaggle competition. Although the competition is over, you can still submit your results for evaluation.
You can access the competition [here](https://www.kaggle.com/c/udacity-arvato-identify-customers/leaderboard)  


