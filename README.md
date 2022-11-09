### Group5_Final_Project

# Section 1: Machine learning revisited from MOD 18

### What model is best suited for the Group?

## Supervised ML
Supervised learning deals with labeled data. An example of supervised learning might be to predict, based on data from previous patients, whether a new patient has diabetes.

Supervised learning is fairly simple: We use it when we know what we're looking for or what our output should be. Two of the most popular techniques are classification and regression. For example, if we want to see how Bitcoin performs over time, or if we want to figure out what kinds of coins a user is most likely to buy, we use supervised learning. 

In supervised learning, the input data already has a paired outcome, which is plugged in to train the model to predict outcomes in new datasets. For example, we want to build a model that, when given unfamiliar data, can accurately predict the outcomes.

## Unsupervised ML
In unsupervised learning, by contrast, machine learning algorithms work with datasets without labeled outcomes. In supervised learning, the labels provide the correct answers. In unsupervised learning, such correct answers, or labels, aren't provided. An example of unsupervised learning might be to task a machine learning algorithm with grouping a bag of objects as it sees fit. The algorithm isn't given labels, so it's on its own to find patterns.

A common application of unsupervised learning is to group customers by purchasing patterns.

We will could  use unsupervised machine learning algorithms, which help us explore data when we're not sure what we're looking for. Now you can analyze data without a clear output in mind. We use unsupervised learning when we don't yet know the question we're asking of the data. In other words, we just want to figure out if there is anything at all the data can tell us.

In unsupervised learning, there are two key differences from supervised learning

There are no paired inputs and outcomes.
The model uses a whole dataset as input.
Unsupervised learning is used in one of the following two ways:

Transform the data to create an intuitive representation for analysis or to use in another machine learning model; or
Cluster or determine patterns in a grouping of data, rather than to predict a classification.

There are two types of unsupervised learning: transformations and clustering algorithms.

We use transformations when we need to take raw data and make it easier to understand. 

We use clustering algorithms to group similar objects into clusters. For example, if a cable service wants to group those with similar viewing habits, we would use a clustering algorithm.

Recall that unsupervised learning does not take in any pairing of input and outcomes from the data—it only looks at the data as a whole. This can cause some challenges when running the algorithm. Since we won't know the outcome it's predicting, we might not know that the result is correct. This can lead to issues where we're trying to decide if the model has provided any helpful information that we can use to make decisions in the real world.

Before moving data to our unsupervised algorithms, complete the following steps for preparing data:

*Data selection* - entails making good choices about which data will be used. availaibiulty missing data and unneeded data.

*Data processing*- organizing the data by formatting, cleaning, and sampling it. 
Data transformation

*Data transformation* - entails transforming our data into a simpler format for storage and future use, such as a CSV, spreadsheet, or database file
