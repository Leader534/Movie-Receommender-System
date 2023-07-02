# movie-recommender-system
A content based movie recommender system using cosine similarity. 

Cosine similarity is a measure of similarity, often used to measure document similarity in text analysis. In Movie Recommender System, I have considered various aspects of Movies such as  Movie Title, Movie Genre, Movie Star Cast and Director of the Movie. I have a created a key for individual movie out of this information and used them in cosine similarity. The system will analyse the key and provide the similar keys in result. So when a Movie is searched in the application, the system will recommend similar movies based on the cosine similarity performed on various Movie aspects.

Example:
Movie Searched: Iron Man
Result: Iron Man2, Iron Man3, The Avengers.


-----------------------------------------------------------------------

Install dependencies using below cmd in terminal:
pip install -r requirements.txt


-----------------------------------------------------------------------

To run application, type below cmd in terminal:
python app.py
