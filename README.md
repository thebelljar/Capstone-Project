# Capstone Project: Sparkify
Udacity's Data Science for Enterprise nanodegree final project

## Project motivation
For the final project for my Data Science nanodegree, we had the opportunity to learn about and use Spark. The dataset was provided by Udacity and represented users' interaction with a music streaming service. There were options of using the full (12GB) dataset or medium (242MB) or small (128MB) subsets of that data. I picked the medium dataset and used IBM Watson Studio with Spark to analyse that data.

The aim of the project was to predict when and which customers would churn i.e. downgrade their membership from paid to free level. This exercise mimics real world situation where many companies want to prevent their customers from existing their paying membership and hence offer deals just when the user is potentially at risk of churning.

## Libraries
Below is a list of installations neccessary to carry out the project:
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Pyspark
6. Datetime

## Files
1. Sparkify: main and only jupyter notebook that contains all of the analysis and commentary

## Results
Gradient Boosted Tree came out with the highest F1 score 86%, which is 22% over the baseline performance of predicting a 0 label for all the users. Top three features that came out as being the most important ones were:
- Average songs played
- Number of thumbs down given
- Total sessions
which were expected because they highlight users' enagagement with the service. 


## Acknowledgements
The data was provided by Udacity (https://www.udacity.com/) and the notebook was hosted on IBM cloud.
