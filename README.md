# AstroChart_Analysis
*[click to run the code from Google Colaboratory](https://colab.research.google.com/github/catch-twenty2/AstroChart_Analysis/blob/main/AstroChart_Analysis.ipynb)

## Overview
AstroChart Analysis is a tool for generating and interpreting natal and relocation astrological charts using the Swiss Ephemeris library. This tool allows users to input their birth details and current location to produce detailed astrological insights for a specific target date.

## Getting Started

### Prerequisites
Before you start, make sure you have the following Python packages installed:
- `swisseph`
- `ipywidgets`
- `IPython`

### Input Your Details:

* Enter your name.

* Enter your birth date, birth time, and birth location (latitude and longitude).

* Enter your current location (latitude and longitude).

* Enter the target date for the relocation chart.

### Obtaining Latitude and Longitude from Google Maps
1. Open Google Maps.
2. Find the location for which you need the latitude and longitude.
3. Right-click on the location on the map.
4. Select "What's here?" from the context menu.
5. A box will appear at the bottom of the screen with the coordinates (latitude, longitude).

### Requesting prompt for analysis:
1. Calculate Charts: Click the "Calculate Charts" button to generate the natal and relocation charts.
2. Interpretation Prompt: The script will generate a detailed context for ChatGPT to provide a professional astrological interpretation of the data.
3. Paste the output to ChatGPT

### Example

After filling in the details and clicking the button, you will see an output similar to this:

```
PROMPT FOR ChatGPT
========================
Dear ChatGPT, I have gathered detailed astrological data for a person, including both their natal chart and a relocation chart for a specific target date. I would like a professional astrological interpretation of this data. Below is the information provided:

Context:
Name: Neo
Birth Date and Time: 2003-04-29, 12:00
Birth Location: Lat: 52.52, Lon: 13.40
Current Location: Lat: 52.52, Lon: 13.40
Target Date: 2024-09-01

Please provide a professional interpretation of this data, focusing on the following aspects:

... (natal chart data) ...

... (relocation chart data) ...

Natal Chart Interpretation: Explain the inherent personality traits, life patterns, and potential challenges based on the natal chart data.
Relocation Chart Interpretation: Describe how the individual might experience life in the new location at the specified target date, highlighting any significant changes or continuities from the natal chart.
Aspect Analysis: Provide insights into the key themes and dynamics in the person's life as indicated by the aspects in both charts.
Overall Comparison: Summarize how the energies and influences in the natal chart compare to those in the relocation chart, and what this might mean for the individual's experiences and opportunities during the target period.

Suggest to user any followup questions dealing with challenges, and suggestions for how to bridge the gap in problematic issues.
Thank you!
```


### Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

### License
This project is licensed under the MIT License.

Happy charting!
