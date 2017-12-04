# Clipper Transactions Exploration

The purpose of this analysis is to investigate the interaction of Clipper users between transportation operators. By knowing which operators have high user overlap and the ridership patterns of those shared users, policy decisions may be informed. 

## Data Aggregation

The Clipper transactions database contains over 330 million records per year. For the sake of computation time, we used SQL queries to aggregate the data to the appropriate level before any extensive analysis. The SQL queries used for aggregation are documented *here*

## Clipper User Overlap between a Given Operator and Other Operators

This analysis looks which other operators Clipper users tend to use for two specific operators, BART and Muni. Data was aggregated in SQL then pulled into Tableau for an interactive visual representation. This analysis was performed for one month, November 2016 for illustrative purposes. 

### How to read the chart

The black line represents the total Clipper users for each operator for a November 2016. The blue bar represents the proportion of riders shared by the given operators of interest--for the first screenshot below, BART, and for the second screenshot, Muni. The darker the blue, the higher percentage of overlap with other operators. 


**insert screenshot with BART dropdown selected here**

**insert screenshot with Muni dropdown selected here**



