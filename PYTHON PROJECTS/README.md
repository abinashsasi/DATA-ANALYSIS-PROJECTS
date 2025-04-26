# Netflix Data Analysis Project

## Overview

This project analyzes the Netflix dataset to derive insights into content trends, production patterns, and viewer demographics. It combines Python-based data analysis with an interactive Power BI dashboard.

## Files

* `net.ipynb`: Jupyter Notebook containing the Python analysis and visualizations.
* `netflix_titles.csv`: The dataset used for analysis.
* `Netflix_Dashboard.pbix`: Power BI dashboard file.
* `README.md`: Project documentation.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Power BI

## Analysis Highlights

* **Content Type Distribution:** Movies constitute a larger share of content compared to TV shows (approximately 70% vs. 30%).
* **Content Release Trends:** Content releases have generally increased over the years, indicating platform growth.
* **Genre Analysis:**
    * Popular genres for movies include Dramas, International Movies, and Comedies.
    * Popular genres for TV shows include International TV Shows, Crime TV Shows, and Docuseries.
* **Country-wise Analysis:** Content production varies across different countries.
* **Rating Analysis:** Distribution of content across different age ratings.
* **Actor/Director Analysis:** Identification of frequently appearing actors and directors.

## Setup

1.  Clone the repository.
2.  Ensure Python 3.x is installed.
3.  Install the required Python libraries:

    ```bash
    pip install pandas numpy matplotlib seaborn plotly
    ```
4.  Open and run the `net.ipynb` notebook to reproduce the Python analysis.
5.  Open the `Netflix_Dashboard.pbix` file in Power BI Desktop to interact with the dashboard.

## Data Dictionary

1.  **show_id:** Unique ID for every Movie / TV Show
2.  **type:** Identifier - A Movie or TV Show
3.  **title:** Title of the Movie / TV Show
4.  **director:** Director of the Movie
5.  **cast:** Actors involved in the movie / show
6.  **country:** Country where the movie / show was produced
7.  **date_added:** Date it was added on Netflix
8.  **release_year:** Actual Release year of the movie / show
9.  **rating:** TV Rating of the movie / show
10. **duration:** Total Duration - in minutes or number of seasons
11. **listed_in:** Genre
12. **description:** The Summary description

## Key Python Analysis Steps

1.  **Import Libraries:** Imported necessary libraries (Pandas, NumPy, Matplotlib, Seaborn, Plotly).
2.  **Load Dataset:** Loaded the Netflix dataset (`netflix_titles.csv`).
3.  **Data Exploration:**
    * Checked the dimensions of the dataset.
    * Checked data types and missing values.
    * Generated descriptive statistics.
4.  **Data Cleaning:**
    * Handled missing values by filling or dropping rows/columns.
    * Removed any duplicate entries (if present).
5.  **Data Visualization (using Plotly):**
    * Visualized content distribution by type (Movie/TV Show).
    * Analyzed content by country.
    * Examined content ratings.
    * Plotted release year trends.
    * Visualized genre distribution.
    * Analyzed duration of content.
    * Identified top actors and directors.

## Key Insights from Python Analysis

* **Content Type:** A higher proportion of Movies compared to TV Shows.
* **Release Year Trends:** General increase in content releases over the years.
* **Genre Distribution:**
    * Movies:  Dramas, International Movies, and Comedies are common.
    * TV Shows: International TV Shows, Crime TV Shows, and Docuseries are prevalent.
* **Top Actors/Directors:** Identified key contributors based on content volume.

## Power BI Dashboard

The Power BI dashboard provides an interactive way to explore the data, with filters and visualizations for:

* Content Type Distribution
* Content by Rating
* Content by Genre
* Content by Country
* Content Over Time
* Top Cast
* Top Directors

## Contributions
ABINASH SASIKUMAR
abitheanalyst@gmail.com

