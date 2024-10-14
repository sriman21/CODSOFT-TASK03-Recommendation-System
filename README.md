# CODSOFT-TASK03-Recommendation-System
Movie Recommendation System 🎬📽️

This project is a Content-Based Movie Recommendation System built using Python and libraries like pandas, scikit-learn, and difflib. The system recommends movies to users based on the genres of their favorite films.

Features

Content-Based Filtering: The recommendation system uses the movie's genres to recommend similar movies.

TF-IDF Vectorization: The system utilizes Term Frequency-Inverse Document Frequency (TF-IDF) to convert the genres into feature vectors, and calculates the similarity between movies.
Cosine Similarity: This technique is used to compute the similarity between different movies based on the TF-IDF vectors.

User-Friendly Input: The system accepts a movie name from the user and returns a list of similar movies.

Data:

The project uses a dataset (movies.csv) that contains movie details such as:


title: The name of the movie

genres: The genres associated with the movie (used for recommendations)

Other features like keywords, cast, director, and tagline can be added to improve the recommendation accuracy.

Requirements:

Python 3. x

pandas

NumPy

sci-kit-learn

Future Improvements:

Include additional features such as cast, director, and keywords for better recommendations.

Implement a collaborative filtering model.

Create a web or mobile interface using Flask or Streamlit.
