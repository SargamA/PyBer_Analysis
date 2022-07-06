# PyBer_Analysis

## The purpose of this analysis was to review and compare number the fare earned by each city type whithin 4 months period. To gather this information, some data clean up and monipulation was required.  

### First, I had to combine data required for the analysis from 2 different data sources. 
Secondly, I wrote below code to get total fare by city by date.

Pyber_table_df = pd.pivot(data = Pyber_summary2_df, index=["date"], columns ="type", values="fare")
Pyber_table_df

### Adding data to plot by each day will not provide clear over view, so then i grouped the dates into weekly buckets and eventually plotted with monthly intervals.

## Summary Grapy of Total Fares by City Type over 4 months period 
C:\Users\Aaryan\Desktop\Bootcamp\PyBer_Analysis\analysis

### As it is clear from the Chart, overall Urban cities are highest revenue generator with an average of between $1500 and $2500, followed by Suburban and lastly Rural cities with the least revenue.

### Based on above analysis and below summary of data, the recommended stretigic changes that could help the business. 
![Screenshot](PyBer_Analysis_average.png)

#### Increase marketing in the Rural area to attract more customers. 
#### Reallocate drivers from Urban to Rural city type 
#### OR focus on improving business in the 2 steady city types, Suburban and Urban, and shut down service in Rural city. 



