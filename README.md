<h1>Movie Recommender System using TMDB Dataset</h1>
<h3>Overview</h3>
This project implements a content-based movie recommender system using cosine similarity. It utilizes the TMDB (The Movie Database) dataset to provide recommendations based on similarities between movies.

<h3>Features</h3>
Recommends movies similar to a given movie based on content features such as genres, keywords, and overview.
Calculates cosine similarity between movies' feature vectors to determine their similarity.
<h3>Requirements<h3>
Python 3.x<br>
Pandas<br>
NumPy<br>
scikit-learn<br>
TMDB API Key (for accessing the dataset)<br>
<h3>Setup<h3>
Clone the repository:

bash
<h3>Copy code<h3>
git clone https://github.com/Rushikesh1807.git
Navigate to the project directory:

bash
<h3>Copy code<h3>
cd movie-recommender-system-tmdb-dataset
Install the required Python packages:

bash
Copy code
<h3>pip install -r requirements.txt<h3>
Obtain a TMDB API key:

Obtain a TMDB API key from TMDB website and update the config.py file:

python
<h3>Copy code<h3>
TMDB_API_KEY = 'your_tmdb_api_key'
Usage
Run the movie recommender script:

bash
<h3>Copy code<h3>
python movie_recommender.py
Input a movie title when prompted.

View the list of recommended movies based on similarity to the input movie.

<h3>Dataset<h3>
The project utilizes the TMDB dataset, which contains information about movies including titles, genres, keywords, overviews, etc. The dataset is accessed through the TMDB API.

<h3>Contributing<h3>
Contributions are welcome! If you find any issues or would like to contribute enhancements, feel free to open a pull request.

<h3>License<h3>
This project is licensed under the MIT License. See the LICENSE file for details.

<h3>Acknowledgments<h3>
Special thanks to TMDB for providing access to their dataset and API.
