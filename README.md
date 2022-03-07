
# Creating a Movie Recommendation System Using PySpark

## Project Overview:

This repository was created for the INFO 632 course at Drexel University.  The goal was to create a recommendating system using PySpark to recommend any number of movies to a user given their previous ratings and ratings of other users who are similar to them.  We utilized both collaborative filtering and content-based recommendations.  The ratings data used came from GroupLens, specifically their [MovieLens](https://grouplens.org/datasets/movielens/) dataset. 

## File Manifest: 

- `Folder /data` - Contains all data files
    - `links.csv` - Contains IMDb and TMDb movie IDs.
    - `movies.csv` - Contains movie titles and genres.
    - `ratings.csv` - Contains ratings data for each user.
    - `tags.csv` - Contains user-provided tags for movies.
- `Folder /documents` - Cotains all miscellaneous documents
    - `Final Project Write Up.pdf` - Final report required for class.
- `Part1_EDA.ipynb` - Python/PySpark code for MovieLens EDA.
- `Part2_CollaborativeFiltering.ipynb` - Python/PySpark code for collaborative filtering recommending.
- `Part3_ContentBased.ipynb` - Python/PySpark code for content-based recommending.

## Reason for Project:

Movie predictions can help users find movies they'll most likely enjoy that they might otherwise not have discovered.  Accurate and useful recommendations can also encourage a user to continue utilizing a given platform, like Netflix, Hulu, or Disney+.  

## Team Members:

Alphabetized by last name:

- Tyler Beard, tb3245@drexel.edu
- Zach Carlson, zc378@drexel.edu
- Andrew Napolitano, asn65@drexel.edu

## Project Requirements


## Python Requirements
- Python ≥ 3.8. 
- Python libraries required: 
    - `matplotlib.pylot`
    - `pandas`
  
## How to Execute Notebook: 

All of the code in this project needs to be opened in a Jupyter notebook environment. We recommend using Google Colab.

## Known Limitations of Project:

1. **Only 600 users.** This only contains data on 600 users.  More users would allow for better predictions and might highlight additional latent features that could be valuable.
2. **Most current data is four years old.**  It might be useful to include ratings from current movies.  If we provided hypothetical recommendations to these users, it might not longer be accurate for their current tastes.
3. **Small dataset** We only have 100,000 ratings. If we had the cloud computing power, we could analyze the larger 20M+ ratings dataset.
