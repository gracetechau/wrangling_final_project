# Data Folder

## raw_data

This folder contains original, unmodified data files after downloading and scraping.

- 2010-2024_Movies_Box_Ofice_Collection_raw.csv
- letterboxd_movie_data_2017_raw_1.csv
- letterboxd_movie_data_2017_raw_2.csv
- letterboxd_movie_data_2017_raw_3.csv
- letterboxd_movie_data_2017_raw_4.csv
- letterboxd_movie_data_2018_raw_1.csv
- letterboxd_movie_data_2018_raw_2.csv
- letterboxd_movie_data_2018_raw_3.csv
- letterboxd_movie_data_2019_raw_1.csv
- letterboxd_movie_data_2019_raw_2.csv
- letterboxd_movie_data_2019_raw_3.csv

## clean_data

This folder contains data files after all cleaning, processing and analyzing.

- box_office_revenue_2017.2019_clean.csv
- letterboxd_movie_data_2017_clean.csv
- letterboxd_movie_data_2018_clean.csv
- letterboxd_movie_data_2019_clean.csv
- letterboxd_movie_data_2017.2019_clean.csv
- 2017_2019_final_film_data.csv

# Data Dictionary

| Column            | Type    | Source     | Description                                                                                                 |
| ----------------- | ------- | ---------- | ----------------------------------------------------------------------------------------------------------- |
| title             | Text    | Both       | Title of the movie                                                                                          |
| year              | Numeric | Both       | Year the movie was released                                                                                 |
| worldwide_revenue | Numeric | Kaggle     | Revenue in U.S. dollars that the movie made at the box office worldwide (in millions)                       |
| domestic_revenue  | Numeric | Kaggle     | Revenue in U.S. dollars that the movie made at the box office in the United States and Canada (in millions) |
| domestic_percent  | Numeric | Kaggle     | Percentage of worldwide box office revenue that is attributed to domestic box office revenue                |
| foreign_revenue   | Numeric | Kaggle     | Revenue in U.S. dollars that the movie made at the box office in foreign countries (in millions)            |
| foreign_percent   | Numeric | Kaggle     | Percentage of the worldwide box office revenue that is attributed to foreign box office revenue             |
| number_ratings    | Numeric | Letterboxd | Total count of ratings the movie has by Letterboxd users                                                    |
| average_rating    | Numeric | Letterboxd | Average star rating of the movie out of 5                                                                   |
| length            | Numeric | Letterboxd | Length of the movie in minutes                                                                              |
| genre             | Text    | Letterboxd | Genre of the movie                                                                                          |
