# California Public EV Chargers Analysis

## Project Overview
The goal of this project is to explore public electric vehicle (EV) chargers in California and find which cities have the most and fewest chargers.

**Research Question:** Which areas of California have the most public EV charging stations, and which areas have the fewest?

## Data Source
The data comes from the California Energy Commission.

Dataset: [Public Chargers as of March 13, 2025](https://sandbox.data.ca.gov/dataset/public-chargers-as-of-march-13-2025)

The original dataset contains 17,186 rows and 12 columns.

## Data Cleaning
I used Python and pandas to check missing values and duplicates. I replaced the missing ZIP code with `Unknown` and created a new column called `Total_Chargers` to calculate the total chargers at each location.

## Key Findings
- **Los Angeles** had the most chargers, with 4,122 chargers across 1,550 charging locations.
- **San Diego** ranked second, with 2,373 chargers.
- **Level 2 chargers** were the most common, with 37,151 chargers.
- The dataset recorded only one charger for each of the 10 cities at the bottom of the results.

## Visualizations
The notebook includes three charts:
1. Top 10 cities by total EV chargers.
2. Chargers by type.
3. Ten cities with the fewest recorded chargers.

## Limitations
The data is from March 13, 2025, so it may not show current charger availability. The results describe the recorded
