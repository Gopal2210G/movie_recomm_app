# Movie Recommender System

Welcome to the Movie Recommender System! This application suggests movies based on your selected favorite. The recommendations are provided along with movie posters to give you a visual idea of the suggested films.

## Features

- **Movie Selection:** Choose from a wide range of movies.
- **Personalized Recommendations:** Get five movie recommendations based on the selected movie.
- **Movie Posters:** Visual representation of the recommended movies with their posters.
- **Custom Styling:** A visually appealing interface with a custom background and styled headers.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/movie-recommender-system.git
    cd movie-recommender-system
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt

    [
    Dependencies
    Python 3.x
    Streamlit
    Requests
    Pandas
    Pickle
    Ensure you have these dependencies installed as specified in requirements.txt.
    ]
    ```

4. **Place the necessary files:**
    - Ensure `movie_list.pkl` and `similarity.pkl` are in the root directory of your project.

## Usage

1. **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

2. **Interact with the app:**
    - Select a movie from the dropdown menu.
    - Click the "Show Recommendation" button to view recommended movies.

## Files

- `app.py`: Main application script.
- `movie_list.pkl`: Pickled file containing the list of movies.
- `similarity.pkl`: Pickled file containing the similarity matrix.
-Data Files
   -/kaggle/input/tmdb-movie-metadata/tmdb_5000_movies.csv
   -/kaggle/input/tmdb-movie-metadata/tmdb_5000_credits.csv

  
Acknowledgements
Streamlit
The Movie Database (TMDb)
Special thanks to the developers and contributors of the libraries and tools used in this project.

![Screenshot (2126)](https://github.com/Gopal2210G/movie_recomm_app/assets/139383848/d4c13e0b-8657-46ab-8d18-5bbaa09bf7b7)
![Screenshot (2128)](https://github.com/Gopal2210G/movie_recomm_app/assets/139383848/ba670560-5693-4f20-b296-fa9a746a2d4a)

