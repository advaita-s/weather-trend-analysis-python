# Weather Trend Analysis Using Python

This individual project presents a clean and practical approach to analyze temperature trends over time using real-world weather data. Built entirely in Python, it utilizes Open-Meteo's free weather API to fetch historical hourly temperature data for a given city, and visualizes it using time series plots.

## Project Overview

The project is implemented in two stages:

1. **Single City Analysis** – Fetches and plots both hourly and daily average temperature trends for a specified city over the past 7 days.
2. **Multi-City Comparison** – Compares daily average temperature trends of multiple cities (e.g., Mumbai, Coimbatore, Chennai) on a single graph.

All data fetching and processing are done using Python libraries like `requests`, `pandas`, and `matplotlib`.

## Key Features

📅 Historical weather data visualization (past 7 days)
Visualize recent temperature patterns using real-world hourly data.

🌍 Supports any city name (via geocoding)
Dynamically fetch data for any city using Open-Meteo’s built-in location search.

📈 Clear temperature trendlines
Generate clean, easy-to-read plots showing hourly and daily trends.

📊 Daily aggregation using time series resampling
Resample hourly data into daily averages using Pandas time series capabilities.

🏙️ Multi-city comparison with Matplotlib
Compare daily average temperatures of multiple cities on a single graph.

☁️ Fully executable in Google Colab or local Jupyter Notebook
Run the entire project seamlessly in the cloud or your local machine.

## Sample visuals

![single_city_hourly_plot](https://github.com/user-attachments/assets/46bbc0c7-3453-4da0-87cb-795cfa1350a7)

![single_city_daily_avg_plot](https://github.com/user-attachments/assets/cfdbb4e5-14ae-45b1-ad97-b2d4462119b3)

![multi_city_comparison_plot](https://github.com/user-attachments/assets/6d446176-b2f5-46f4-b589-fa68899b56bc)

## 📊 Libraries Used

- `pandas` – for data manipulation and time series resampling
- `matplotlib` – for plotting temperature trends
- `requests` – for API requests and geolocation
- `datetime` – for date calculation

## How It Works

1. City names are geocoded to get latitude and longitude using Open-Meteo's geolocation API.
2. Historical hourly weather data is pulled from Open-Meteo’s archive endpoint.
3. Data is processed and resampled to daily averages.
4. Visualizations are created for both single-city and multi-city scenarios.

## Use Case

This project demonstrates how open weather data can be analyzed using Python for:

- Academic or personal data science projects
- Environmental research
- Climate comparisons across regions
- Learning time series data manipulation and visualization

## Advantages of This Approach

- No web scraping: clean, API-based data retrieval
- No authentication required: Open-Meteo is free and open

## Data Source

> **Data Source**: Weather data provided by [Open-Meteo](https://open-meteo.com/), a free weather API for open use.

## ✅ Author
Advaita_S_S
BSc Computer Science (Data Analytics) Student
This project is developed as an individual effort focused on applying data analysis and time series concepts using real-world datasets and work developed for academic and portfolio use.





