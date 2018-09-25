# Datamine RS Metrics




This project introduces a potential use of RS Metrics "MetalSignals" data.  MetalSignals measures growth in global stockpiles of copper, aluminum, and zinc (finished metals and concentrates) at hundreds of global smelters and storage sites, and generates signals that are highly predictive of exchange price and inventory.

Further Information about RS Metrics and Datamine can be found at CME Group [CME Datamine RS Metrics Data](https://www.cmegroup.com/market-data/rs-metrics.html "CME Datamine RS Metrics Data") and [RS Metrics Information](https://rsmetrics.com/ "RS Metrics Homepage")


## Run on Binder
Automatcially run this in a hosted jupyter notebook with all the dependencies.  
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CMEGroup/datamine-rsmetrics/master)


## To Run This Analysis Locally

To use the examples in juptyer notebook from Anaconda Python.  The following will clone this repo, inlcuding an environment.yml file that will create the proper Anaconda environment with all the dependencies.  You then launch the juptyer lab environment.  

```
git clone https://github.com/CMEGroup/datamine-rsmetrics.git
cd datamine-rsmetrics
conda env create
source activate  datamine-rsmetrics
juptyer notebook


```
Alternatively, you can use your own python environment but review the environment.yml file to determine the package dependencies.

## Notebook Summary

There are a notebook for data introduction and analysis.  The general summary of the notebook is below.

### RSmetrics Blog
[CME Datamine RS Metrics Data Analysis](https://github.com/CMEGroup/datamine-rsmetrics/blob/master/RS%20metrics%20blog/RSmetrics-Blog.ipynb "RS Metrics Analysis")

This analysis introduces RS Metrics data and finds a potential relationship between RS metrics data and CME copper futures data.




## Data Supplied
This workbook leverages altered data in the analysis. It displays the general statistical 
properties of the orignal data set.

## Author
[Seo Wook Jang](https://github.com/sjangcme) - CME Group Global Data Licensing Services

## Questions and Comments?
Please contact markettechsales@cmegroup.com or use the Issues feature.

## Notice
The information herein has been complied by CME Group for general informational and education purposes only and does not constitute trading advice or the solicitation of purchases or sale of futures, options, or swaps. The views in this video reflect solely those of the author and not necessarily those of CME Group or its affiliated institutions. All examples discussed are hypothetical situations, used for explanation purposes only, and should not be considered investment advice of the results of actual market experience. Although every attempt has been made to ensure the accuracy of the information herein, CME Group and its affiliates assume no responsibility for any errors or omissions. All data is sourced by CME Group unless otherwise stated. All matters pertaining to rules and specification herein are made subject to and are superseded by official CME, CBOT, NYMEX, and COMEX rules. Current rules should be consulted in all cases concerning contact specifications.
 
CME Group, the Globe Logo, CME, Globex, E-Mini, CME Direct, CME Datamine and Chicago Mercantile Exchange are trademarks of Chicago Mercantile Exchange Inc.  CBOT is a trademark of the Board of Trade of the City of Chicago, Inc.  NYMEX is a trademark of New York Mercantile Exchange, Inc.  COMEX is a trademark of Commodity Exchange, Inc. All other trademarks are the property of their respective owners.
