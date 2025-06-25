# 🎬 Netflix Data Analysis Project 2025

This project analyzes a dataset of Netflix movies to explore trends in **genres**, **popularity**, **votes**, and **release patterns** using Python.

## 📁 Dataset

The dataset `mymoviedb.csv` contains metadata for 9,800+ Netflix movies, including:

- `Title`
- `Release_Date`
- `Popularity`
- `Vote_Average`
- `Vote_Count`
- `Genre`
- and more...

## 🧹 Data Cleaning Steps

- Converted `Release_Date` to datetime and extracted only the release year.
- Dropped irrelevant columns: `Overview`, `Original_Language`, `Poster_Url`.
- Handled comma-separated genres and exploded them into individual rows.
- Removed duplicates and missing values.
- Categorized `Vote_Average` into 4 levels using quartiles:
  - `not_popular`, `below_average`, `average`, `popular`

## 📊 Key Analysis Performed

### Q1: What is the most frequent genre?

- **Drama** is the most frequent genre, appearing in more than 14% of all movies.

### Q2: Which genre has the highest vote category?

- Among "popular" movies, **Drama** leads again with over 18.5%.

### Q3: What movie has the highest popularity?

- 🎥 *Spider-Man: No Way Home* — Genres: Action, Adventure, Science Fiction

### Q4: What movie has the lowest popularity?

- 🎥 *The United States vs. Billie Holiday* and *Threads* — Genres: Music, Drama, War, History, Science Fiction

### Q5: Which year had the most movie releases?

- 📅 **2020** had the highest number of film releases in the dataset.

## 📈 Visualizations

Visuals created using **Matplotlib** and **Seaborn**:
- Genre frequency bar chart
- Vote average category distribution
- Movie release year histogram
- Most/least popular movie summaries

## 🛠️ Tech Stack

- Python
- pandas
- matplotlib
- seaborn
- numpy
- Jupyter Notebook
- VS Code

