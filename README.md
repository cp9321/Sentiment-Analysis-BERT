# Sentiment Analysis with a Google BERT's fine tuning
> 

## Introduction
This project is born for the Laboratory of Data Mining, which is given as an add-on to the Data Mining course in the Master’s Degree in Computer Engineering at the University of Florence.

The aim of this project is to go into detail of Google BERT, which was one of the final leftover topics of the base course, and try an application of it in Sentiment Analysis, with the ultimate goal to fine tune it.


## Technologies and Launch
The code it’s written in Python, and uses Hugging Face transformers libraries for the specific functionalities.

It’s strongly recommended to launch it using a GPU, to keep the execution time reasonable. If you don’t have one, you can use Google Colab.


## Screenshots
<img width="1098" alt="Schermata 2024-03-11 alle 18 34 28" src="https://github.com/cp9321/Sentiment-Analysis-BERT/assets/126768526/745e9829-1f03-4d39-bb1b-3a2f1790128d">


## Setup and Usage
The files in this repository are in .ipynb format so they're Jupyter Notebooks, and you can simply open them by importing in Google Colab. 

In the BERT_Fine_Tuning.ipynb file you’ll find a dataset analysis, the tokenizer setting and BERT model in its final fine tuning, the training and finally the evaluation and the prediction of new examples, with step by step cell of code.  
In the BERT_Base.ipynb file you'll find a base version of the tuning, based on the BERT authors's recommendations, with a final evalutaion of the results. 
In the BERT_Undersampling.ipynb file you'll find our model dealing with a slightly different (undersampled) version of the dataset used.
In the BERT_5_Categ.ipynb file you'll find our model dealing with more cathegories (5 instead of 3) to work with.

I’ll add to the repo also the reviews.csv file containing the data used for the train of our Sentiment Analysis model.
And the reviewsunders.csv containing the undersampled dataset. Both are by Google.
