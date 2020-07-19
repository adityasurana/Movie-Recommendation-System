# Movie-Recommendation-System
Build Movie Recommendation System on Databricks with Apache Spark

•	Recommending movies (top 20) to a user from a given set of movies, used ALS matrix factorization algorithm with PySpark on Databricks.

Dataset was taken from movieLens dataset containig over 100,000 movies and their ratings given by different users.

# Used ALS (Alternating Least Squares) matrix factorization algorithm,
in order to get high accuracy with appropriate amount of time (reduced time); as there were more than 100k different movies classified into more than 1000 genre(classes).
In ALS mechanism, we are basically minimizing the entire loss function at once, but only twidding half the parameters.

In ALS, we split our parameter vector into two blocks (let ssay U and V) and then alternatively update each block of parameters.

Code is self explanatory.
