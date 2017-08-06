# ACLUProject
Eli Saracino (esaracin@bu.edu) and Kylie Moses (kylietmo@bu.edu)

This directory contains each of the IPython notebooks used to collection, manipulate,
and visualize our data analysis for the project. The 'datasets' subdirectory
contains each of the datasets used by our notebooks, including any modifications made through
our work (i.e. webscraping, joining, etc.). Below are brief descriptions of each of these files.


Linear-Analysis-FIOs.ipynb:
	Contains the data manipulation and visualization used to compute the linear regression
	results explained in the Final Report

FIO_Clustering.ipynb:
	Contains the data manipulation, visualization, and several types of clustering to compute
	the clusters described in the Final Report

Crime-Incident-Reports.ipynb:
	Contains our preliminary analysis of the Crime Incident dataset, but also includes
	some comparisons with the FIO dataset through 2012-2015 as well.

Census_Data.ipynb:
	Contains the Pie charts used to convey racial compositions within Boston neighborhoods.

FIO-Data-Analysis:
	Contains the data manipulation and visualization for our preliminary analysis of the FIO
	dataset, as well as some brief comparisons with the Crime-Incident Dataset, and statistics
	regarding each.

FIO_Location_Scraper.ipynb:
	Contains the script used to scrape the web for latitude and longitude information
	relevant to the FIO datasets.

Maps.ipynb:
	Contains the code that computed the Graphs of crimes in the Boston Area.

GoogleMapper.ipynb:
	Contains a class used to create map objects-- extremely helpful for ease of plotting.

datasets/bpd-field-interrogation-and-observations-reports.csv:
	Contains the main FIO dataset used, containing FIOs reported by the BPD between 2012 and
	June 2015. Webscraping provied the lat/long attributes seen.

datasets/crime_incident-reports-2012-2015.csv:
	Contains the main Crime dataset used, containing crimes reports by the BPD between 2012 and 
	2015.

datasets/stop_and_frisk.csv:
	Contains a supplementary dataset provided by the ACLU of comprehensive
	FIO reports throughout 2015. The two csvs provided have been joined on the FC_NUM field.

datasets/FIO_data.csv:
	A version of the 'bpd-field...' dataset in which we have web scraped for latitude and
	longitude information.

