# Mars Data Analysis

## Overview

This project involves scraping and analyzing data related to Mars, including temperature and atmospheric pressure. The data is collected from various sources and analyzed to answer specific questions about Mars.

## Data Collection and Analysis

### Part 1: Scrape Titles and Preview Text from Mars News

- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).

- The titles and preview text of the news articles were scraped and extracted.

- The scraped information was stored in a Python list of dictionaries, where each dictionary has two keys: 'title' and 'preview'.

### Part 2: Scrape and Analyze Mars Weather Data

- Automated browsing (with Splinter) was used to visit the Mars Temperature Data Site.

- The HTML table on the website was extracted using Beautiful Soup.

- The data from the table was cleaned and assembled into a Pandas DataFrame.

- The data types of the columns were examined and adjusted as needed.

- The dataset was analyzed to answer specific questions about Mars weather.

### Questions Answered

1. **How many months exist on Mars?** There are a total of 12 months on Mars.

2. **How many Martian (and not Earth) days' worth of data exist in the scraped dataset?** There are 1867 Martian days' worth of data in the dataset.

3. **Which month, on average, has the lowest temperature? The highest?** The month with the lowest average temperature is month 3, with an average low temperature of -83.3°C. The month with the highest average temperature is month 8, with an average low temperature of -68.3°C.

5. **Which month, on average, has the lowest atmospheric pressure? The highest?** The month with the lowest average atmospheric pressure is month 6, with an average pressure of 745.05. The month with the highest average atmospheric pressure is month 9, with an average pressure of 913.31.

6. **About how many terrestrial (Earth) days exist in a Martian year?** There are approximately 705.8 terrestrial days in a Martian year.

## Data Export

The final analyzed dataset is exported to a CSV file named "mars_weather_data.csv" for future reference and sharing.

## Technologies Used

- Python
- Jupyter Notebook
- Beautiful Soup
- Splinter
- Pandas
- Matplotlib
