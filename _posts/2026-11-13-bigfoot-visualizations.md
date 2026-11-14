---
layout: post
title: "Bigfoot Visualizations"
date: 2026-11-13
---

## Visualization 1: Sightings by State

<iframe src="{{ '/charts/bigfoot_states.html' | relative_url }}" width="100%" height="580" style="border:none;"></iframe>

For my first visualization, I created a bar chart showing the 15 states with the most reported Bigfoot sightings. I used a nominal encoding for the states on the y-axis and a quantitative encoding for the number of sightings on the x-axis. I also used a blue color scheme where darker shades represent more sightings. I chose this because it makes it easier to see which states have the most reports. In my Python notebook, I grouped the data by state, counted the number of reports, and sorted the results to find the top 15 states. I also added tooltips so users can hover over the bars to see the state and its total number of sightings.

## Visualization 2: Sightings Over Time

<iframe src="{{ '/charts/bigfoot_years.html' | relative_url }}" width="100%" height="500" style="border:none;"></iframe>

For my second visualization, I created a line chart showing how reported Bigfoot sightings have changed over time. I used an ordinal encoding for the year on the x-axis and a quantitative encoding for the number of sightings on the y-axis. I kept the line blue because I wanted the chart to be simple and easy to read without having too many different colors. To prepare the data, I converted the date column into a datetime format, extracted the year, and grouped the reports by year and state to calculate the number of sightings.

I also added a dropdown menu that allows users to select a specific state or view all states together. This makes the chart more interactive because users can explore how sightings have changed over time in different locations. I think this is useful because it allows people to focus on a particular state instead of having to compare multiple separate charts.

## Data and Analysis

[The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv)

[The Analysis](https://github.com/aidancg2/aidancg2.github.io/blob/main/IS445_Homework_Bigfoot.ipynb)
