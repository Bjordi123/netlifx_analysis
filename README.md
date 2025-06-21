# 📺 Netflix Titles Dataset Analysis

This project performs exploratory data analysis on a dataset of movies and TV shows available on Netflix. It includes data cleaning, feature extraction, and insightful visualizations to understand content trends, genre distributions, production geography, and more.

---

## 📊 Dataset Description

The dataset contains information about various titles available on Netflix, including metadata like cast, genre, release year, and country of origin. Additional columns have been engineered for in-depth analysis.

### 📌 Key Columns:

| Column Name            | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `show_id`              | A unique identifier for each title                                          |
| `type`                 | Indicates if the title is a **Movie** or a **TV Show**                      |
| `title`                | Name of the movie or show                                                   |
| `director`             | Name(s) of the director(s)                                                  |
| `cast`                 | Main actors and actresses featured                                          |
| `country`              | Country or countries where the title was produced                           |
| `date_added`           | Date the title was added to Netflix                                         |
| `release_year`         | Year the title was originally released                                      |
| `rating`               | Maturity rating (e.g., **TV-MA**, **PG-13**, etc.)                          |
| `duration`             | For movies: duration in minutes; for shows: number of seasons               |
| `listed_in`            | Categories or genres assigned to the title                                  |
| `description`          | Summary or synopsis of the content                                          |
| `Actual Genre`         | Cleaned and refined genre classification for deeper analysis                |
| `duration_minutes`     | Numeric duration (in minutes) for movies                                    |
| `duration_seasons`     | Numeric season count for TV shows                                           |
| `primary_country`      | Main country involved in the production                                     |
| `secondary_country`    | Second country listed (if applicable)                                       |
| `3rd–11th countries`   | Additional countries involved in production                                 |

---

## 🛠️ Technologies Used

- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Regex**, **Datetime**, **String processing** – Data cleaning
- **Jupyter Notebook** – Code execution & inline output display

---

## 📈 Key Features of the Analysis

- Cleaning and normalizing categorical and date columns
- Splitting multi-country productions into separate fields
- Extracting and engineering new features (e.g., actual genres, duration type separation)
- Visual analysis of:
  - Genre popularity over time
  - Country-wise production insights
  - Trends in maturity ratings
  - Duration and type comparisons

---

## 📂 Dataset Source

You can find the original dataset on [Kaggle – Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows).

---

## 📸 Notebook Preview

The Jupyter Notebook is available in this repository with all outputs visible, including charts and transformed datasets.

---

## ✅ How to Run

1. Clone the repo  
```bash
git clone https://github.com/Bjordi123/netflix_analysis.git
