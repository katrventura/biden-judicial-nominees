# Judicial Nominees Map: Biden Administration (District Courts)
This project features an interactive map displaying the judicial nominees appointed by President Joe Biden for various district courts. The data was scraped from press releases on the White House website utilizing BeautifulSoup and regex techniques. The map visualization is created using geojson.

## Project Overview

## Data Collection
- The initial step involved visiting the White House website to gather press releases concerning Biden's judicial nominees.
- Utilizing BeautifulSoup and regex, the website was scraped to compile a comprehensive list of judicial nominees across different states, including non-U.S. jurisdictions like Puerto Rico.
- Due to variations in press release formats, regular adjustments to the regex patterns were necessary to accurately extract the nominee data.

## Visualization
- A federal courts geojson map template was selected to visualize the collected data.
- The color purple was chosen to represent female nominees, reflecting the project's initial focus on mapping out the female nominees of the Biden administration.

## Deployment
- A separate repository was created to host the interactive map on GitHub Pages, ensuring accessibility and ease of use for users.

## Usage
- Explore the interactive map to view the geographic distribution of judicial nominees appointed by President Biden across various district courts.
- Click on individual regions to access detailed information about the nominees appointed for each district.

## Dependencies
- BeautifulSoup: Python library for web scraping.
- Regex: Regular expression module in Python for pattern matching.
- Geojson: A format for encoding a variety of geographic data structures.
