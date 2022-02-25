The dataset consists of 140 unweighted undirected networks. 

Each network represents a country: its nodes are 21 variables related to sustainability, climate change, economic indicators and production 
(downloaded from the FAOSTAT database).
An edge between any two variables (nodes) means that the corresponding variables are highly (positively or negatively) correlated.

The networks have been generated as follows: 
- For each contry, consider 21 time series of the variables from 1990 to 2019. 
- Detrend the time series to avoid autocorrelation.
- Compute correlation matrix for each country. 
- Tranform each correlation matrix into an adjacency matrix: whenever the correlation between two variables,
 in its absolute value, is higher than a threshold (0.7), then an edge will link the two nodes. 
 So the generic element a_{ij} is 1 if variables i and j are highly correlated, 0 otherwise.

The variables taken into account are:
- CH4_LULUCF: total emissions of methane (CH4), measured in kilotonnes, from Land Use, Land Use Change and Forestry. 
- CH4_AFOLU:  total emissions of methane (CH4), measured in kilotonnes, from Agriculture, Forestry, and Other Land Use.
- CH4_Emission on agricultural land: total emissions of methane (CH4), measured in kilotonnes, from Agriculture.
- CH4_Farm-gate emissions: Farm-gate total emissions of methane (CH4), measured in kilotonnes.
- CH4_Land Use change: total emissions of methane (CH4), measured in kilotonnes, from Land use change.
- CO2_LULUCF: total emissions of carbon dioxide (CO2), measured in kilotonnes, from Land Use, Land Use Change and Forestry 
- CO2_AFOLU:  total emissions of carbon dioxide (CO2), measured in kilotonnes, from Agriculture, Forestry, and Other Land Use.
- CO2_Emission on agricultural land: total emissions of carbon dioxide (CO2), measured in kilotonnes, from Agriculture.
- CO2_Farm-gate emissions: Farm-gate total emissions of carbon dioxide (CO2), measured in kilotonnes.
- CO2_Land Use change: total emissions of carbon dioxide (CO2), measured in kilotonnes, from Land use change.
- N2O_LULUCF: total emissions of nitrous oxide (N2O),measured in kilotonnes, from Land Use, Land Use Change and Forestry.
- N2O_AFOLU:  total emissions of nitrous oxide (N2O), measured in kilotonnes, from Agriculture, Forestry, and Other Land Use.
- N2O_Emission on agricultural land: total emissions of nitrous oxide (N2O), measured in kilotonnes, from Agriculture.
- N2O_Farm-gate emissions: Farm-gate total emissions of nitrous oxide (N2O), measured in kilotonnes.
- N2O_Land Use change: total emissions of nitrous oxide (N2O), measured in kilotonnes, from Land use change.
- Agriculture: Gross per capita Production Index Number (2014-2016 = 100) for agricultural products.                     
- Livestock: Gross per capita Production Index Number (2014-2016 = 100) for livestock.    
- Vegetables and Fruit Primary: Gross per capita Production Index Number (2014-2016 = 100) for vegetables and fruit.    
- Gross Domestic Product: gross domestic product (in value US$ per capita, 2015 prices).
- Agricultural land: share of the agricultural land in land area (%).
- Temperature change: increment of temperature (measured in °C) in the meteorological year w.r.t the previous year.

