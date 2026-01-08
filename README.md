# Chicago Building Permit Explorer

This web application allows users to search historical building permit records from the City of Chicago. It connects directly to the Chicago Data Portal to retrieve information about construction projects, contractors, and permit costs.

## Purpose

The tool helps residents, researchers, and professionals find building permits associated with specific companies or individuals. It searches across 15 different contact fields in the city database to identify relevant records.

## Features

* **Search by Name**: Find permits by entering the name of a contractor, architect, or business entity.
* **Live Data**: Connects to the City of Chicago API to provide current information.
* **Detailed Records**: Displays permit IDs, issue dates, work descriptions, and reported costs.
* **Map Integration**: Includes links to view project locations on Google Maps.
* **Data Export**: Allows users to download search results as a CSV file for use in spreadsheet software.

## Technical Details

The application is a single-page tool built with HTML, CSS, and JavaScript. It does not require a backend server because it communicates directly with the Chicago Data Portal using the Socrata Query Language (SoQL).

### Data Source

The data comes from the [Chicago Data Portal - Building Permits dataset](https://www.google.com/search?q=https://data.cityofchicago.org/resource/ydr8-5enu.json). This dataset contains permits issued from 2006 to the present.
