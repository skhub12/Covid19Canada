# Epidemiological Data from the COVID-19 Outbreak in Canada
The **COVID-19 Canada Open Data Working Group** is collecting publicly available information on confirmed and presumptive positive cases during the ongoing COVID-19 outbreak in Canada. Data are entered in a spreadsheet with each line representing a unique case, including age, sex, health region location, and history of travel where available. Sources are included as a reference for each entry. All data are exclusively collected from publicly available sources including government reports and news media. We aim to continue making updates daily. 


# Acknowledgements
We want to thank all individuals and organizations across Canada who have been willing and able to report data in as open and timely a manner as possible. 

Please see below for a recommended citation of this dataset. A number of individuals have contributed to the specific data added here and their names and details are listed below, as well as in the contributors tab of the spreadsheet. 


# Citation
Berry I, Soucy J-PR, Tuite A, Fisman D. Open access epidemiologic data and an interactive dashboard to monitor the COVID-19 outbreak in Canada. CMAJ. 2020 Apr 14;192(15):E420. doi: https://doi.org/10.1503/cmaj.75262


# Datasets
The line list of cases is posted and updated at:
https://docs.google.com/spreadsheets/d/1D6okqtBS3S2NRC7GFVHzaZ67DuTw7LX49-fqSLwJyeo/edit?usp=sharing ([direct download link](https://docs.google.com/spreadsheets/d/1D6okqtBS3S2NRC7GFVHzaZ67DuTw7LX49-fqSLwJyeo/export?format=xlsx)).

The full data may be downloaded in a machine-readable format directly from this repository.

### Individual-level Data
* **Codebook**: codebook.csv
* **Cases**: cases.csv
* **Mortality**: mortality.csv
* **Date and time of update**: update_time.txt

### Health Region-level Time Series
* **Daily and cumulative cases**: timeseries_hr/cases_timeseries_hr.csv
* **Daily and cumulative mortality**: timeseries_hr/mortality_timeseries_hr.csv

### Province-level Time Series
* **Daily and cumulative cases**: timeseries_prov/cases_timeseries_prov.csv
* **Daily and cumulative mortality**: timeseries_prov/mortality_timeseries_prov.csv
* **Daily and cumulative recovered**: timeseries_prov/recovered_timeseries_prov.csv
* **Daily and cumulative testing**: timeseries_prov/testing_timeseries_prov.csv
* **Current and change in active cases**: timeseries_prov/active_timeseries_prov.csv

### Canada-level Time Series
* **Daily and cumulative cases**: timeseries_canada/cases_timeseries_canada.csv
* **Daily and cumulative mortality**: timeseries_canada/mortality_timeseries_canada.csv
* **Daily and cumulative recovered**: timeseries_canada/recovered_timeseries_canada.csv
* **Daily and cumulative testing**: timeseries_canada/testing_timeseries_canada.csv
* **Current and change in active cases**: timeseries_canada/active_timeseries_canada.csv

### Other Files
* **Correspondence between health region names used in our dataset and HRUID values given in Esri Canada's [health region map](https://resources-covid19canada.hub.arcgis.com/datasets/regionalhealthboundaries-1), with [2018 population values](https://www150.statcan.gc.ca/t1/tbl1/en/cv.action?pid=1710013401)**: other/hr_map.csv

# Dashboard
We have also created an interactive dashboard for up-to-date visual analytics and epidemiological analyses. 

This is available for public use at: https://art-bd.shinyapps.io/covid19canada/


# Specific Contributors
Name | Role | Organization | Email | Twitter
--- | --- | --- | --- | ---
Isha Berry | Founder | University of Toronto  | isha.berry@mail.utoronto.ca | @ishaberry2
Jean-Paul R. Soucy | Founder | University of Toronto | jeanpaul.soucy@mail.utoronto.ca | @JPSoucy
Meghan O'Neill | Data Lead | University of Toronto | meghan.oneill@utoronto.ca |@_MeghanONeill
Shelby Sturrock | Data Lead | University of Toronto | shelby.sturrock@mail.utoronto.ca| @shelbysturrock
James E. Wright | Data Lead | SickKids | jamese.wright@sickkids.ca | @JWright159
Kamal Acharya | Contributor | University of Guelph | acharyak@uoguelph.ca | @Kamalraj_ach
Gabrielle Brankston | Contributor |  University of Guelph | brankstg@uoguelph.ca | @GBrankston
Vinyas Harish | Contributor |  University of Toronto | v.harish@mail.utoronto.ca | @VinyasHarish
Kathy Kornas | Contributor | University of Toronto  | kathy.kornas@utoronto.ca | 
Thivya Naganathan | Contributor |  University of Guelph |tnaganat@uoguelph.ca |
Lindsay Obress | Contributor |  University of Guelph | lobress@uoguelph.ca |
Tanya Rossi | Contributor |  University of Guelph | rossit@uoguelph.ca | @DrTanyaRossi
Alison Simmons | Contributor | University of Toronto | alison.simmons@mail.utoronto.ca | @alisonesimmons
Matthew Van Camp | Contributor |  University of Guelph | vancampm@uoguelph.ca | 
Wendy Xie | Contributor |  University of Guelph | xxie03@uoguelph.ca | @XiaotingXie

