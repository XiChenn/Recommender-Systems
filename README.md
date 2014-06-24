Recommender Systems
===================================
(Adapted from Coursera) This lab is performed collaborative filtering on the MovieLens 100k Dataset. The dataset rates movies on a scale of 1 to 5. There are nu = 943 users and nm – 1683 movies.

The movie ratings dataset is stored in lab13_movies.mat, which has Y (the num_movies) and x (num_users matrix) with the ratings y(i,j) (from 1 to 5). R is an indicator matrix where R(i,j) = 1 if user j rated movie i and 0 otherwise. The goal of collaborative filtering is to predict the ratings for users who haven’t rated a movie yet.


### Recommendations
    Top recommendations for you:
    Predicting rating 9.0 for movie Titanic (1997)
    Predicting rating 8.9 for movie Star Wars (1977)
    Predicting rating 8.8 for movie Shawshank Redemption, The (1994) Predicting rating 8.5 for movie As Good As It Gets (1997) Predicting rating 8.5 for movie Good Will Hunting (1997) Predicting rating 8.5 for movie Usual Suspects, The (1995) Predicting rating 8.5 for movie Schindler’s List (1993)
    Predicting rating 8.4 for movie Raiders of the Lost Ark (1981) Predicting rating 8.4 for movie Empire Strikes Back, The (1980) Predicting rating 8.4 for movie Braveheart (1995)
    Original ratings provided:
    Rated 4 for Toy Story (1995)
    Rated 3 for Twelve Monkeys (1995)
    Rated 5 for Usual Suspects, The (1995)
    Rated 4 for Outbreak (1995)
    Rated 5 for Shawshank Redemption, The (1994) Rated 3 for While You Were Sleeping (1995) Rated 5 for Forrest Gump (1994)
    Rated 2 for Silence of the Lambs, The (1991) Rated 4 for Alien (1979)
    Rated 5 for Die Hard 2 (1990)
    Rated 5 for Sphere (1998)
