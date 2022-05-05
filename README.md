# General Reports for Processing SARS-CoV-2 Sequencing Results

These reports can be used to visualize and otherwise understand the final results from SARS-CoV-2 genomic sequencing results.

### Contents

* Data folder:
    * **case_data_mi_state**: contains the data files pulled by **pull_cases_from_michigan_website.R**

##### Assistance Code Files:

* **pull_cases_from_michigan_website.R**: Scrapes the html of the [State of Michigan's COVID-19 Data website](<https://www.michigan.gov/coronavirus/stats>) in order to download the "Cases and Deaths by County by Date
of Onset of Symptoms and Date of Death" data file as a .csv file rather than an .xlsx file.

##### Report Code Files:

* **strain_and_cases_report_code.Rmd**: Using genomic sequencing data of SARS-CoV-2, this code will create a report that contains a bar chart of total samples per week colored by lineage group (i.e. Delta, Omicron, etc.) and an additional bar chart where that same data is translated into the percent of samples each week that were each lineage group type. This report focuses on Public Health Region 2S of Michigan, and also charts the number of reported COVID-19 cases per week in that region as a line over each bar chart. An additional small table is included, looking at the lineage calls of the 50 most recent samples processed. 
