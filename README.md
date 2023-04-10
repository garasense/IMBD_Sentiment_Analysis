<h1 align="center">IMDB Sentiment Analysis</h1>
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/69/IMDB_Logo_2016.svg"></img>
</p>

## Project's Background
IMDb is the world's most popular and authoritative source for movie, TV, and celebrity information. Watch trailers, get showtimes, and buy tickets for upcoming films. Rate and review shows you've seen and track what you want to watch using your Watchlist. The large number of reviews obtained by IMDb is the reason for the company to carry out an analysis regarding the sentiments given by the audience, so that the company can find out positive or negative responses.

The company asked a data scientist to do a sentiment analysis of the reviews it obtained based on 50k samples.

1. What is the proportion of positive and negative sentiment?
2. What are the words that appear the most in negative and positive sentiments?
3. What kind of preprocessing techniques can be done for this dataset?
4. Classification whether a review is a negative or positive sentiment
---
## Objectives
Create a Classification model for sentiment analysis using the Recurrent Neural Network Algorithm

*This project* is done in *notebook* format with/or with *deployment model* (optional) with the following *mandatory criteria*:

1. The Deep Learning framework used is *Tensorflow*.

2. There is use of a visualization library, such as *matplotlib*, *seaborn*, or others.

3. The contents of *notebook* must follow the *outline* below:
    1. Introductions
       > The introductory chapter must be filled with identity, a big picture of the dataset used, and the *objective* you want to achieve.
   
    2. Import Libraries
       > The first *cell* in *notebook* **must contain and contain only** all *libraries* used in *project*.
   
    3. Data Loading
       > This section contains the data preparation process prior to further data exploration. The Data Loading process can be in the form of giving a new name to each column, checking the size of the dataset, etc.
   
    4. Exploratory Data Analysis (EDA)
       > This section contains data exploration in the dataset above by using queries, groupings, simple visualizations, and so on.

    5. Data Preprocessing
       > This section contains the process of preparing data for the model training process, such as dividing data into train-dev-test, data transformation (normalization, encoding, etc.), and other processes needed.
   
    6. Model Definition
       > This section contains cells to define the model. Explain the reasons for using an algorithm/model, the hyperparameters used, the types of metrics used, and other things related to the model.

    7. Model Training
       > Cells in this section only contain code to train the model and the resulting output. Do the training process several times with different hyperparameters to see the results obtained. Analyze and narrate these results in the Model Evaluation section.
   
    8. Model Evaluation
       > In this section, a model evaluation is carried out which must show how the model performs based on the selected metrics. This should be proven by visualizing performance trends and/or model error rates. **Perform analysis related to the results on the model and write down the results of the analysis**.

    9. Model Saving
       > By looking at the model evaluation results, choose the best model to save. This best model will be reused in deploying on Heroku.
   
    10. Model Inference
        > Models that have been trained will be tried on data that is not included in the train-set or test-set. This data must be in the original format, not data that has been scaled.
   
    11. Conclusion
        > In this last section, **must contain** conclusions that reflect the results obtained with the *objective* that has been written in the introduction section.
