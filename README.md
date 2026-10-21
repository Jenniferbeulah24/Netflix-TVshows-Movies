# Netflix Movies and TV Shows — Data Analysis

## Project Overview
This project analyzes Netflix movies and TV shows using data analysis and visualization techniques. The aim is to understand Netflix's content trends, production geography, audience maturity, ratings, popularity, and potential opportunities for future content expansion.

## Objectives
- Analyze Netflix's catalog growth and content distribution.
- Study movie runtimes and TV show seasons.
- Explore production countries and content maturity ratings.
- Examine relationships between IMDb scores, popularity, and votes.
- Analyze director and actor performance.
- Identify potential content gaps and strategic opportunities.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab
- Statistical analysis and data visualization

## Dataset
The project uses the Netflix Movies and TV Shows dataset from Kaggle.

Dataset link: https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies?utm_source=chatgpt.com

## Files used:
- titles.csv
- credits.csv

### Team Contributions

## Jennifer Beulah(Team Lead)
Talent Impact, Engagement Mechanics & Statistical Correlations

 ## Role & Objective:
 You are responsible for analyzing the statistical relationships across Netflix metrics and evaluating talent ROI. You will merge credits with titles to rank the most successful directors and actors, test whether popularity correlates with high review scores, and compute Pearson correlation matrices with formal p-value hypothesis testing.

## Deliverables
Chart 1: Correlation Heatmap Matrix with annotated r-coefficients.
Chart 2: IMDb Score vs. TMDB Popularity Scatter & Regression Plot.
Chart 3: Top 10 Directors & Actors Leaderboard (≥3 projects on platform).
Written Insights: 3–4 bullet points detailing statistical significance and talent performance.

## Joshita 
Data Cleaning, Strategic Gap Analysis & Opportunity Modeling

## Role & Objective: 
I am responsible for building the main data cleaning code and finding hidden opportunities where Netflix should make more shows. I will fix broken text data so Python can read it, safely fill in missing information without deleting important rows, and create a custom "Opportunity Score." This math formula balances average audience ratings, total viewer interest, and how many similar shows already exist. This powers a 4-Quadrant Bubble Chart to highlight the best highly-rated niches for Netflix to invest in next.

## Deliverables

## Data Cleaning: 
Master Data Cleaning Code (fixing text lists and safely filling missing data).

Chart 1: 4-Quadrant Strategic Bubble Chart (showing Market Supply on the X-axis, Audience Rating on the Y-axis, and Total Viewer Interest as the bubble size).
Why I calculated it: To go beyond simple popularity by combining average ratings, viewer interest, and current market supply into one single math score.
Why it is important: It stops us from falling for the "rating trap" (niches with high scores but very few real viewers) and ignores overcrowded markets, helping to find true gaps where audiences want more content.
Business Value for Netflix: It helps Netflix executives spend their budget safely by creating shows in areas with guaranteed high demand, which keeps subscribers happy and lowers financial risk.


## Methodology
1. Load the dataset into Python.
2. Clean missing, duplicate, and inconsistent values as required.
3. Perform exploratory data analysis.
4. Create charts and visualizations.
5. Apply correlation analysis and statistical tests where appropriate.
6. Interpret the findings and identify potential content opportunities.

## How to Run the Project
1. Download or clone this repository.
2. Download the dataset from the Kaggle link above.
3. Place titles.csv and credits.csv in the location expected by the notebook.
4. Open the .ipynb notebook in Google Colab or Jupyter Notebook.
5. Install any required libraries that are not already available.
6. Run the notebook cells in order.

## Key Findings
## 🔍 Key Findings:
- **Country Distribution:** The US contributes the largest catalog share (35.6%), followed by India (9.5%).
- **Age Certification:** TV-MA is the most common TV show rating, while R is the most common movie rating.
- **IMDb Rating Trends:** TV shows generally achieve higher average IMDb scores than movies in many recent years.
- **Production Trends:** Movie and TV show releases increased significantly after 2015.
- **Runtime Analysis:** Movies have a median runtime of approximately 98 minutes, compared with 40 minutes for TV shows.
- **Correlation Analysis:** IMDb and TMDB scores show a moderate positive correlation (0.57).
- **Popularity Analysis:** IMDb scores and TMDB popularity show almost no linear correlation (0.02).
- **Top Performers:** The analysis highlights actors and directors associated with high average IMDb scores.
- **Genre Analysis:** Drama has the highest production volume, while history and war have relatively high average ratings.

### 📌 Conclusion:
The analysis explores patterns in Netflix's content library, including country distribution, content maturity, production trends, ratings, popularity, runtime, and genre performance.

## Team Members
Jennifer Beulah
A. Prem Steiven Doss
Joshita. S
S. Sairam

## Acknowledgements
Dataset source: Kaggle.
