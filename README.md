# Dynamic Movie Recommendation System

## Project Description
The **Dynamic Movie Recommendation System** allows users to discover trendy movies based on their preferences. Users can filter movies by genre, rating range, and popularity to find exactly what they're looking for. The application is built using Python and provides a flexible, customizable movie discovery experience.

## Features
- Filter movies by **genre** (e.g., Horror, Action, Sci-Fi).
- Specify **minimum and maximum ratings** to refine results.
- Sorts movies by **popularity** to show the most trendy options first.
- Easy-to-use **command-line interface** for movie recommendations.
- Extendable dataset that can integrate with real-world APIs like IMDb or TMDB.

## Tech Stack
- **Python**
- **Pandas** (for data manipulation)

## How It Works
1. The program uses a dataset containing movie titles, genres, ratings, and popularity.
2. Users can:
   - Select a genre.
   - Set a minimum and/or maximum rating threshold.
3. The program filters the dataset based on user inputs and displays the recommendations sorted by popularity.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-recommendation-system
   ```
3. Install the required dependencies:
   ```bash
   pip install pandas
   ```

## Usage
1. Run the program:
   ```bash
   python movie_recommendation.py
   ```
2. Follow the prompts to:
   - Choose a genre.
   - Specify minimum and/or maximum ratings.
3. View the recommended movies.

## Example
**Input:**
```
Available Genres: Sci-Fi, Action, Drama, Horror, Thriller
Enter the genre you're interested in (or press Enter to skip): Horror
Enter the minimum rating (or press Enter to skip): 7.5
Enter the maximum rating (or press Enter to skip): 8.5
```

**Output:**
```
Recommended Movies:
       Title   Genre  Rating  Popularity
The Conjuring  Horror     7.5          75
     Get Out   Horror     7.7          80
```

## Dataset
The sample dataset contains the following columns:
- **Title**: Name of the movie.
- **Genre**: Genre of the movie (e.g., Action, Horror).
- **Rating**: IMDb-style rating (scale of 1-10).
- **Popularity**: Popularity score (scale of 1-100).

Feel free to expand the dataset or integrate with APIs like TMDB or IMDb for live data.

## Future Enhancements
- Integrate with **TMDB API** for live trending movies.
- Add additional filters such as:
  - Release year
  - Cast and crew
  - Runtime
- Build a **web application** using Flask or Django.

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

Happy movie hunting!
