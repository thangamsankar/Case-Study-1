# This repository contains the code for cleanup, analysis and reporting on GDP vs. Income groups information.
# Here are the names of the files and their contents

  Data Import.R   - Contains code for downloading the spreadsheets from web and loading them into R data frames
  
  Data Cleanup.R  - Contains code for cleaning up the data and report on NA data
  
  Data Analysis.R - Merges the data in the 2 spreadsheets and provides the following metrics:
  
                     ID matches 
                     Country with the 13th highest GDP
                     Average GDP rankings for "High income: OECD" and "High income:nonOECD" groups
                     
  Reporting.R     - Contains code for the following reports:
                     GDP value for all the countries and color plots by income group
                     Summary statistics of GDP by income groups
                     GDP ranking into 5 separate quantile groups and report on the countries that are in Lower middle income but among the
                     38 nations with highest GDP
  Case Study1.RMD  - Contains the r-markdown code that invokes all the R scripts above and knits them into a git_hub document
  Case_Study_1.md  - The .md file generated when Case Study 1.RMD is knit
