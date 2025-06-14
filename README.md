# RECOMMENDATION-SYSTEM


COMPANY: CODTECH IT SOLUTIONS


NAME: YELLANKI DEVENDRA


INTERN ID: CT04DG224


DOMAIN: MACHINE LEARNING


DURATION: 4 WEEKS


MENTOR: NEELA SANTOSH


PROJECT DESCRIPTION : Personalized Movie Recommendation System with Flask Web Interface
This project implements a personalized movie recommendation system using collaborative filtering techniques and serves it through a web-based user interface developed in Flask. The system allows users to receive intelligent, genre-specific movie recommendations based on their historical ratings and preferences, creating an interactive and engaging movie discovery experience.

The application is powered by a Singular Value Decomposition (SVD)-based collaborative filtering algorithm, implemented using the Surprise library. It integrates fundamental machine learning principles with a sleek and responsive front-end, designed using HTML/CSS, to deliver personalized and relevant movie suggestions with minimal user input.

Core Functionality and Workflow
1. Dataset and Data Modeling
The system uses a sample dataset consisting of user ratings for a variety of popular movies across different genres such as Sci-Fi, Crime, Romance, Drama, and Telugu cinema. Each record in the dataset includes:

A unique user ID

A movie title

A rating (from 1 to 5)

The movie's genre

This tabular data is loaded into a Pandas DataFrame and used to train a recommendation model. Although the dataset is relatively small and synthetic, the structure allows for scalability and can be extended to support larger and more complex datasets from platforms like IMDb or MovieLens.

2. Collaborative Filtering Using SVD
The core recommendation engine is built using the SVD algorithm from the Surprise library. This algorithm is effective in collaborative filtering tasks where the goal is to predict how a user would rate unseen movies, based on existing rating patterns.

When a user submits their ID and genre of interest via the form, the following steps occur:

The model is trained on the available user-movie ratings.

The system identifies movies in the selected genre that the user hasn't rated yet.

SVD is used to estimate predicted ratings for these unseen movies.

The top recommendations are sorted by predicted rating and returned to the user.

This approach enables personalization without requiring users to explicitly rate every movie, leveraging the patterns learned from others with similar tastes.

3. Trending Fallback System
In the absence of extensive data, the app includes a genre-specific fallback system. Each genre (e.g., Sci-Fi, Crime, etc.) has a list of trending or classic movies that act as a default suggestion pool. This ensures the app always has something to recommend, even when data is sparse or when a new user ID is entered.

4. Web Interface and User Interaction
The user interface is designed using Flask's render_template function to dynamically generate HTML pages. It features:

A clean form where users can input their ID and select a preferred genre.

A results section displaying personalized recommendations in a visually styled list.

The design aesthetics are enhanced using an external CSS stylesheet (style.css) which includes:

A responsive card-based layout

A modern, readable font and intuitive spacing

A background image with a dark overlay for contrast

Styled form elements and interactive buttons

5. Deployment and Execution
The app runs locally using Flask’s development server. When users access the root URL (/), they are greeted with the home page where they can interact with the recommendation form. The app is modular and can be easily deployed to cloud platforms like Heroku or Render for broader accessibility.

Use Cases and Applications
This recommendation system can serve a variety of purposes:

Entertainment platforms: Suggest movies tailored to individual tastes.

Educational demos: Teach collaborative filtering and recommender systems.

User engagement tools: Keep users returning by providing dynamic suggestions.

With enhancements like user authentication, dynamic data collection, or advanced algorithms like matrix factorization or neural networks, this project can evolve into a full-scale intelligent recommender engine.


#OUTPUT :

![Image](https://github.com/user-attachments/assets/3845e0ef-4ee1-4299-9922-4f785c39a986)
![Image](https://github.com/user-attachments/assets/5eb478c6-63ef-4cba-b2f5-068e1e246e52)

