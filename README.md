
# Identifying Age-Related Conditions
- This project focuses on prediction Identifying Age-Related Conditions. The project includes machine learning, exploratory data analysis (EDA), and data visualization techniques to gain insights into the dataset and understand its patterns. The project uses the train.csv dataset, which can be downloaded from Kaggle:
https://www.kaggle.com/competitions icr-identify-age-related-conditions/data




## DATA CONTENT
### Analysis of data columns to identify independent and dependent variables:

* The competition data comprises over fifty anonymized health characteristics linked to three age-related conditions. Your goal is to predict whether a subject has or has not been diagnosed with one of these conditions -- a binary classification problem.

* Note that this is a Code Competition, in which the actual test set is hidden. In this version, we give some sample data in the correct format to help you author your solutions. When your submission is scored, this example test data will be replaced with the full test set. There are about 400 rows in the full test set.

### Files and Field Descriptions
##### train.csv - The training set.
* Id Unique identifier for each observation.
* AB-GL Fifty-six anonymized health characteristics. All are numeric except for EJ, which is categorical.
* Class A binary target: 1 indicates the subject has been diagnosed with one of the three conditions, 0 indicates they have not.
##### test.csv - The test set. 
* Your goal is to predict the probability that a subject in this set belongs to each of the two classes.

* Epsilon The date the data for this subject was collected. Note that all of the data in the test set was collected after the training set was collected.
## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scipy
- Sklearn

- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn 
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

1. IMPORTING LIBRARIES

2. LOADING DATASET

3. DATA DESCRIPTION

4. EXPLORATORY DATA ANALYSIS

5. FEATURE ENGINEERING

6. MISSING VALUES

7. DATA VISUALIZATION

8. OUTLIER DETECTION

9. DATA PREPROCESSING

10. MODEL TRAINING AND EVALUATING

11. FEATURE IMPORTANCE

12. AUC-ROC

13. MODEL TUNING

14. CONCLUSION


 The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 

* After I have done the Exploratory Data Analysis, I have found out that there are outliers in the dataset. I have used the IQR method to fill the outliers with median. And then I have done data visualization to get insight from data.  I have tried models like RandomForestClassifier, LogisticRegression, KNeighborsClassifier, SVC, GaussianNB, DecisionTreeClassifier, AdaBoostClassifier, GradientBoostingClassifier, XGBClassifier. After model tuning , I got %94.62 accuracy score from GradientBoostingClassifier.



