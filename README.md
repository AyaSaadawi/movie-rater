# Movie Rater

A simple Java-based application that allows users to rate movies and provides basic information about movies like title, year, genres, and more. The application also provides functionality for movie data management and user ratings.

## Features

- **Movie Information**: Displays movie details such as title, year, director, genre, etc.
- **User Ratings**: Users can rate movies on a scale of 1 to 10.
- **Data Management**: The application handles movie data and ratings, allowing users to add, view, and update ratings.
- **File Handling**: Movie data and ratings are read from and written to CSV files.

## Technologies Used

- Java
- CSV files for data storage

## Files Overview

- **Movie.java**: Contains the `Movie` class that represents movie details.
- **Rater.java**: Handles user ratings and interactions with movie data.
- **Rating.java**: Represents a user's rating for a movie.
- **CSV Files**:
  - `ratedmovies_short.csv`: A short version of the movie data.
  - `ratedmoviesfull.csv`: A full version of the movie data.
  - `ratings.csv`: Stores the user ratings for the movies.

## Getting Started

To get started with this project:

1. Clone the repository:
   ```bash
   git clone https://github.com/AyaSaadawi/movie-rater.git
Navigate to the project directory:

bash
Copy code
cd movie-rater
Compile and run the Java files:

bash
Copy code
javac Movie.java Rater.java Rating.java
java Rater
Follow the prompts to rate movies and view their details.

Future Enhancements
User Interface: Implement a graphical user interface (GUI) for a better user experience.
Rating Validation: Add input validation to ensure ratings are within the acceptable range (1-10).
Database Integration: Replace CSV files with a database system to handle larger datasets and provide better performance.
