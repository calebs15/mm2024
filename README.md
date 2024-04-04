# mm2024
Statistics and visualizations for March Madness 2024

Goal: To create a Python notebook capable of scraping data from college basketball teams and turn this data into informative vizualizations

Overview:
- used Python to scrape data from the official [NCAA mens college basketball statistics website](https://www.ncaa.com/stats/basketball-men/d1/current/team/145)
  - data was not available to download as a csv, so data was scraped from 26 different statistics pages, each with 8 pages of data
- used pandas to create multiple dataframes for data manipulation
- used matplotlib and seaborn to vizualize different statistics

Challenges:
- learning how to most efficiently scrape data from 26 different urls containing 8 page references each
- learning how to use matplotlib to customize vizualizations and concisely display data
- cleaning data within pandas dataframes

Successes:
- using loops, joined 26 different dataframes containing data from 351 D1 NCAA men's college basketball teams
  - further drilled down this data to include only teams present for the field of 68 selected March Madness 2024 teams
- created unique vizualizations utilizing Python libraries to present findings within the data
