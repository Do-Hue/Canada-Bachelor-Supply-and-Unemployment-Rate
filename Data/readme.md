Labour Force Survey Data

Overview
This analysis uses Statistics Canada's Labour Force Survey (LFS) public-use microdata file (PUMF) from 2006 to 2025. The data is not included in this repository due to size constraints and licensing requirements.

Data Source
Provider: Statistics Canada
Dataset: Labour Force Survey (LFS) Public Use Microdata File (PUMF)
Link: Statistics Canada - Labour Force Survey
How to Obtain the Data

Either: 
Visit Statistics Canada
Go to https://www.statcan.gc.ca/
Search for "Labour Force Survey" or navigate to their microdata download section
Download the PUMF
Create an account or log in
Download the Labour Force Survey PUMF for the period 2006-2025
The file will be provided in CSV format

Or:
Download the EVERMD.csv file through this link: https://www.dropbox.com/scl/fo/b4ygmw9g4i9oeffip6p2u/AHR8NIvVRTxaswzE_hWk0Ys?rlkey=oeow30u6l02akphlxim7nl5lq&st=oc8vz4uj&dl=0
Save it to this directory: Data/EVERMD.csv
Ensure the filename matches exactly

File Requirements
Filename: EVERMD.csv (must be exact)
Location: Data/ folder in the project root
Format: CSV (comma-separated values)
Expected Size: ~2.7 GB

Usage
Once the file is in place, the R analysis script (Codes/E5029_Research_Codes.Rmd) will automatically:
Load the data from Data/EVERMD.csv
Process and analyze the Labour Force Survey data
Generate results and visualizations

Licensing & Attribution
Data is subject to Statistics Canada's licensing terms
You must comply with Statistics Canada's data usage agreement
Do not redistribute the raw data without permission
Always cite Statistics Canada as the source

Questions?
For questions about data access or licensing:
Contact Statistics Canada directly
Review their data documentation
Check the terms of use on their website

Running the Analysis
After placing EVERMD.csv in this directory, run:
# In RStudio
rmarkdown::render("Codes/E5029_Research_Codes.Rmd")

The analysis will produce:
Descriptive statistics
Model results (linear probability, probit, panel regression)
Visualizations of findings
All outputs saved to results/ folder
