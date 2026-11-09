# EarthquakeProject
## Project Overview
This project analyzes real-world earthquake data from the United States Geological Survey (USGS) using Python. The goal is to examine earthquake frequency, magnitude, depth, and location, and understand their potential impact on buildings and infrastructure.

## Dataset
The dataset was obtained from the USGS Earthquake Catalog and contains 759 earthquakes with magnitudes of 4.5 or greater over a 30-day period (starting 11/8 going back to 10/9).

The main variables used were time, latitude, longitude, depth, magnitude, place, and event type.

## Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab

## Analysis
The project uses Python to classify earthquakes mainly by magnitude and depth, and identify events with magnitudes of 5.0 or greater.

Four graphs were created:

- Histogram of earthquake magnitudes
- Scatter plot of magnitude vs. depth
- Bar chart of earthquakes by magnitude category
- Location-based scatter plot of earthquakes


## Main Findings
Of the 759 earthquakes analyzed, the majority (549) had magnitudes below 5.0, and most were also (608) classified as shallow earthquakes.

There were 210 earthquakes with magnitudes of 5.0 or greater, including two major earthquakes. The largest recorded magnitude was 7.7.

The data suggests that most recorded earthquakes were relatively weak and shallow, although the dataset is limited to a 30-day period and excludes earthquakes below magnitude 4.5.

## How to Run
1. Open `earthquakes.ipynb`
2. Fix file path in code to `Earthq_4.5up_last30.csv`
3. Run the program. 

The program uses Pandas and Matplotlib.

## Project Files
- `earthquakes.ipynb` — Python, analysis, and visualizations
- `Earthq_4.5up_last30.csv` — USGS earthquake dataset
- `EarthquakeReport.pdf` — interpretation and project report

## Data Source
USGS Earthquake Catalog: https://earthquake.usgs.gov/earthquakes/search/
