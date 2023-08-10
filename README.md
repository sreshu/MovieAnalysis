# MovieAnalysis
The MovieLens dataset is a popular benchmark dataset. It contains user ratings and movie information, making it a valuable resource for building and evaluating recommendation algorithms. The dataset was created by the GroupLens Research Project at the University of Minnesota.

There are several versions of the MovieLens dataset, with varying sizes and levels of detail. One of the commonly used versions is the MovieLens 25M dataset (the one getting used for this project) , which contains:

    * Movie Data: Information about movies, including movie IDs, titles, and genres. The dataset may also include other details such as release year and IMDb links.

    * User Data: Information about users who have rated movies, including user IDs and demographic information.

    * Ratings Data: User ratings for movies, indicating how users have rated different movies. This data includes user IDs, movie IDs, ratings (usually on a scale of 1 to 5), and timestamps of when the ratings were given.

    * Tags Data: User-generated tags or labels associated with movies. Tags provide additional context about movies, and users can use them to describe or categorize movies.


Instructions to run:
Keep executing each cell , 
* if asked for Movie Input - put Movie Names  Waiting to Exhale (1995), American President, The (1995), Sense and Sensibility (1995) etc
* if asked for Genre - put Comedy,Drama,Romance,Thriller etc
* if asked for User ID - put any number from 1 to 2500

   Generate and display different approaches of recommendations by uncommenting  any one of these cells
#recommendations = generate_movie_recommendations(input_movie, ratings, movies) <br />
#recommendations = recommend_by_cosine_similarity(input_movie, ratings, movies) <br />
#recommendations = recommend_by_content(input_movie, movies) <br />
#recommend_movies_knn(input_movie, ratings, movies, num_recommendations=5, k=6) <br />

# Future Scope:
   Create customized filtering method, Research/Dive deep about DNN based approaches.

   Recommendation on the basis of sentiments presented in the comments, can improvise the similarity score further.
   

   
