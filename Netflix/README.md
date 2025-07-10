# 📺 Netflix Data Analysis — New Shows and Movies

## 🗂️ Download Datasets
This project uses the `netflix_data.csv` dataset, often shared as a take-home assignment for data science positions at Netflix.

---

## 🎯 Assignment Objective
Analyze the data and generate **actionable insights** to help Netflix decide:
- What type of shows/movies to produce
- How to grow their business in different countries

---

## 🧠 Key Questions to Explore

- What type of content is available in different countries?
- How has the number of movies released per year changed over the last 20–30 years?
- TV Shows vs. Movies: Which dominates?
- What is the best time to launch a TV show?
- Actor and director trends across genres
- Has Netflix shifted its focus more toward TV shows recently?
- How does content vary geographically?

---

## 📊 Dataset Description

The dataset contains all TV shows and movies available on Netflix:

| Column        | Description                                                 |
|---------------|-------------------------------------------------------------|
| `show_id`     | Unique ID for every title                                   |
| `type`        | Movie or TV Show                                            |
| `title`       | Title of the movie/show                                     |
| `director`    | Director’s name                                             |
| `cast`        | Main actors involved                                        |
| `country`     | Country of production                                       |
| `date_added`  | Date added to Netflix                                       |
| `release_year`| Year of original release                                    |
| `rating`      | Age/TV rating (e.g., PG, TV-MA)                             |
| `duration`    | Total runtime (in minutes or number of seasons)             |
| `listed_in`   | Genre/category                                              |
| `description` | Summary of the movie/show                                   |

---

## 💡 Practical Considerations

- The **goal** is to provide **data-driven recommendations**, not opinions.
- Ensure all insights are clearly supported by data and visualizations.
- **Avoid technical jargon** — imagine you're presenting to non-technical business stakeholders.
- Tie every finding back to **business impact**: which content to produce, and where.

---

## 🧹 Data Cleaning & 📊 Exploration

All cleaning, preprocessing, and analysis steps are implemented in:

🔗 [`netflix_newshows_and_movies.py`](./netflix_newshows_and_movies.py)

This script includes:
- Handling missing values
- Standardizing columns (e.g., country, genre)
- Feature extraction (year, duration buckets)
- Visualization and analysis for all key business questions

Each insight directly supports the overall goal: identifying what kind of content Netflix should invest in by region, genre, and format.

---


## 📌 Tools Recommended

- Python (Pandas, Matplotlib/Seaborn, Plotly)
- SQL (for content filtering by region/year/genre)
- Jupyter Notebook for analysis

---

> 📈 This analysis mimics real-world business challenges faced by data teams at streaming platforms. Use it to sharpen both your analytical and storytelling skills.
