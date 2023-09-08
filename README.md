# Tableau Challenge

## Background

Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.
<img width="603" alt="Screenshot 2023-09-07 at 11 08 38 PM" src="https://github.com/javsgon/Tableau_Challenge/assets/125521896/b931c170-24a3-4ec6-bf1f-b18d5ee71c26">

## Deployment
Please find below the link to the Tableau dashboard, showcasing the results of the analysis:
https://public.tableau.com/app/profile/javier.saldana1893/viz/CityBikeTableauChallenge/Story1

## Instructions
1. Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

- Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

- Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

- Create one of the following visualizations for city officials:

  - Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

  - Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.


- Create your final presentation:

- Create a Tableau story that brings together the visualizations, requested maps, and dashboards.


## Data Source
The first thing done was to download the monthly CSV files, covering the period from January 2018 to December 2018, from the Citi Bike Data webpage. The data used in this analysis specifically pertains to the New York region.

After that, I created a Jupyter Notebook file, named "citibike.ipynb" in the "Resources Folder", that combines the monthly CSV files into a single CSV file, to import it into Tableau.
