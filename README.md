# tag-ez

The aim of the project is to predict the tags (a.k.a. keywords, topics, summaries) of a question, given only the question text and its title. The dataset consists of 6M+ of ‘Title’, ‘Body’ and ‘Tags’ of the questions posted on StackOverflow. From disparate stack exchange sites, containing a mix of both technical and non-technical questions. Using Binary Relevance Method with One vs Rest Classifier to achieve more than 94 % accuracy This repo contains my implementation of the Taxonomy Classification problem

* Team Info: Group 7
| Member          | email                           |
|-----------------+---------------------------------|
| Kin Chang       | kin.chang@sjsu.edu              |
| Achal Rajyaguru | achal.rajyaguru@sjsu.edu        |
| Sagar Raval     | sagarbharatkumar.raval@sjsu.edu |
| Jay Patel       | jay.j.patel@sjsu.edu            |
| Rutvik Patel    | rutvik.g.patel@sjsu.edu         |
* Objectives
- We want to improve experience for users when they ask questioin in Q&A platform, such as Stack Overflow, Quora, etc., by automatically suggesting tags based on the question they are asking.
- In essence, we would like to develop a Machine Learning model that can predict related tags, given questions title and text
* Dataset
- We will be using a subset of data scraped from StackOverflow (Tile and Body -> Tags), with over 6M datapoints
# * Approach
# - We are going to train our model using Binary Relevance Method with One vs Rest Classifier; and compare their performance


You will need to install the following modules to run this code successfully. The entire code is written in Python3

(1) Pandas

(2) Numpy

(3) Matplotlib

(4) Sqlite

(5) Seaborn

(6) Wordcloud

(7) Sqlalchemy

(8) NLTK libraries

(9) Sklearn packages
