# Final Project - Recommendation Engine
Hello! This project is me creating a recommendation engine that predicts the ratings users would give to movies that they have never seen before.

First, I import the necessary files. Then, I observe the data and find the highest rated movies in the dataset. 

I perform a count of the movies and see if the number of reviews are too small (since 1 rating of 5 stars is not enough to make a good recommendation). 

Once I am done exploring the data, I start the matrix factorization process by organizing the data into a PivotTable where the rows are users, the columns are movies, and the entries are ratings the users gave those movies. 
I then perform the Single Value Decomposition (SVD) and use it to get predictions. I split the matrix and record predicted values with actual values to receive a final RMSE of .89.
