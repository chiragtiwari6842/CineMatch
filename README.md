### Movie Recommendation System

## How to use

1. Install ipywidgets using the following command:
    `pip install ipywidgets`

2. Run all cells, create the `recommendations.csv` file. 

3. After runnning the last cell, enter the movie name in this format:

    `{movie_imdb_name}<space>({movie_release_year})`

4. To get recommendation for another movie, re-run the last cell again.

# Note
   
The movie name and release year should be according to IMDB. Any spelling mistakes will cause an error.

## Future Enhancements

Optimize the approach to handle the entire dataset efficiently, as the current method, using only a subset of the data, still takes considerable time to create the `recommendations.csv` file.

This version includes clearer instructions and formatting, making it easier for users to follow along.
