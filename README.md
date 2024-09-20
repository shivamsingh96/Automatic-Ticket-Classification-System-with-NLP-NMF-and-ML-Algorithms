# Automatic-Ticket-Classification-System-with-NLP-NMF-and-ML-Algorithms
This project designed to automate the classification of customer support tickets utilizing Natural Language Processing (NLP) techniques, Non-Negative Matrix Factorization (NMF), and various Machine Learning (ML) algorithms. 


## Problem Statement
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.

These customer complaints are unstructured text data. So, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department, which then further gets assigned to a particular support employee. This becomes tedious as the company grows and has a large customer base.

In this case study, I will be working as an NLP engineer for a financial company that wants to automate its customer support ticket system. As a financial company, the firm has many products and services, such as credit cards, banking and mortgages/loans. So, need to build a model that is able to classify customer complaints based on the products/services. By doing so, company can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.


## Dataset
You can download the dataset from https://drive.google.com/file/d/1qTVu7y8QTtN2_XNOK1NnGVqteEfXMA-m/view?usp=drive_link.

Although the dataset contains 22 features but only complaint text is valuable for us and since Topic Modelling is a unsupervised learning problem so the labels are not given. We have find the significant labels/category for each complaints.


## Text Preprocessing
Before analysis, we should process the text data so that we will get valuable insights and information from dataset for further extraction and prediction. Text preprocessing involves 3 main steps:
1. Data Cleaning (Removing Brackets, Punctuations, Numbers and special characters)
2. Lemmatization
3. Parts of Speech (POS) Tagging


## Exploratory Data Analysis
This process helps to analyse the data and extract valuable insights and information from dataset. This process includes plotting of wordcloud to check the most frequent word occuring in the complaints and then visualize top 30 unigrams, bigrams and trigrams.





