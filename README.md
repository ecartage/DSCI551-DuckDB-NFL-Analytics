# DSCI551-DuckDB-NFL-Analytics

DuckDB NFL Analytics App
DSCI 551 Final Project — Emanuel Cartagena
Overview
A Streamlit application that runs analytical queries on NFL 2025 play-by-play data using DuckDB. Users can view player and team statistics filtered by season type with interactive charts and DuckDB execution plans.
Dependencies
Python 3.8+ is required. Install dependencies with:
pip install streamlit duckdb
Dataset
The dataset used is the NFLFastR 2025 play-by-play Parquet file (play_by_play_2025.parquet). It is included in this repository. Make sure it is in the same directory as 551_demo.py before running.
How to Run

Clone the repository

git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

Navigate into the project folder

cd YOUR_REPO_NAME

Install dependencies

pip install streamlit duckdb

Run the app

streamlit run 551_demo.py
The app will open automatically in your browser.
Application Modes

Player Total Stats — ranks all receivers by a chosen stat
Player Comparison — compares two players head to head
Team Total Stats — ranks all 32 teams by a chosen stat
Team Per-Game Avg — normalizes team stats by games played

No API Keys Required
This project requires no secret keys, API keys, or credentials of any kind.Sonnet 4.6
