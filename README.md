# US Flight Delays Analysis Dashboard

## Dashboard Link

Explore the dashboard [here](https://andrea-cas.github.io/tableau-dashboards/).

## Project Description

This project analyzes flight delays in the United States for 2023, using data from multiple sources. The aim is to visualize and understand patterns in flight delays, cancellations, and their geographical distribution through an interactive Tableau dashboard.

## Data sources

The data used in this project comes from three sources:

- `Airlines.xlsx`: Contains information about delays and flight cancellations for each airline.
- `Delay_Type.csv`: Provides information about the types of delays.
- `Airports`: Includes information about delays for cities and airports.

You can find these datasets in the `data` directory of this repository.

## Visualizations

- **Bar Chart: Total Flight Delay Time by Airline** - This chart shows the total delay time in minutes for each airline, showing worst performances first.
- **Highlight Table: Weekly Flight Cancellations by Airline** - A heatmap that indicates the number of cancelled flights for each airline on different days, making it easy to spot patterns.
- **Treemap: Total Flight Delay Time by Airline** - Visualizes the total delay time in minutes for each airline, with larger sections representing higher total delays.
- **Area Chart: Total Delay Time by Type** - Shows the distribution of different types of delays (weather, departure, arrival, etc.) over the year 2023.
- **Dual-Axis Map: Arrival Delays by City and Airports** - Combines a Choropleth map and Density map to display geographical areas and specific airports with the highest total delay times.

## Usage

You can interact with the visualizations and explore the data in depth:

1. Open the [dashboard link](https://andrea-cas.github.io/tableau-dashboards/) provided in this README file.
2. Interact with the visualizations:
   - **Hover** over different charts to see full detailed information.
   - **Map Interaction**: You can zoom in, zoom out, and search for and select specific geographical locations on the map for more granular details.
