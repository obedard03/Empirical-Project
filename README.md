# Gender Discrepancies in Media 

This project will analyse representation of gender in media, specifically movies, using the Cornell Movie-Dialog Corpus. This project explores proportions of speaking roles, weight of dialogue per gender, how this has changed over time and gender-dominating genres over time.

## Repository Overview 
This repository is structured as follows:

Empirical-Project/ 
├── blog.ipynb # Jupyter Notebook with all analysis 
├── Makefile
├── data/ # NOT tracked in GitHub (see below) 
│ ├── movie_lines.txt
│ ├── movie_characters_metadata.txt 
│ ├── movie_titles_metadata.txt 
├── output/ 
│ └── dialogue_trend_by_gender.png 
├── scripts/ 
│ └── analyze_dialogue_gender.py 
└── README.md

All data is contained in the data sub-directory, all source code is contained in source, and all output is automatically exported to results.

## Requirements 
Install the following Python packages (ideally in a virtual environment):

bash
pip install pandas matplotlib seaborn nltk


note versions of python being used... and "I used Pandas 3.2.0..."

## Running instructions
