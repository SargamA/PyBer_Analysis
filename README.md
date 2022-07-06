# PyBer_Analysis

## The purpose of this analysis was to review and compare number the fare earned by each city type whithin 4 months period. To gather this information, some data clean up and monipulation was required.  

### First, I had to combine data required for the analysis from 2 different data sources. 
Secondly, I wrote below code to get total fare by city by date.

Pyber_table_df = pd.pivot(data = Pyber_summary2_df, index=["date"], columns ="type", values="fare")
Pyber_table_df

### Adding data to plot by each day will not provide clear over view, so then i grouped the dates into weekly buckets and eventually plotted with monthly intervals.

## Summary Grapy of Total Fares by City Type over 4 months period 
![PyBer_fare_summary](https://user-images.githubusercontent.com/102809106/177460543-93f6247b-88cf-483e-bacd-11f16f754c49.png)

### As it is clear from the Chart, overall Urban cities are highest revenue generator with an average of between $1500 and $2500, followed by Suburban and lastly Rural cities with the least revenue.

### Based on above analysis and below summary of data, the recommended stretigic changes that could help the business. 
![PyBer_Analysis_average](https://user-images.githubusercontent.com/102809106/177460651-fc6707ba-a3f2-4ad2-a659-8fc99df31c8b.png)

#### Increase marketing in the Rural area to attract more customers. 
#### Reallocate drivers from Urban to Rural city type 
#### OR focus on improving business in the 2 steady city types, Suburban and Urban, and shut down service in Rural city. 



