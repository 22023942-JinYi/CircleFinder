# Circle Finder

## Overview  
Circle Finderis a tool designed for the **Quality and Service Department (QSD)** to monitor employee mobile clock-ins at project sites. The application provides **map-based visualizations** using **automated circle generation, Excel data uploads, and interactive filtering** for better workforce tracking.  

## Features  

### Circle Generator  
- Draw a **polygon on the map** to define an area.  
- **Auto-generate circles** to cover the entire land area.  
- **Manually adjust circles** by adding, moving, or deleting them.  
- **Download output files** (Excel & text format) with circle coordinates and details.

### Upload Excel Data  
- **Clock Records Processing**  
  - Reads **latest** employee clock-in records from OneDrive.  
  - Allows **manual upload** of Clock Records if needed.  
  - Filters employees before processing for **faster analysis**.  
  - Configurable **project site radius** (default: **100m**).  
  - Interactive **map visualization** of clock-in locations.  

- **Other Excel Spreadsheets**  
  - Supports custom **Longitude, Latitude, and Radius** data.  
  - Displays **previously generated circles** for reference.  
  - Allows **modification of radius values** after upload.  

### Interactive Map Features  
- **Click on circles or markers** to highlight details in the output box.  
- **Zoom into specific project sites** or **zoom out** for an overview.  
- **Date filtering** for clock-in records.  
- **Downloadable reports** in Excel and text formats.  

## Output Structure  
- **Processed Clock Records** – Shows employees within the specified **radius (Y), near the radius (Y1), or outside (N)**.  
- **Generated Circles** – Provides a structured dataset of circle locations for project sites.  
- **Downloadable Reports** – Includes **Excel (CSV)** and **Text (TXT)** formats for easier review and documentation.  

## Tech Stack  
- **Backend:** Flask (Python)  
- **Frontend:** HTML, JavaScript  
- **Mapping & Geolocation:** Leaflet.js, OpenCV, NumPy, Pandas  
- **Data Processing:** Pandas, Pyproj, OpenPyXL  

## Security Considerations  
Since this application handles **employee tracking data**, it is designed for **local use only**. To maintain privacy, all uploaded files are **automatically cleared** once processing is complete.  

## EXE Application Download
https://github.com/22023942-JinYi/CircleFinder/releases/download/CircleFinder/CircleFinder.exe
