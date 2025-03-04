# Guinea-Bissau's latest coup attempt is only one of 10 since 2000

Code for the data journalism project hosted [here](https://tejalwakchoure.github.io/coup/).

## Aim

To trace the history of political unrest in Guinea-Bissau and its effects of the economy. I started digging into this after the attempted assassination of President Umaro Sissoco Embaló in February 2022.

## Findings

1. The most interesting finding was that only one elected president in Guinea-Bissau has ever completed a five-year term in office since its independence in 1974.
2. Out of the two coups that were successful, the one that was welcomed by the public led to an increase in GDP whereas the other led to a drastic drop.


## Data collection process

1. Pulled data from the Cline Center for Advanced Social Research's [Coup D'état Database](https://clinecenter.illinois.edu/project/research-themes/democracy-and-development/coup-detat-project) via the Data Is Plural newsletter.
2. Gathered GDP and military spending data from the [World Bank](https://data.worldbank.org/country/guinea-bissau).
3. Gathered information from local newspapers to contextualize the attempted coups with significant political unrest in the country.

## Data analysis process

1. The Coup D'état Database details all coups globally from 1945, so the dataset itself is large. Sorted all attempted coups by country and year to map how the situation has changed globally.
3. Created unique keys for each coup attempt in Guinea-Bissau based on its outcome (unrealized, realized, resignation, arrest, injury, death) and source (military, dissident, foreign, etc) to filter effectively.
4. Using basic statistics, converted the GDP data to GDP as a percentage change year-over-year. Then compared that with the dates of realizes coups to highlight effects.
5. Made an interactive map for the global coup data using Plotly.
6. Plotted the year-on-year GDP percentage change as a bar chart.
7. Used scrollytelling as a narrative style to interpret the coup numbers with details from local news.

## New skills

1. Creating a choropleth map in Python
2. Scrollytelling in D3.js

## Future improvements and additions

1. Refine responsiveness for the map and the scrollytelling.
2. In December 2023, Embaló dissolved parliament citing allegations of an attempted coup d'état. I'm interested to continue this story during the next presidential elections scheduled for November 2025.
   
