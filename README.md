# Movie-Ratings-Bias-Analysis
# Movie Ratings Bias Analysis

This repository contains a portfolio-ready exploratory data analysis project that investigates whether **Fandango movie ratings appeared inflated in 2015** compared with other popular rating platforms.

## Project goal

The main question is simple:

> If a platform both shows movie ratings and sells movie tickets, can that create a more favorable presentation of ratings?

To explore this, the notebook compares Fandango scores with ratings from:

- Rotten Tomatoes
- Metacritic
- IMDb

## What this project demonstrates

- data cleaning and preparation with **pandas**
- exploratory data analysis and visual storytelling
- cross-platform metric comparison
- normalization of different rating scales to a common **0–5 range**
- interpretation of findings in a business context

## Tech stack

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- Jupyter Notebook

## Main findings

- Fandango ratings are concentrated in the higher range.
- Displayed star values can appear higher than the underlying numeric rating.
- After normalizing the scales, Fandango still appears more generous than competing platforms.
- The gap is especially noticeable for low-rated films.

## Files

- `movie-ratings-bias-analysis.ipynb` — main analysis notebook
- `requirements.txt` — Python dependencies
- `.gitignore` — recommended Git ignore rules

## Dataset

The notebook expects the following CSV files in the same folder as the notebook:

- `fandango_scrape.csv`
- `all_sites_scores.csv`

These files come from the original FiveThirtyEight movie ratings dataset.

## How to run

```bash
pip install -r requirements.txt
jupyter notebook
```

Then open:

```bash
movie-ratings-bias-analysis.ipynb
```

## Portfolio note

This version was cleaned for GitHub publication:
- removed course-template elements
- removed placeholder cells and draft calculations
- added business framing and final conclusions
- kept the analysis focused and readable
