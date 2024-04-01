## Project Overview
This project is a web application with Python backend that visualizes your Google location history. It displays a timeline of your location data and showcases a heatmap of your activity.
- **Backend Development:**
  - Utilized REST APIs and Python libraries including Flask, Shapely, and Pandas for backend development, 
  dynamic data processing, and efficient routing.

- **Frontend Design:**
  - Designed the dynamic website using Figma to create an intuitive and visually appealing user interface.
  - Employed templating techniques for dynamic functionality, HTML, CSS and javascript for interactive elements.

- **Mapping Integration:**
  - Integrated Leaflet, an open-source mapping library, to embed interactive maps seamlessly into the application.
  - Utilized GeoJSON data to display location history and heatmap layers on the map.
![](demo.gif)

## How to run

1. Install all Python dependencies. I.e ```pip install -r requirements.txt```.
2. Download your Location History data from [Google Takeout](https://takeout.google.com/settings/takeout).
3. Save ```LocationHistory.json``` in the ```location``` folder.
4. From the input folder, run ```python sample_location.py```. This matches points to countries and
samples the data to reduce the file size. This may take a few minutes.
5. From the root folder, run ```python app.py```.

## Frameworks and Libraries

You need the following framework and libraries:

- **Framework**: ![Flask](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- **Python Libraries**:
  - Pandas
  - Shapely
- **Frontend**:
  - ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square)

