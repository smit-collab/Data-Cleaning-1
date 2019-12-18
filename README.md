## Data-Cleaning-1

## Dependencies
 pandas 
 numpy 
 
 
## Introduction
Data cleaning is the most important step in the preparation of the data.
It removes major errors and inconsistencies that are inevitable when multiple sources of data are getting pulled into one dataset.
Incorrect or inconsistent data leads to false conclusions. So cleaning the data properly is important.
So we take a file that has not been cleaned name property data in CSV format.

## Observations : 
1. There are many missing values in the CSV file.
2. We use Pandas to recognize the missing values.
3. we can see that only capital NAN are considered as missing values and others were not considered.
4. So we create a manual list of missing values having ["n/a","na","--"].
5. now all missing values are recognized
6. In the end, we print the summary of a number of missing values in the file.




