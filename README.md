# Movie Recommendation System

## Project Overview
This project implements a **content-based movie recommendation system** using Python.
The goal of the project is to build the foundation of a recommendation system by
analyzing movie content such as overview, genres, keywords, cast, and crew, and
measuring similarity between movies.

This project was developed as part of the **Winter in Data Science (WiDS) Analytics Club**
program.

---

## Dataset Used
The project uses the following datasets:

- **movies_metadata.csv**  
  Contains movie details such as title, overview, genres, release date, and popularity.

- **credits.csv**  
  Contains information about the cast and crew of each movie.

- **keywords.csv**  
  Contains keywords associated with movies that describe important themes and concepts.

- **links.csv**  
  Used only as a **filter** to retain valid TMDB movie IDs.  
  This dataset is **not merged** with the others, as per project guidelines.

---

## Data Preprocessing
The following preprocessing steps were performed:

- Handled inconsistent and missing movie IDs safely
- Converted ID columns to numeric format
- Removed invalid records
- Used `links.csv` only to filter valid TMDB movie IDs
- Merged movies metadata, credits, and keywords datasets using the common movie ID

---

## Techniques Used
- **Pandas** for data loading, cleaning, and merging
- **NumPy** for numerical operations
- **Matplotlib** for basic data visualization
- **Scikit-learn** for:
  - CountVectorizer
  - Cosine Similarity

---

## Current Progress
- Dataset loading, cleaning, and preprocessing
- Merging multiple datasets into a master dataset
- Creation of a content-based feature set
- Introduction to Count Vectorizer and Cosine Similarity

---

## Outcome
A clean master dataset has been created, which can be used to compute similarity
between movies based on their content. This dataset forms the basis for building
a content-based movie recommendation system.

---

## Author
**Shashi Shankar**
