# Master-Thesis-2022
Master Thesis - Do stricter capital requirements raise the cost of capital of banks

The code for Rebecca Schwartz and Julie Laustsens' master thesis for the MSc in Finance and Investment at Copenhagen Business School.

The analysis is divided into 14 jupyter notebooks. In every notebook a path is set in the begining of the file.

__________________________________
Jupyter notebook: 'Load of data_GitHub' contains further data cleaning, return and ratio calculations, and outlier treatment. Additionally, a banks affiliation country is connected to the data.

Jupyter notebook: 'Descriptive_stat_GitHub' contains descriptiv statistics of the data overall and on country level. Additionally, a equal- and value-weighted portfolio is constructed with all banks and the distribution of excess return is examined. Dependencies to file 'Load of data_GitHub'.

Jupyter notebook: 'Descriptive stat(beta sorted)' contains descriptiv statistics on data sorted into three groups (30%,40%,30%) according to backward beta. Additional analysis of the distribution of average Tier 1 ratio and average book equity ratio is performed. Dependencies to file 'Load of data_GitHub'.

Jupyter notebook: 'Deposits analysis' contains a calculation of deposit ratios for all banks. Banks are then sorted in to 10 groups according to backward beta and a tabel with average disposit ratios are displayed. Dependencies to file 'Load of data_GitHub' and 'Low risk anomaly_use'.

Jupyter notebook: 'Capital ratio analysis' contains a analysis of the correlation between Tier 1 ratio and book equity ratio. Dependencies to file 'Load of data_GitHub'

Jupyter notebook: 'Low risk anomaly_use' contains a calculation of backward and forward betas. Banks are then sorted into three groups (30%,40%,30%) according to betas (both backward and forward) and then a value- and equal-weighted portfolio is created in each group. To examine the low risk anomaly, then backward betas and alphas are estimated for the backward sorted portfolios. This gives 6 pairs of alpha and betas that an extra linear regression is performed to determine the strenght of the low risk anomaly. Dependencies to file 'Load of data_GitHub'

Jupyter notebook: 'Low risk anomaly - reduced time period' contains the same as file 'Low risk anomaly_use', however the data is reduced to end in 2011. Dependencies to file 'Load of data_GitHub' and 'Low risk anomaly_use'. 

Jupyter notebook: 'Low risk anomaly_use10port' contains the same as file 'Low risk anomaly_use', however banks are sorted into 10 equal sized groups instead of 3. Dependencies to file 'Load of data_GitHub'.

Jupyter notebook: 'Low risk anomaly_useNoCrisis' contains the same as file 'Low risk anomaly_use', however data from Januar 2007 to February 2009 is removed. Dependencies to file 'Load of data_GitHub'.

Jupyter notebook: 'BW Step 1 - Regression backward beta' contains calculations of inverse tier 1 ratio and inverse tier 1/RWA ratio along with linare and kernel regression of backward beta on inverse tier 1 ratio. The linear regression is also performed for a shorted data sample with ending in 2011. Dependencies to file 'Load of data_GitHub' and 'Low risk anomaly_use'. 

Jupyter notebook: 'BW Step 1 - Regression forward beta' contains calculations of inverse tier 1 ratio and inverse tier 1/RWA ratio along with linare and kernel regression of forward beta on inverse tier 1 ratio. The linear regression is also performed for a shorted data sample with ending in 2011. Additionally, a theroretic graph of the expected relationship between equity beta and leverage is constructed. Dependencies to file 'Load of data_GitHub' and 'Low risk anomaly_use'. 

Jupyter notebook: 'BW Step 1 - Kernel large banks forward beta' contains linear and kernal regression of forward betas on inverse tier 1 ratio for large banks. Large banks are define as banks with a market value above 1 billion €. Dependencies to file 'Load of data_GitHub' and 'Low risk anomaly_use'. 

Jupyter notebook: 'BW Step 1 - tabel - backward beta' contains 3 sorting of banks according to Book equity ratio, Tier 1 ratio, and Tier 1 ratio/RWA ratio. Within each sorting 10 equal-sized deciles are determine. In each decile a value- and equal-weighted portfolio is calculated. Then the backward beta is regressed and reported for each portfolio along with the average capital ratio. Last a piecewise regression is performed on backward beta and inverse tier 1 ratio. Dependencies to file 'Load of data_GitHub'.

Jupyter notebook: 'BW Step 1 - tabel - forward beta' contains calculation of the forward beta for each portfolio in each decile that are calculated in the file 'BW Step 1 - tabel - backward beta'. Both average capital ratio and forward beta is reported. A piecewise  regression is performed on forward beta and inverse tier 1 ratio. Dependencies to file 'Load of data_GitHub' and 'BW Step 1 - tabel - backward beta'.
