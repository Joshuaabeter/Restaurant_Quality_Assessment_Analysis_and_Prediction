EATERIES QUALITY ASSESSMENT ANALYSIS AND PREDICTION


This project aims to analyze and predict the quality assessment result of eateries based on various features such as time of assessment, type of assessment, reasons for assessment, eatery location, law, and more.

TABLE OF CONTENTS


Introduction
Data Description
Installation
Usage
Results
Contributing
License

INTRODUCTION


Quality assessment of eateries is crucial for maintaining compliance with health and safety regulations, as well as protecting public health. Utilizing data analysis and prediction, assessment agencies can identify potential risks, target eateries that are most likely to fail the test, and save costs. By analyzing features such as compliance history, violations, and risk history, the quality of eateries can be assessed and the results predicted, and regulatory compliance can be improved.

DATA DESCRIPTION


The dataset used in this eatery industry quality assessment project includes information, on the day of assessment, type of assessment, violations, assessment history, and reasons for violation. The dataset also includes information on the eateries, such as the types of eateries, eatery locations, and eatery ID. The data is sourced from Kaggle. Before analysis, the data was preprocessed to handle missing values, duplicates, and outliers, and ensure consistency

INSTALLATION


To run this project, you will need to install the following dependencies:
Python 3.9
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Plotly Express
Scikit-learn

USAGE


To run the project, simply clone this repository and open the Jupyter Notebook file. Follow the instructions in the notebook to perform data analysis and prediction.

RESULTS


The analysis of the eatery quality assessment results showed that restaurants were the most common type of eatery to fail the quality assessment test. Furthermore, eateries that violated sections 32, 33, and 34 were more likely to fail the assessment. Quality assessment with ID 21868 was the most commonly failed assessment, with canvassing being the primary reason for assessments. The analysis found that the section of the quality law violated and the reasons for assessment, were the main factors in determining an eatery's success or failure in the quality assessment test.
Using machine learning algorithms, such as decision tree classifier, logistics regression, random forest classifier, and SVC, we predicted eatery quality assessment results with an F1 score of 91% based on the above factors. To further enhance data accuracy and prevent overfitting, we conducted cross-validation using K-fold and feature selection with Chi-Square.

CONTRIBUTING


Contributions are welcome! Please open an issue or pull request if you would like to suggest changes or improvements.

LICENSE


None

CONTACT


If you have any questions or comments, please feel free to contact me at Joshuaabupeter@yahoo.com..

