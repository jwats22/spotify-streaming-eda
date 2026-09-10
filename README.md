# Spotify Streaming Data Analysis

An exploratory data analysis (EDA) project examining Spotify streaming data to identify patterns in streaming performance, popularity, artists, genres, audio characteristics, and song distributions.

## Project Overview

This project uses Python to explore factors associated with Spotify streaming performance. The analysis is organized around 10 questions and uses data aggregation, visualization, and correlation analysis to identify patterns within the dataset.

## Questions Explored

1. Which genres receive the most streams?
2. Which artists receive the most streams?
3. How do streams differ across songs released from 2020–2025?
4. Does Spotify popularity relate to stream count?
5. Do explicit songs receive more streams than non-explicit songs?
6. Does danceability relate to stream count?
7. Does energy relate to stream count?
8. Which countries have the highest average stream counts?
9. What is the distribution of Spotify popularity scores?
10. What is the distribution of song durations?

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings

- Pop had the highest total streams, followed by R&B.
- Spotify popularity had a moderate positive correlation (0.40) with stream count.
- Danceability and energy showed essentially no linear relationship with stream count.
- Non-explicit songs had slightly higher average streams than explicit songs, although the difference was small.
- Most songs had Spotify popularity scores around 20–40.
- Most songs were approximately 3–4 minutes long.
- Popularity appeared more related to streaming performance than the individual audio characteristics examined.

## Correlation Analysis

A correlation heatmap was used to examine relationships between numerical variables. Popularity had the strongest positive relationship with stream count among the original variables examined, while most individual audio characteristics had correlations close to zero.

Correlation does not imply causation, so these relationships should not be interpreted as evidence that one variable directly causes another.

## Dataset

The dataset used for this project contains Spotify streaming information, including stream counts, artists, genres, popularity scores, audio characteristics, release information, and country associations.

**Dataset Source:** (https://www.kaggle.com/datasets/beamhonor0911/spotify-artist-streaming-analytics-20202025)

## View the Analysis

- **Jupyter Notebook:** Open the `.ipynb` file in this repository.
- **Kaggle Notebook:** (https://www.kaggle.com/code/justinw1/exploring-spotify-streams-what-the-data-reveals)

## Future Improvements

This analysis could be extended with:

- Streaming performance prediction
- More detailed genre and artist comparisons
- Music trend analysis
- Further analysis of Spotify audio features
