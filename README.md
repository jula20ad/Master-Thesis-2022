# Master-Thesis-2022
Master Thesis - Do stricter capital requirements raise the cost of capital of banks

The code for Rebecca Schwartz and Julie Laustsens' master thesis for the MSc in Finance and Investment at Copenhagen Business School.

The data and analysis is divided into 18 files, 4 excel and 14 jupyter notebooks. In every notebook a path is set in the begining of the file.

__________________________________
Excel file: 'Eikon_data_to_python' contains cleaned data from 1999-2021 on the 226 European banks. 

Excel file: 'euribor-ready_to_python' contains the 1 month EURIBOR rate excressed in monthly rate from 1999-2021. The EURIBOR rate is used as the risk free rate in the analysis.

Excel file: 'market data to python' contains the monthly prices on MSCI Europe Investable Market Index from 1999 to 2021. 

Excel file: 'Country dist' containts a list with 226 banks and their belonging country. 

Jupyter notebook: 'Load of data_GitHub' contains further data cleaning, return and ratio calculations, and outlier treatment. Additionally, a banks affiliation country is connected to the data (link between data Eikon_data_to_python & Country dist.) 

Jupyter notebook: 'Descriptive_stat_GitHub' contains descriptiv statistics of the data overall and on country level. Additionally, a equal- and value-weighted portfolio is constructed with all banks and the distribution of excess return is examined. Dependencies to file 'Load of data_GitHub'.

Jupyter notebook: 'Descriptive stat(beta sorted)' contains descriptiv statistics on data sorted into three groups (30%,40%,30%) according to backward beta. Additional analysis of the distribution of average Tier 1 ratio and average book equity ratio is performed. Dependencies to file 'Load of data_GitHub'.

Jupyter notebook: 'Deposits analysis' contains a calculation of deposit ratios for all banks. Banks are then sorted in to 10 groups according to backward beta and a tabel with average disposit ratios are displayed. Dependencies to file 'Load of data_GitHub' and 'Low risk anomaly_use'.
