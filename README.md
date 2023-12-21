# Movie Database Analysis Project

## Overview
This project involves analyzing a movie database, including Netflix titles, ratings, countries, and categories. The analysis includes fetching additional rating details using an external API, visualizing the data through graphs and word clouds, and exploring various insights.

## Project Structure

### Files
- `utils.py`: Contains utility functions for dataset summarization and Pandas configuration.
- `mydatabase.db`: SQLite database file containing the processed data.
- `netflix_titles.csv`: The original dataset file.
- `gist_stopwords.txt`: Stopwords file used for word cloud generation.

### Notebooks/Scripts
- `main_script.py`: Main script for data processing and analysis.

## Requirements
- Python 3.x
- Required Python packages: pandas, sqlite3, requests, wordcloud, matplotlib

## Setup
1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Install the required packages.

## Usage
1. Run `main_script.py` to perform data processing and analysis.
2. View the generated graphs and word clouds to gain insights.

## API Key
Ensure you have a valid API key for the [Movies Database API](https://moviesdatabase.p.rapidapi.com/). Update the `X-RapidAPI-Key` in `main_script.py` for proper functioning.

## Note
- Be mindful of API rate limits, especially in the free version.

## Contributors
- [Selim Koç](https://github.com/sselimkoc)
