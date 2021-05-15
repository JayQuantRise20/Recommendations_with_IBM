# Recommendations_with_IBM

### Introductions:

For this project we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

### Motivation:

By completing this project, we can build a recommender system which uses machine learning approach to make predictions and evalue them on validation data and report the accuracy and prediction errors. 


### How it Works:

 project will be divided into the following tasks

**I. Exploratory Data Analysis**

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

**II. Rank Based Recommendations**

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**III. User-User Based Collaborative Filtering**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

**IV. Content Based Recommendations**

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

**V. Matrix Factorization**

Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). we will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.


### Evaluation of Results:

As we use SVD for matrix factorization and then predict the test data, one of the parameters that is important for prediction is the latent factors of the SVD model. we have tried to plot the actual vs predicted values error for different latent factors, and the plot below represents this:

![](images/Screenshot 2021-05-15 at 15.41.04.png)


