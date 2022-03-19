# **How does population density, fossil fuel consumption, Renewable Energy Consumption impact on greenhouse gas emission?** 

*Abdul Salam Kagaji*

*Data Science Master's Student, UMBC*

*March 19, 2022*

Global population growth leads to overpopulation, causing scarcity of natural resources of the Earth. Population is growth is influenced by multiple factors like evolved health care, better and safe urban infrastructures. It makes life unsustainable in areas with dense populations.
Advanced innovations in the fields of science and health care have made life on Earth long-lasting. Despite these phenomenal results, it has also led to overpopulation which in turn affects the consumption of natural resources for energy generation. Modern innovations ranging from automobiles to semiconductor devices demand energy sources in form of electricity or fuels. 

Fossil fuels are the most prominent natural resources for the production of energy. Increasing populations require higher production of energy for everyday activities and this demands consumption of fossil fuels like coal and crude oil. Despite the production of hydroelectricity, the majority proportion of energy generated is from fossil fuels. 
Continued usage of energy and electronic devices have affected carbon emission leading to the greenhouse effect on Earth. Greenhouse gases cause global warming which disrupts the environmental conditions creating chaos that could lead to devastating situations.

Lets analyze the effects of overpopulation, fossil fuel consumption, renewable energy consumption on greenhouse gas emissions with the data from the time period of 2010 to 2021.

## Approach

**a.	Source of data & graphs:** THE WORLD DEVELOPMENT EXPLORER (https://www.worlddev.xyz/) 

**b.	Regions Compared:** East Asia & Pacific, Europe & central Asia, Latin America & Caribbean, Middle East & North Africa, North America, South Asia, Sub-Saharan Africa.

**c.	Timeline :** 2010 to 2021

**d.	Topics and Indicators:**

-	**Urban Development** : Population density (people per sq. km of land area)
- **Energy & Mining** : Renewable energy consumption (% of total final energy consumption)
- **Energy & Mining** : Fossil fuel energy consumption (% of total)
- **Climate Change** : Total greenhouse gas emissions (kt of CO2 equivalent)

## Visual Analysis:

### Population distribution among regions:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/population_distribution.png)

- From the distribution graph it is clearly seen that the population density of East Asia & Pacific region is the highest as compared to other western regions like North America and middle East & North Africa region, followed by Europe & central Asia with second highest population density.
- Sub-Saharan Africa is the region with least population density.


### Population Change between 2010 and 2021:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/pop_change_timeseries.png)

- The time series graph shows a gradual increase in population densities in all the regions with time and it is also seen that North America has a decrease in population density, whereas all the other regions has an incremental change.

### Fossil Fuel Consumption by region:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/fossilfuel_consuption_pie.png)

- The above pie chart shows that the Middle East & North Africa has the highest fossil fuel consumption recorded with a total of 20.3% followed by North America, and Sub-Saharan Africa has the least fossil fuel consumption of 6.89%.

### Renewable Energy Consumption by region:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/renewable_energy_consumption_pie.png)

- In contrast to the fossil fuel consumption graph, Sub-Saharan Africa has the highest renewable energy consumption when compared to all the other regions with a total of 34.4% and Middle East & North Africa has the least renewable Energy Consumption records

### Greenhouse Gas Emission by region:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/greenHouse_gas_emission_pie.png)

- A surprisingly high contribution towards greenhouse gas emission is seen by the North America with a total of 72.6% which is almost the 3/4th part of the total greenhousegas emission.

### Relation between population density,fossil fuel consumption and greenhouse gas emission:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/pop_vs_fossilfuel_vs_greenhousegas.png)

- The graph shows how fossil fuel consumption directly impacts the emission of greenhouse gases despite population density. 
- North America, despite its low population density has a very high volume of greenhouse gas emission. And East Asia & pacific with comparably less greenhouse gas emission even with highest population density.


### Relation between population density, renewable energy consumption and greenhouse gas emission
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/pop_vs_renewabeenergy_vs_greenhousegas.png)

- The graph shows how renewable energy consumption directly impacts the emission of greenhouse gases despite population density. 
- North America, despite its low population density has a very high volume of greenhouse gas emission due to its very less consumption of renewable energy sources. And Sub-Saharan Africa with comparably less greenhouse gas emission even with highest population density due to its highest usage of renewable resources.


### Change in Fossil fuel consumption, renewable energy consumption and greenhouse gas emission with time:
Fossil fuel consumption | Renewable energy consumption 
:-------------------------:|:-------------------------:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/fossil_fuel_consumption_timeseries.png) | ![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/renewable_energy%20_consumption_timeseries.png) 

- The above time series graphs show the trends of consumption of fossil fuels and renewable energy during 2010 and 2021

####  Greenhouse gas emission
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/green_house_gas_emission_timeseries.png)

- The above time series graph shows the trends of greenhouse gas emission during 2010 and 2021, North America could be seen at the top of the plot with the highest gasses emission rates. 
In a nutshell the graph shows a increase in greenhouse gasses emission with time.


## Regression Analysis

### Impact of fossil fuel consumption on greenhouse gas emission:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/fossil_fuel_consumpiton_vs_greenhousegas_emission_regression.png)
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/regression_analysis_fossilfuel_consumption_vs_greenhousegas.jpg)

- The regression graph clearly shows a upward trend indicating to the point that usage of fossil fuels leads to increase in emission of greenhouse gasses.

### Impact of renewable energy consumption on greenhouse gas emission:
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/renewable_energy_vs_greenhousegas_regression.png)
![](https://github.com/abdulSalamKagaji97/world_development_explorer/blob/main/charts/regression_analysis_renewable_energy_vs_greenhousegas.jpg)

- The regression graph clearly shows a downward trend indicating to the point that usage of renewable energy resources leads to a decrease in emission of greenhouse gasses.

## Observations 

- It can be observed that as time passes the population density increases
- As population density increases the emission of greenhouse gasses increases
- Consumption of fossil fuels affects the emission of greenhouse gasses by increasing its rates.
- Consumption of renewable energy affects the emission of greenhouse gasses by decreasion its rates.
- Emission of greenhouse gasses increases with increase in nation's land size and is slightly affected by the populatio density.


## Conclusion

Although it is inevitably true that it is not possible to determine 100% facts from just few indicators like population, consumption of fossil fuels and consumption of renewable energy to declare them as the sole contributors to the increase in greenhouse gasses as many other factors like current environmental situaltions, climatic conditions could also be the reasons.


