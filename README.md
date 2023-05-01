# Anime Movie Recommendation System

This is a project I built to recommend anime movies to users based on their rating history. The system uses a collaborative filtering approach, specifically an item-item based method, to generate recommendations for users.

# Collaborative Filtering
Collaborative filtering is a popular method for building recommendation systems. It works by identifying patterns in users' rating histories to find similarities between items. In this project, we used item-item based collaborative filtering to recommend anime movies to users.

Item-item based collaborative filtering is a type of recommendation system that identifies items that are similar to each other based on users' ratings. It works by first building a matrix of user ratings for each item. Then, for each item, we compute the similarity between it and every other item in the dataset. Finally, we generate recommendations for each user by identifying the items that are most similar to the ones they have already rated highly.

I chose to use item-item based collaborative filtering for several reasons. First, it is a well-established method for generating accurate recommendations. Second, it is a scalable method that can handle large datasets. Finally, it is a flexible method that can be adapted to different types of recommendation tasks.

# Datasets
The datasets used in this project are anime.csv and ratings.csv. The anime.csv dataset contains information about each anime movie in the dataset, including its ID, name, genre, type, number of episodes, rating, and number of members. The ratings.csv dataset contains information about user ratings for each anime movie, including the user ID, anime ID, and rating.

# Running the Project
To run the project, you will need to have Python 3 installed on your machine. You will also need to install several Python libraries, including NumPy, Pandas, and Scikit-learn. Once you have installed these dependencies, you can run the project by running the jupyter notebook attached

# Conclusion
In conclusion, this project demonstrated how collaborative filtering can be used to build a recommendation system for anime movies. By using item-item based collaborative filtering, I was able to generate accurate recommendations for users based on their rating history. The project provides a useful tool for users who

