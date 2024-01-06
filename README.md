# Happiness-Scores-Python-Analysis

**Purpose:**
This Python script extracts and analyzes data from the World Happiness Report 2020, focusing on happiness scores and associated factors. The script fetches information from a Wikipedia page, performs basic operations, and creates visualizations.

**Dependencies:**
pandas: Data manipulation library
requests: HTTP library for making requests
bs4 (Beautiful Soup): HTML parsing library
matplotlib: Plotting library
plotly: Interactive plotting library
google.colab: Colab-specific library for file handling

**Steps:
Data Retrieval:**
The script sends an HTTP request to the Wikipedia page World_Happiness_Report and parses the HTML using BeautifulSoup.

**Table Extraction:**
The happiness score and related details for the year 2020 are extracted from the second table with the class 'wikitable sortable'.

**Data Presentation:**
The script prints and saves the primary dataframe as a CSV file ('dataframe.csv').
The top 10 happiest countries are extracted, presented, and saved as a separate CSV file ('top10_happiest_countries.csv').

**Basic Operations on the First Table:**
Basic statistical operations (sum, max, mean, median, mode) are performed on the 'Score' column of the primary dataframe.
The correlation matrix between different variables is calculated.

**Graph Generation - Happiness Score Distribution:**
A bar graph is created to visualize the happiness scores of different countries for the year 2020.
The graph is saved as 'graph2-1.png' and can be downloaded.

**Graph Generation - Correlation Plot:**
A correlation plot is generated to show the correlation between happiness factors.
The graph is saved as 'graph2-2.png' and can be downloaded.

**Usage:**
Run the script in a Colab environment.
View and download the CSV files for the primary dataframe and the top 10 happiest countries.
Examine and download the first graph ('graph2-1.png') displaying the happiness score distribution.
Examine and download the second graph ('graph2-2.png') illustrating the correlation plot.
