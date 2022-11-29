# Covid-19-detection-using-Machine-Learning
This project aims to compare different machine learning algorithms like K-nearest neighbors, Random forest and Naive Bayes with respect to their accuracies and then use the best one among them to develop a system which predicts whether a person has COVID or not using the data provided to the model.

<ins>Methodology</ins> - 
The proposed methodology consists of 4 steps. In step 1 data
collection is being performed and step 2 gives an overview of
preprocessing, step 3 exploratory analysis is being performed
to understand the data set, step 4 includes
the hyperparameter tuning by grid search CV, step 5 includes implementing various predictive models and step 6 includes using performance metrics for effective analysis of the models
* <ins>Data Collection</ins> - 
Procured a data set from kaggle.com and it has 5434 × 21 rows of
columns. This dataset contains 20 variables that could be
determinants in the prediction of COVID-19, as well as one
class attribute that defines if COVID-19 is found.
* <ins>Data Preprocessing </ins>- 
Preprocessing of data is an essential step in which
we clean the data and make it compatible i.e. suitable to be
used in a machine learning model. This also enhances the
accuracy and efficiency of the model.
  * <ins>Removing features</ins>: From the figure 2 we can conclude
that wearing masks and sanitization from the market are two
features that have only one value that is ‘no’ as they don’t
affect our predictions we can simply just drop those columns
off our dataset.
  *<ins> Encoding Categorical Data </ins>: Labeling Coding is
a popular form of code flexible code management for
categories. In this process, each label is given a whole
number based on alphabetical order. All attributes of our
dataset are of ‘yes’ or ‘no’ type so we have used label
encoding to convert it to 0 and 1 for the model to understand
the dataset better. Table 4 shows the dataset after applying
label encoding.
  * <ins>  Splitting the Dataset </ins>: 
  We divided the data into an 80:20 split.We take all the 20 independent
attributes into x and the dependent column ‘COVID-19’ into
y as we aim to predict if the patient is COVID positive or not.
*<ins> Exploratory Data Analysis </ins>:
Exploratory data analysis is used to evaluate various datasets
with the aim of summarizing them based on their key characteristics. This summary can be visualized using statistical
graphics and other data visualization techniques.
* <ins>Hyperparameter tuning by grid search CV </ins>: 
Its main goal is to discover the optimal parameters where
the model’s efficiency is the best or highest and the error rate is
the minimum. We have used the gridsearchcv tool to produce
the best combination of parameters, based on accuracy score
as the scoring metric when all the different parameters are fed
into the parameter grid
*  <ins>IMPLEMENTATION</ins> : 
In our project, we use various classification algorithms to predict
and use a grid search CV to find the most advanced solution
for each algorithm. Some of the categorization algorithms that
have been employed include:
	* Logistic Regression
	* KNN
	* Random forest
* <ins> Performance evaluation</ins> : 
 To evaluate the effectiveness of the Machine Learning
algorithms applied in this experiment, we decided to adopt
the Accuracy, Mean squared error, Precision, Recall and
F-Measure which are widely used in domains such as
information retrieval, machine learning and other domains
that involve binary classification.

  

