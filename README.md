IDEAL Study and Health Report

Purpose
You use this project to generate a static HTML report from livestock and public health data. The report replaces an interactive Shiny app with a single shareable HTML file.

What the report shows
• Monthly calf births and deaths
• Linear regression for growth rate
• Logistic regression for mortality risk
• Data table preview
• County-level pregnancy map for Kenya

Files required
• ANALYSIS.Rmd
• ideal3a.csv
• table6_teenpregnancybycounty.csv
• shapefiles folder
• County.shp
• County.dbf
• County.shx
• County.prj

Folder setup
Place ANALYSIS.Rmd in the same folder as the CSV files.
Keep the shapefiles inside a subfolder named shapefiles.

Required R packages
• tidyverse
• sf
• leaflet
• plotly
• DT
• lubridate
• broom
• rmarkdown
• knitr

Install missing packages once using RStudio.

How to generate the HTML report

Open ANALYSIS.Rmd in RStudio

Click Knit

Select HTML

Wait for the report to finish rendering

RStudio creates an HTML file in the same folder.

How to save the HTML elsewhere

After knitting, open the preview window

Click File

Click Save As

Choose a folder and filename

How to open the HTML
• Double-click the file in File Explorer
• Or open a browser and press Ctrl + O

No R or RStudio needed for viewing.

Common issues
File not found error
• Confirm CSV and shapefiles exist in the expected folders
• Confirm filenames match exactly

Map not showing
• Confirm all shapefile components exist
• Confirm county names align across datasets

Output type
This report is static.
Filters and buttons from the Shiny app do not apply.

Contact
Use this README together with the report when sharing with reviewers or stakeholders.
