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
