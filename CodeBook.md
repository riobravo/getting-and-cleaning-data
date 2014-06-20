**Getting and Cleaning Data Project**

* The function run.analysis() description:

1) reads train and test data sets and merges them

2) processes the merged data set (extract the relevant variables, adds descriptive activity names, etc.)

3) writes the merged data set to rawdata.csv

4) generates the tidy data set

5) writes the tidy data set to tidydata.csv

6) returns the tidy data set

If you have the project data available in the current directory, just run:

source('./run_analysis.R')

run.analysis() # invoke the actual function

Otherwise, you can use download.data() function provided in the script. The function will download the data archive and extract it. After that you can run run.analysis(). The full code:

source('./run_analysis.R')

download.data() # download samsung data and unzip it

run.analysis() # invoke the actual function

If you don't want to use download.data(), you should download the data manually, unzip it in the current directory and then run:

source('./run_analysis.R')

run.analysis() # invoke the actual function