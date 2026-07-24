# Movie Rental Analysis

A single Jupyter notebook performing basic descriptive analytics on a movie rental transactions CSV — monthly revenue trends, top 10 movies by revenue, and customer spending distribution.

## What it does

Reads a 683-row CSV of movie rental transactions (rental_id, customer_id, movie_title, rental_date, final_fee, etc.), plots a monthly revenue line chart, a top-10 movies bar chart, and a customer spending histogram. Three of four cells work. The fourth cell attempts a "Revenue by Genre" analysis but crashes with a `KeyError: 'genre'` because the dataset has a `category` column, not `genre`.

## Tech stack

Python, pandas, matplotlib, Jupyter

## Status

**Incomplete academic exercise.** Three visualizations render correctly; one analysis cell is broken (references a non-existent column). The dataset CSV is included. Hardcoded absolute file path must be updated to run on another machine. No README existed before this rewrite — originally abandoned mid-development.