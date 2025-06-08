# recommender
movie recommender system
<br>
# Movie Recommender System

This is a simple movie recommender system built with Streamlit. It suggests movies similar to the one you select and displays their posters.

## Features

- Select a movie from a dropdown list.
- Get 5 similar movie recommendations.
- View posters for each recommended movie.

## How it works

- Uses precomputed similarity data (`similarity.pkl`) and a movie dictionary (`movie_dict.pkl`).
- Fetches movie posters from The Movie Database (TMDb) API.

## Requirements

- Python 3.x
- streamlit
- pandas
- requests

## Setup

1. Clone this repository and navigate to the `recommender` directory.
2. Ensure you have the following files in the directory:
   - `movie_dict.pkl`
   - `similarity.pkl`
3. Install dependencies:
   ```sh
   pip install streamlit pandas requests

streamlit run Website.py

Collecting workspace informationHere is a suggested [README.md](d:/recommender/recommender/README.md) for your project:

```md
# Movie Recommender System

This is a simple movie recommender system built with Streamlit. It suggests movies similar to the one you select and displays their posters.

## Features

- Select a movie from a dropdown list.
- Get 5 similar movie recommendations.
- View posters for each recommended movie.

## How it works

- Uses precomputed similarity data (`similarity.pkl`) and a movie dictionary (`movie_dict.pkl`).
- Fetches movie posters from The Movie Database (TMDb) API.

## Requirements

- Python 3.x
- streamlit
- pandas
- requests

## Setup

1. Clone this repository and navigate to the `recommender` directory.
2. Ensure you have the following files in the directory:
   - `movie_dict.pkl`
   - `similarity.pkl`
3. Install dependencies:
   ```sh
   pip install streamlit pandas requests
   ```
4. Run the app:
   ```sh
   streamlit run Website.py
   ```

## Notes

- You need an internet connection to fetch posters from TMDb.
- The TMDb API key is hardcoded in the script.

## File Structure

- `Website.py` - Main Streamlit app.
- `movie_dict.pkl` - Pickled movie data.
- `similarity.pkl` - Pickled similarity matrix.
- `.gitattributes`, `.gitconfig` - Git configuration files.

## License

This project is for educational purposes.
```
You can edit or expand this as needed for your project.
<br>
