# Movie-Recommender-System
A movie recommender system uses Machine Learning (ML) to predict user preferences, suggesting films they'll likely enjoy by analyzing past viewing habits, ratings, and item features.
Key ML approaches include:
1. Collaborative Filtering: Finding similar users/movies
2. Content-Based Filtering: Recommending items with similar attributes like genre/actors
3. Hybrid systems: Combine these for better accuracy, learning patterns to create personalized viewing experiences.

This project mainly focuses on Content Based Filtering.

Concept: Recommends movies similar to those a user has liked before, based on movie attributes.
ML Aspect: Analyzes movie metadata (genre, director, cast, keywords) and builds a user profile based on liked items. Uses cosine similarity to find similar movie vectors.
