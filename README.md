<h1 align="center">IBM recommendation engine Project</h1>

<p align="center">
This repository contains a project with an IBM dataset about articles. This project is part of the Data Scientist nanodegree by Udacity.<br>
  <a href="https://www.udacity.com/course/data-scientist-nanodegree--nd025?campaign_name=back2skills&coupon=BACK2SKILLS&utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524475679&utm_keyword=data%20science%20udacity_e&gclid=CjwKCAjwrranBhAEEiwAzbhNtU2AhXMTLOAIxbb7dFpKJJ5RpY5AJ2vrr2QDXU5EzU5AiBIidf2R_hoCqrYQAvD_BwE"><strong>Udacity nanodegree</strong></a>
  <br>
  <a href="https://medium.com/@guillaume.david11"><strong>My blog post</strong></a>
  <br>
</p>

## Table of contents

- [How to run the project](#How-to-run-the-project)
- [Motivation and goals](#Motivation-and-goals)
- [Structure](#Structure)
- [Author and acknowledgement](#author-and-acknowledgement)

## How to run the project

Here is the list of installed packages for this proj


Clone the GitHub repository and use Anaconda distribution of Python 3.11.

    $ git clone https://github.com/DavidGuillaum/project_IBM_recommendation_engine.git

In addition This will require pip installation of the following:

     pip install pandas
     pip install matplotlib
     pip install numpy
     pip install pickle


1. Just open the Recommendations_with_IBM.ipynb file and run the cells.


## Motivation and goals

The goals of this project are the following:
- I. Exploratory Data Analysis of the datasets
- II. Rank Based Recommendations
    - This is the most simple system only based on ranking the article with the most interactions
    - New users will have recommendations based on this
- III. User-User Based Collaborative Filtering
    - This method consist into looking similar user in term of interaction with articles
- IV. Matrix Factorization
    - I will build a matrix decomposition using SVD


## Structure
This project is structure is 3 main folders/parts: app, data and models. The app folder will contains everything related to the web app. Regarding the data, there are 2 raw dataset, one SQL DB (we want to stock it here at the end) and a python file containing all the process of cleaning... The last main folder named model will contains the file to train the model and the trained model.
- data
    - articles_community.csv #contain content of articles (doc_body / doc_description / doc_full_name / doc_status / article_id)
    - user-item-interactions.csv #contain interaction with user and article (article_id / title / email)

- project_test.py #python script used to see if my answers are corrects

- README.md

- Recommendations_with_IBM.ipynb # main file

- top_5.p # pickle file created in the jupyter notebook

- top_10.p # pickle file created in the jupyter notebook

- top_20.p # pickle file created in the jupyter notebook

- user_item_matrix.p # pickle file created in the jupyter notebook


<br>


## Author and acknowledgement
I'm David Guillaume, currently studying for a master's degree in Data Analytics and Economics at the University of Fribourg (Switzerland). I'm very interested in data sciences and economics in particular (bachelor's degree in Political Economy). I hope you'll like my project. I would like to thank Udacity for overseeing this program.
<br>
<a href="https://www.linkedin.com/in/david-guillaume-a7bb1b201/"><strong>Here is my Linkedin</strong></a>
<br>