# Movie_Recommender_System
## Overview
The Movie Recommender System is a content-based recommendation engine developed using Python, Pandas, and Scikit-learn. It leverages movie descriptions to provide personalized recommendations based on the content similarity between movies. The system utilizes CountVectorizer for text data processing, cosine similarity for content matching, and Porter Stemmer for efficient word normalization. This project features a web interface built with Streamlit, allowing users to easily get movie recommendations.

## Features
1.Content-Based Recommendations: Recommends movies based on their descriptions.

2.Efficient Text Processing: Uses CountVectorizer and Porter Stemmer for processing movie descriptions.

3.Cosine Similarity: Measures the similarity between movies.

4.Interactive Web Interface: Built with Streamlit for ease of use.

## How It Works
1.Data Processing: Movie descriptions are processed using CountVectorizer,converting the text data into a matrix of token counts.

2.Stemming: Porter Stemmer normalizes words, reducing them to their root forms.

3.Similarity Calculation: Cosine similarity is calculated between movies based on their description vectors.

4.Recommendation: The system identifies the top 5 most similar movies for a given movie and displays their titles and posters.

## Usage
### Run the Streamlit App:
Code:streamlit run app.py

### Open the App in a Browser:
Streamlit will provide a local URL (e.g., http://localhost:8501), which you can open in your web browser.

### Get Recommendations:
1.Select a movie from the dropdown menu.

2.Click the "Recommend" button to see the recommended movies.

## Project Structure
1.app.py: Main script for the Streamlit web app.

2.movies_dict.pkl: Pickle file containing the movie data.

3.similarity.pkl: Pickle file containing the similarity matrix.

4.requirements.txt: List of required packages.

## Future Work
1.Incorporate advanced NLP techniques for improved recommendations.

2.Expand the dataset to include more movies.

3.Enhance the user interface for a better user experience.

## Acknowledgements
1.The Movie Database (TMDb) for providing movie data.

2.Streamlit for the interactive web app framework.
