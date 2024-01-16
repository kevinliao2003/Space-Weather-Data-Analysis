# Solar Flare Data Analysis

## Overview
This Python script is designed to scrape solar flare data from Space Weather Live and NASA websites, perform data preparation, conduct analysis, and generate visualizations.

## Requirements
- Python 3.x
- Required Python libraries: requests, BeautifulSoup, pandas, matplotlib, numpy

## Usage
1. Clone the repository or download the script.
2. Install the required libraries using the following command:

```bash
pip install requests beautifulsoup4 pandas matplotlib numpy
```

```python
3. Run the script using a Python interpreter.

## Data Scraping and Preparation
- The script utilizes web scraping techniques to extract solar flare data from Space Weather Live and NASA websites.
- The data is then cleaned, organized, and transformed into a structured format suitable for analysis.

## Analysis
### Replication
- Identifies the top 50 solar flares based on the X-class classification from NASA data.
- Sorts and selects the top 50 solar flares.

### Integration
- Matches the top 50 solar flares from NASA with the corresponding entries in Space Weather Live data.
- Creates a new column indicating the rank of each flare in Space Weather Live.

### Plotting
- Generates a plot of starting frequencies for the top 50 solar flares over time.

## Conclusion
- The analysis suggests that there is no clear correlation between the start datetime and start frequency of solar flares.
- Outliers observed in the 2000 to 2008 range may influence the skewness of the data.

## Note
- Ensure compliance with the terms of use of the websites from which the data is scraped.

## Author
Kevin Liao

Feel free to modify the README to better suit your project and provide additional details if needed.
```