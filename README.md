# Movie Gross Prediction using Degree Centralities

For using data, drive mount on the colab is used. If the final data which preprocessed would be used, preprocessing part can be passed.


# Introduction
Predicting the gross of a movie is an important task in the film industry. In this project, we aim to predict the gross of movies by using graph centrality measures and node features that represent the actors in the movie and their relationship with the movie.

# Data
The dataset used in this project is a directed graph network where the source nodes are "actor's names" and the destination nodes are "gross" which represents the gross of one movie they have played in. The name of the movie is the edge attribute.

# Methodology
The first step was to convert the table dataset into a graph network. Next, we calculated various centrality measures for each node in the graph. These centrality measures, along with the gross of the movie and other relevant node features, were used as input features for a regression model to predict the gross of each movie.

# Results
The results of the model will be reported and evaluated in terms of regression metrics, such as mean squared error and R^2 score. The performance of the model will also be visualized and discussed.

# Conclusion
The conclusion will summarize the findings of the project and discuss any future work that can be done to improve the model.

# Usage
The code and necessary dependencies can be found in the repository. To run the code, simply clone the repository and follow the installation instructions.

# References
Any relevant references used in this project will be listed in this section.

# Acknowledge
We would like to acknowledge any contributing authors or sources that helped in the creation of this project.
