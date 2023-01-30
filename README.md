# Influence of Actors in Movie Gross: A Network Analysis

## Introduction
The film industry is one of the largest and most dynamic markets globally. The success of a movie can be influenced by a variety of factors, including the cast, budget, marketing, and reviews. In this project, the focus is on the influence of actors on a movie's gross. The goal is to understand how actors' relationships, as measured by centrality measures in a network, can impact a movie's financial success.

## Data
If you want to run the code, you have to download the dataset [Here](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset). Then in `preprocessing_data.ipynb` you can create the network from dataset.

## Methodology
To achieve the goal of this project, a network was built using the movie dataset from Kaggle. The actors were treated as nodes, and connections were established between actors who appeared in the same movie. The centrality measures were then calculated for each actor to assess their importance in the network. The three centrality measures used were degree centrality, closeness centrality, and betweenness centrality. Finally, the relationship between these centrality measures and the movie's gross was analyzed to determine if there is a correlation between the centrality measures and the success of a movie in terms of its gross.

## References
We have used [this](https://towardsdatascience.com/can-network-analysis-work-for-predicting-success-of-box-office-revenue-c8370c8427f9) research as the baseline of our project.

## Acknowledge
We would like to acknowledge any contributing authors or sources that helped in the creation of this project.
