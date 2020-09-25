## Journal

Opinion mining based content management and document classification system aims to order posts depending on sentiment analysis

## Abstract

Data mining can be defined as the process of finding previously unknown patterns , trends in databases and using that information to build predictive models.Alternatively , it can be defined as the process of data selection and exploration and building models using vast data stores to uncover previously unknown patterns. Data mining is not new, it has been used intensively and extensively by financial institution, for credit scoring and fraud detection.This project aims for mining relationship among some blogs for classification (positive/negative).The data mining methods and techniques will be explored to identify the suitable methods and techniques for efficient classification of <b>Journal</b> and in mining useful patterns.

### Motivation

People sometimes need recommendations or impressions about someone specific products, trends and more. They won't waste a lot of time reading all opinions

### Objective

From this point of view and to overcome this problem, we have built a web app using some data mining algorithms that helps analyzing and exposing content of review or blog post written about some product or trend that helps someone deciding if that content suitable for him or not

### Overview

<b>Journal</b> is a website for writing and analyzing articles about Economy and finding positive / negative classified articles

in this website user can:
  - see all articles in the website.
  - search for articles by:
    - Tags
    - Opinions "This article is positive or negative"
    - Words "That if the user wants to search for articles that have specific words"
    - make new article with its title and can add tags for the article
    - `Like` / `Dislike` an article and/or `comment` on it
    
### Data Sets Used

[Dataset](https://github.com/YoussefElkilaney/Projects/tree/master/Graduation%20Project/Datasets)

#### Economic News Article Tone and Relevance
Contributors read snippets of news articles. They then noted if the article was relevant to the US economy and, if so, what the tone of the article was. Tone was judged on a 9 point scale (from 0 to 9, with 0 representing absolutely negative). Dataset contains these judgments as well as the dates, source titles, and text. Dates range from 1951 to 2014

<b>Number Of Articles:</b> 8000 Articles

<b>Attributes Information:</b>

- Unit id: It has id for each article
- Golden: FALSE
- Unit state: Finalized
- Trusted judgments: 3
- Last judgment at: DATE
- Positivity: From 0 to 9
- Positivity : Confidence :-0 to 1
- Relevance: Yes , No , not sure
- Article id: Serial number
- Date: DATE
- Headline: Title
- Text: main article

### U.S. economic performance based on news articles
Contributors viewed a new article headline and a short,bolded excerpt of a sentence or two from the attendant article. Next, they decided if the sentence in question provided an indication of the U.S. Economy health, then rated the indication on a scale of 0-9, with 0 being negative and 9 being positive.

<b>Number Of Articles:</b> 5000 Articles

<b>Attributes Information:</b>

- Unit id: It has id for each article
- Golden: FALSE
- Unit state: Finalized
- Trusted judgments: 3
- Last judgment at: DATE
- Positivity: From 0 to 9
- Positivity : Confidence :-0 to 1
- Relevance: Yes , No , not sure
- Article id: Serial number
- Date: DATE
- Headline: Title
- Line ID
- Next sentence
- Previous sentence
- Text: main article

### Tools & Technologies
#### DataBases
- MySQL
- MongoDB
### BackEnd
- Django
### FrontEnd
- HTML
- CSS
- Bootstrap
- JavaScript
- JQuery
### Classification Algorithms
- Logistic Regression
- KNN
- SVC
- Decision Tree
- Random Forests
### Python packages
- re
- Pandas
- Stopwords from nltk.corpus
- word_tokenize from nltk.tokenize
- PorterStemmer from nltk.stem.porter
### References
- https://www.figure-eight.com/data-for-everyone
- https://www.w3schools.com/html/html_intro.asp
- https://www.w3schools.com/css/css_intro.asp
- https://www.w3schools.com/js/js_intro.asp
- https://www.w3schools.com/bootstrap/bootstrap_get_started.asp
- https://www.w3schools.com/jquery/jquery_intro.asp
- https://machinelearningmastery.com/clean-text-machine-learning-python
- https://www.geeksforgeeks.org/python-stemming-words-with-nltk
- http://istqbexamcertification.com/what-are-the-software-development-models
