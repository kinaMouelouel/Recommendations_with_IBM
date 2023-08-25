# Recommendations with IBM     

## Introduction
 
The goal of the project is to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles that we will think they will like. 
The IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.

## The Tasks
Your project will be divided into the following tasks

I. Exploratory Data Analysis

Before generating any type of recommendations, it's essential to examine the data associated with the  project. Delve into the dataset to uncover insights. Fundamental and necessary inquiries about the data will guide your exploration throughout the notebook. This stage of exploration is critical before delving into the finer aspects of your recommendation system in the subsequent sections.

II. Rank Based Recommendations

To initiate the process of creating recommendations, your first step involves identifying the articles that have garnered the highest number of interactions, signifying their popularity. Given the absence of ratings, it becomes straightforward to consider articles with the most interactions as the ones with the greatest appeal. These articles subsequently become candidates for recommendations to new users or individuals, depending on the available information about them.

III. User-User Based Collaborative Filtering

To enhance recommendations on IBM's platform, an effective strategy is to examine users who share similar interaction patterns with items. By suggesting these items to users who exhibit similarity, we take a positive stride towards delivering more personalized recommendations. The forthcoming implementation will focus on realizing this approach.

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Considering the abundance of content associated with each article, there exists a variety of approaches for crafting a content-based recommendation system. Leveraging your expertise in natural language processing (NLP), you have the opportunity to devise innovative methods to construct such a system. While creating a content-based recommendation system is encouraged, it's not mandatory to fulfill the project requirements.

V. Matrix Factorization

Lastly, you will finalize a machine learning method for constructing recommendations. By utilizing user-item interactions, you will develop a matrix decomposition technique. This process will provide insights into your capability to forecast potential articles that an individual could engage with (though the accuracy may be limited). Subsequently, you will deliberate on potential strategies for future implementation and assess how effectively your recommendations engage users, including possible testing approaches.

## File Descriptions

**Recommendations_with_IBM.ipynb** - Jupyter Notebook for project.<br/>
**project_test.py** - Python file contains solutions for test questions in the Jupyter Notebook.<br/>
**top_10.p** - P file contains top 10 articles.<br/> 
**top_20.p** - P file contains top 20 articles. <br/> 
**top_5.p** - P file contains top 5 articles.<br/> 
**user_item_matrix.zip** - zipped file for *user_item_matrix.p*. We need to unzip the file to use it. This is P file containing user item matrix that we will use to perform Singular Value Decomposition (SVD).<br/>
(**Note:** P files are used by project_test.py to test top n articles we obtained via functions we created.)<br/>

### Datasets<br/>
**user-item-interactions.csv** - list of user article interactions.<br/>
**articles_community.csv** - articles available on the IBM platform.<br/>

## Installation
There should be no extra libraries required to install apart from those coming together with Anaconda distribution. There should be no issue to run the codes using Python 3.5 and above.

### Libraries Used
pandas, numpy, matplotlib, pickle

## Instructions
Run the codes inside Jupyter notebook to complete the project.

## Acknowledgements
* [Udacity](https://www.udacity.com/) for providing an excellent Data Scientist training program.
* [IBM](https://www.ibm.com/) for providing user interaction article dataset from IBM Watson Studio.
