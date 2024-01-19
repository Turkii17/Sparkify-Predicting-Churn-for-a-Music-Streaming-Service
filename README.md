# Sparkify: Predicting Churn for a Music Streaming Service

## Installations
- NumPy
- Pandas
- Seaborn
- Matplotlib
- PySpark SQL
- PySpark ML

No additional installations beyond the Anaconda distribution of Python and Jupyter notebooks.

## Project Motivation
For this project, the aim was to predict customer churn for a fictional music streaming company, Sparkify.

The project involved the following steps:
1. Loading and cleaning a small subset (128MB) of a full dataset available (12GB).
2. Conducting Exploratory Data Analysis to understand the data and identify features useful for predicting churn.
3. Feature Engineering to create features for the modeling process.
4. Modeling using machine learning algorithms such as Logistic Regression, Random Forest, Gradient Boosted Trees, Linear SVM, and Naive Bayes.

## File Descriptions
There is one exploratory notebook and an HTML file of the notebook to showcase the work in predicting churn. Markdown cells were used throughout to explain the process taken.

## Medium Blog Post
The main findings of the code can be found in the [Medium Blog post]([https://medium.com/@turkiabalzahrani/sparkify-predicting-churn-for-a-music-streaming-service-821fda0adf74](https://medium.com/@turkiabalzahrani/guide-on-predicting-churn-using-pyspark-8a0c1e2020c2)) explaining the technical details of the project. A Random Forest Classifier was selected as the best model based on evaluating F1 score and accuracy metrics. The final model achieved an F1 and Accuracy score of 0.88.

## Licensing, Authors, Acknowledgements, etc.
I would like to acknowledge Udacity for the project idea and workspace.
