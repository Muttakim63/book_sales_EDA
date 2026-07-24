# Book Sales Exploratory Data Analysis

An exploratory data analysis (EDA) of a 1,070-book sales dataset, examining genre distribution, author performance, pricing, ratings, and revenue trends across publishers.

## Project Overview

This project investigates a real-world-style book sales dataset to answer questions like:

- Does book price actually influence how many units sell?
- Are the highest-rated authors also the top sellers?
- Which genres, publishers, and languages dominate the market?
- How has total sales volume changed across publishing years?

## Dataset

- **Source file:** `data/Books_Data_Clean.csv`
- **Size:** 1,070 rows × 15 columns (988 rows after cleaning)
- **Key fields:** Publishing Year, Book Name, Author, Genre, Author Rating, Book Average Rating, Ratings Count, Gross Sales, Publisher Revenue, Sale Price, Units Sold, Language Code

## Key Findings

- **Genre fiction dominates** the dataset (759 of 988 books) over 4x the next largest category (nonfiction).
- **Sale price has virtually no relationship with units sold** (correlation ≈ 0.02) indicates pricing alone doesn't explain sales performance.
- **Rating quality and commercial success are largely independent.** The top-rated authors (Bill Watterson, Tolkien, George R.R. Martin) don't appear among the top sellers by gross sales (Harper Lee, Stephen King, David Sedaris).
- **The market is heavily English-language and publisher-concentrated** — Penguin Group, Random House, and Amazon Digital Services account for the large majority of total publisher revenue.
- **Total units sold peaked in 2012** (~765,000 units) before declining toward 2016, though this likely partly reflects newer titles not yet having accumulated their full sales history.

## Tech Stack

- **Python** — pandas, matplotlib, seaborn
- **Jupyter Notebook** for analysis and visualization
