Knowledge-Based Restaurant Recommender System
This project implements a knowledge-based restaurant recommendation system that leverages explicit user preferences such as cuisine type, budget, and location, combined with detailed restaurant attributes from the Zomato dataset. Unlike collaborative filtering approaches, this system does not rely on past user behavior, thereby eliminating the cold-start problem.

Features
Data preprocessing: Cleans and processes the Zomato dataset, handles missing values, normalizes categorical data, and engineers features like cost buckets and main cuisine extraction.

Recommendation engine: Filters restaurants based on user preferences and ranks them using weighted scores based on user ratings and number of votes.

Interactive Streamlit interface: Allows users to input preferences, view ranked restaurant recommendations with explanations, and submit feedback directly through the app.

Evaluation metrics: Collects user feedback on recommendation satisfaction and relevance to help assess and improve the system.
Dataset
The dataset used is the Zomato Restaurants Dataset from Kaggle.

Future Work
Integration of a map view for restaurant locations.

Enhanced ranking using proximity and popularity metrics.

More advanced feedback analytics and A/B testing for optimization.

