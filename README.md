# Movie-Recommender-System
A movie recommender system uses Machine Learning (ML) to predict user preferences, suggesting films they'll likely enjoy by analyzing past viewing habits, ratings, and item features.
Key ML approaches include:
1. Collaborative Filtering: Finding similar users/movies
2. Content-Based Filtering: Recommending items with similar attributes like genre/actors
3. Hybrid systems: Combine these for better accuracy, learning patterns to create personalized viewing experiences.

This project mainly focuses on Content Based Filtering.

Concept: Recommends movies similar to those a user has liked before, based on movie attributes.

ML Aspect: Analyzes movie metadata (genre, director, cast, keywords) and builds a user profile based on liked items. Uses cosine similarity to find similar movie vectors.

# Project Flow
tmbd_5000_movies----> data processing-----> model------> website------> deploy
# Main python libraries used
1. Pandas
2. Numpy
3. ast(Abstract Syntax Tree)
4. nltk
5. pickle
6. streamlit

# Business Objectives
All entertainment websites or online stores have millions/billions of items. It becomes challenging for the customer to select the right one. At this place, recommender systems come into the picture and help the user to find the right item by minimizing the options.

Recommendation Systems in the world of machine learning have become very popular and are a huge advantage to tech giants like Netflix, Amazon and many more to target their content to a specific audience. These recommendation engines are so strong in their predictions that they can dynamically alter the state of what the user sees on their page based on the user’s interaction with the app.

