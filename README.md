# Uber Data Analysis

## Project Objective
Perform exploratory data analysis on Uber trip data to find patterns such as busiest hours, trip distance distribution, and demand trends.

## Dataset
- Source: Udemy data analytics project course
- Columns include: date/time, pickup location, trip distance, etc.

## Tools & Libraries
- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn

## What’s Inside
- `Uber data analysis.ipynb`: Notebook with full EDA
- Visualizations: time distribution, frequency of trips, etc.

## Key Insights
- Time-Based Demand Patterns

It is observed that the during friday and saturday, the pickups were highest after the midnight comapared to any other day.
For all the days, the pick-ups peak after 4 pm indicating the rush in uber rides.
Lowest demand occurs between 2 AM and 4 AM, indicating minimal travel activity during these hours.

- Daily Trends

Fridays and Saturdays consistently recorded the highest number of pick-ups across all months, while Mondays, Tuesdays and Wednesdays remained the lowest.
After the high demand on Fridays and Saturdays, Sundays have shown a drastic dip in demands.
In April month, peak in observed in the weekday (on Thurday) and the pickups on Wednesday and Thursday are more than pickups on Friday and Saturday.

- Monthly Trends

The pick-ups have been steadily increased from January to June.
Pick-ups increased steadily from January to June, peaking in May and June — indicating growing activity toward mid-year.

- Base-wise Ride Distribution

The highest rides and vehicles for the base number - B02764.
The lowest rides and vehicles for the base number - B02512.



## How to Run
Install libraries:
```bash
pip install pandas numpy matplotlib seaborn
