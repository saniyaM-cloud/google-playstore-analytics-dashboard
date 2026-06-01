# Google Play Store Analytics Dashboard

## Project Overview
This project is an extension of my training project and was developed as part of my internship. It uses the same Google Play Store dataset to build additional analytics dashboards and reports using Python, Pandas, Plotly, and Jupyter Notebook.

The project focuses on analyzing app ratings, installs, reviews, revenue, categories, app size, update trends, and user sentiment.

## Dataset Used
- `googleplaystore.csv`
- `googleplaystore_user_reviews.csv`

The dataset includes app details such as category, rating, reviews, installs, size, price, content rating, Android version, last updated date, and user review sentiment.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Plotly
- NLTK
- Scikit-learn
- HTML/CSS

## Data Transformations
- Removed missing and duplicate values
- Cleaned installs, price, reviews, and size columns
- Converted dates into datetime format
- Created revenue and log-based columns
- Performed sentiment analysis on user reviews
- Applied category, rating, installs, size, review, and time-based filters

## KPIs Measured
- Total installs
- Average rating
- Total reviews
- Revenue
- Category-wise app distribution
- Free vs paid app performance
- Sentiment score
- Monthly install growth
- Cumulative installs over time

## Dashboard Features
- Interactive Plotly charts
- Category-wise analysis
- Rating and review analysis
- Revenue analysis
- Sentiment analysis
- Time-series install trends
- Bubble chart for app size vs rating
- Stacked area chart for cumulative installs
- Time-restricted dashboards based on IST
- Multilingual category labels in selected charts

## Internship Tasks Implemented
- Task 1: Grouped bar chart for ratings and reviews by top installed categories
- Task 2: Choropleth map for global installs by category
- Task 3: Dual-axis chart comparing installs and revenue for free vs paid apps
- Task 4: Time series chart showing install trends by category
- Task 5: Bubble chart showing app size vs rating with installs as bubble size
- Task 6: Stacked area chart showing cumulative installs over time

## How to Run
1. Clone the repository.
2. Open `Analysis2.ipynb`.
3. Install the required libraries.
4. Run all notebook cells.
5. Open the generated `dashboard.html` file.

## Screenshots
Add screenshots of:
### Main Dashboard: Google Play Store Reviews Analytics

This dashboard provides an overall view of Google Play Store app analytics using interactive Plotly visualizations. It includes category distribution, app type distribution, rating distribution, sentiment analysis, installs by category, yearly update trends, revenue by category, genre analysis, update impact on ratings, and paid vs free app rating comparison.

The dashboard helps summarize key insights from the Google Play Store dataset in one place and supports interactive exploration of app performance metrics.

![Main Dashboard](https://github.com/user-attachments/assets/a207cdbc-a3db-4b6d-8143-e961ec584208)


### Task 1: Average Rating and Total Reviews for Top Installed Categories

This grouped bar chart compares the average rating and total review count for the top 10 app categories based on number of installs. The green bars represent average rating, while the red bars represent total reviews.

Filters applied include average rating, app size, and January last update month.

This chart is displayed on the dashboard only between 3 PM and 5 PM IST.

![Task 1 Grouped Bar Chart](https://github.com/user-attachments/assets/b941768c-f751-4bf8-978c-ee357cd4267c)
- Task 2 chart
### Task 3: Average Installs and Revenue for Free vs Paid Apps

This dual-axis chart compares average installs and total revenue across the top filtered app categories. The bars represent average installs, while the line represents revenue.

Filters applied include installs, revenue, Android version, app size, content rating, and app name length.

Due to the revenue filter, the final filtered dataset contains paid apps only, since free apps generate zero direct revenue.

![Task 3 Dual Axis Chart](https://github.com/user-attachments/assets/46f6dfc1-9e3c-46c0-a851-709689e9ac49)

- Task 4 chart
- Task 5 chart
- Task 6 chart

## Project Outcome
This project demonstrates practical data analysis, interactive visualization, dashboard development, and insight generation using a real-world app marketplace dataset.

## Author
Saniya Ganesh Madhavi
