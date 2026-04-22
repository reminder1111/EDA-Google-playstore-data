# EDA Google Play Store Data

This project is a simple Exploratory Data Analysis (EDA) of Google Play Store app data.

## Dataset

The analysis uses the `googleplaystore.csv` file included in this repository.  
This dataset contains app details such as:
- app name
- category
- rating
- reviews
- size
- installs
- type
- price
- content rating
- Android version

## What Happens In This EDA

In the notebook, the data is first loaded and explored using basic checks like shape, columns, summary statistics, and data types.

After that, some cleaning is done:
- duplicate rows are removed
- `Reviews` is converted to numeric
- `Size` is cleaned and converted into a usable numeric format
- `Installs` and `Price` are cleaned by removing symbols like `+`, `,`, and `$`
- some text cleanup is done for columns like `Android Ver`

Then the notebook explores patterns in the data using plots and groupby analysis, mainly around:
- app categories
- ratings
- installs
- pricing
- app type
- content rating

## Purpose

The main purpose of this EDA is to understand the Google Play Store dataset better and find useful trends in app data.

It helps answer simple questions like:
- which categories are most common
- which app categories have the highest installs
- how ratings are distributed
- how free and paid apps differ
- how pricing and reviews look across the dataset

## Files

- `1.EDA-Google playstore data.ipynb` : Jupyter notebook with the full EDA
- `googleplaystore.csv` : dataset used in the notebook
