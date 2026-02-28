# Data Challenge Project, Team 3 (Restaurant Reviews)

This repository contains our Team 3 submission for the Data Challenge project. The goal is to analyze the provided restaurant reviews dataset, clean the data, answer the assigned questions, and present results using a notebook and a short video demo.


## Repository Contents

- **`group3DataChallengeReal.ipynb`**  
  The main solution notebook. Includes:
  - Data loading and exploration
  - Data cleaning steps with assumptions/decisions
  - Analysis answering all 6 assigned questions
  - Visualizations (4 plots) with brief interpretations

- **`team03_restaurant.csv`**  
  The dataset used for this project (Restaurant Reviews for Team 3).

- **`copy_28B6D265-F28D-459F-8E32-00A95D99C4D4.mp4`**  
  Video demo walkthrough of the notebook, showing how the code runs and highlighting key findings/visualizations.

- **`README.md`**  
  This file, explaining the purpose and structure of the repo.



## Project Questions Answered

1. What is the average rating by price range?  
2. Which cuisine type receives the highest ratings?  
3. How does wait time correlate with ratings?  
4. Do delivery orders have different ratings than dine-in?  
5. Which day of the week has the highest average rating?  
6. What percentage of reviews are 4 stars or higher by meal time?


## Workflow Summary

### Step 1: Setup
- Created a GitHub repository and added the dataset, notebook, and demo video.

### Step 2: Data Exploration
- Loaded the dataset and inspected structure (shape, columns, types).
- Checked for missing values, duplicates, and basic validity.

### Step 3: Data Cleaning
- Preserved the original dataset and cleaned a copy.
- Handled missing numeric values using median imputation when needed.
- Ensured numeric fields were stored as numeric types.
- Standardized text formatting for categorical columns when needed.
- Validated results by rechecking missing values, types, and ranges.

### Step 4: Analysis
- Used groupby summaries, calculated metrics, correlation, and a t-test where appropriate.
- Documented insights for each assigned question.

### Step 5: Visualization
- Created 4 meaningful visualizations with clear titles and axis labels.
- Saved plots and interpreted results.


## Key Findings

- Ratings are very similar across price ranges, with only small differences.
- American cuisine has the highest average rating in this dataset.
- Wait time and rating have essentially no meaningful correlation.
- Delivery ratings are slightly higher than dine-in on average, but not statistically significant.
- Monday has the highest average rating, while weekend ratings are lower.
- Dinner and lunch have the highest percentage of 4+ star reviews, breakfast is slightly lower.
