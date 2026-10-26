# Tempe Traffic Crash Dashboard

https://benram3737.shinyapps.io/Tempe_Crash_Dashboard/

This is an interactive dashboard I built in R that maps traffic crash reports in Tempe, AZ. Every crash is plotted on a map and colored by severity, so you can see where crashes happen and which ones caused harm.

- Gray: no injuries
- Blue: at least one injury
- Orange: at least one fatality

Circles get larger as the number of people hurt goes up. Click any crash to see its time, injuries, fatalities and collision type.

## What you can explore

- **Day and Time:** pick days of the week and an hour range.
- **Driver Characteristics:** filter by age, gender and travel mode (driver, cyclist or pedestrian) for both parties in the crash. Summary boxes show the number of crashes, total injuries, total fatalities and the share of crashes that caused harm.
- **Comparisons:** the same filters, with Driver 1 and Driver 2 on side by side maps.
- **Alcohol Use:** crashes where either driver had alcohol in their system, by day and time.
- **Driving Conditions:** filter by weather, lighting and road surface.
- **Data:** a searchable table of the first 100 records, with copy, CSV, PDF and print buttons.

## Built with

R, Shiny, flexdashboard, Leaflet, tidyverse and DT. The data comes from the Tempe traffic accident dataset in the DS4PS Data Science Class repository.

## Run it yourself

1. Open `Tempe_Crash_Dashboard.Rmd` in RStudio.
2. Install the packages listed at the top of the file.
3. Click **Run Document**.
