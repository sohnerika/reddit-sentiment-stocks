# Ozempic Sentiment and Novo Nordisk Stock Analysis

## Overview
My first ever data science project, completed as a team for DS2500 at Northeastern. We investigated whether public sentiment about Ozempic on Reddit could predict movements in Novo Nordisk's (NYSE: NVO) stock price. Using the PRAW API, we collected March 2025 posts from subreddits including r/Ozempic, r/stocks, r/Diabetes, and r/wallstreetbets, scored them with VADER sentiment analysis (weighted by upvotes), and aligned them to daily closing prices from Bloomberg, accounting for after-hours and weekend posts.

We then used time-series analysis and linear regression to test the relationship. We found no significant correlation between Reddit sentiment and stock price (r = -0.014, p = 0.95), suggesting factors like macroeconomic trends and company announcements matter far more than online sentiment. A subreddit heatmap did reveal a clear split: health-focused communities skewed negative while finance communities skewed positive.

## Files
- `report.pdf`: Full project report with methodology, results, and future work
- `slides.pdf`: Presentation slides
- `data/`: Reddit sentiment and stock price datasets

*Note: The original source code is not included in this repository.*

## Skills
Python, Pandas, PRAW API, NLP, VADER sentiment analysis, time-series analysis, linear regression, data visualization

## Team
Rishona Shelby Israel, Kathleen Lautenbach, Mahika Modi, Erika Sohn
