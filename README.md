# Alteryx-COVID-Extraction
Alteryx COVID 19 Extractor Workflow

Johns Hopkins University has been uploading Worldwide COVID Figures CSV files daily. 
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data  

The data from the files will be loaded from GIT, blended and extracted to Excel, QVX and Tableau Extracts. The Workflow file that extracts the data from the URL and the Macro File that does the pre-processing of data has been attached.

The COVID Extractor Worklfow uses the URL for the first uploaded file in the JHU Repository, and downloads the rest of them till n-1 date. 

THE COVID Tracker Macro loads all the downloaded files, handles the data type issues, field lables, addition of calculated fields and null/missing value handling. Since, this is a macro it can be used in the COVID Extractor Workflow directly to get the output in your required format. 

The extracted QVX file and the QVW in which it has been loaded have been attached as reference. 
