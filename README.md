# Future-of-Agriculture
# Introduction 

Agriculture plays a vital role in the survival of the human population and the economic development of countries worldwide. In order to promote agriculture activities globally and ensure that they are sustainable, it is important to identify and address the various economic and non-economic factors that affect agriculture.

One of the key factors that can impact agriculture is the demand for agricultural products. This can include factors such as population growth, dietary preferences, and changes in consumer behavior. By understanding the demand for agricultural products, we can identify opportunities to increase agricultural production and improve the economic viability of the sector.

Another important factor to consider is the economic impact and contributions of agriculture. This includes the value of agricultural exports, the role of the agricultural sector in job creation, and the impact of the sector on rural development. By understanding the economic importance of agriculture, we can prioritize policies and investments that support the sector.

Finally, it is important to consider ways to promote agriculture in a sustainable way. This can include investing in sustainable farming practices, protecting natural resources, and reducing the environmental impact of agricultural activities. By taking a sustainable approach to agriculture, we can ensure that the sector can continue to provide benefits for future generations.

Overall, to increase agricultural activities around the world, we need to consider the demand for agricultural products, the economic impacts and contributions, and the ways to do it in a sustainable way.

# Background

1. Economic growth and population expansion have put tremendous pressure on the agricultural sector to meet expanding industrial and food demands.
2. Modern technology has been widely adopted in recent decades in order to increase productivity and efficiency in agriculture.
3. Intensive agriculture, which includes the use of artificial fertilizers and pesticides, expansion of farmed land, exploitation of natural resources for energy use, and burning of agricultural wastes to clear fields, has been a result of the adoption of modern technology.
4. This intensive agriculture has contributed to several environmental problems.

# Dataset Description

- To help with our analysis we took all the required data from the Food and Agriculture Organization (FAOSTAT). These are the open license datasets that are provided by The United Nations food and agriculture body. The link https://www.fao.org/faostat/en/#data provides a brief overview of all our datasets and their sources along with the relevant background research. It is available under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 IGO license (CC BY-NC-SA 3.0 IGO; https://creativecommons.org/licenses/by-nc-sa/3.0/igo). The size of the data is 383 Mb approximately. 
- Data is semi-structured and its in CSV format.

1. Trade Indices 
- Url of dataset: https://www.fao.org/faostat/en/#data/TI
- The food and agricultural trade dataset is collected, processed and disseminated by FAO according to the standard International Merchandise Trade Statistics (IMTS) Methodology. The trade database includes the following variables: export quantity, export value, import quantity, and import value. The trade database includes all food and agricultural products imported/exported annually by all the countries in the world. 

2. Crops and Livestock Products 
- Url of dataset: https://www.fao.org/faostat/en/#data/QCL
- Crop and livestock statistics are recorded for 278 products, covering the following categories but I'll look for particular crops which would be listed below in following code as a List. Data are expressed in terms of area harvested, production quantity and yield. 

3. Crop Residues
- Url of dataset: https://www.fao.org/faostat/en/#data/GA
- Estimates of nitrous oxide (N2O) emissions from the breakdown of nitrogen in crop residues left on managed soils can be found in the FAOSTAT domain Crop Residues. 
- According to the 2006 IPCC Guidelines for National Greenhouse Gas (GHG) Inventories, estimates are computed at Tier 1. (IPCC, 2006). 
- For the years 1961 through 2020, with annual updates, forecasts for 2030 and 2050, and global coverage, data are provided by nation.

4. Energy Use 
- Url of dataset: https://www.fao.org/faostat/en/#data/GN
- Crop and livestock statistics are recorded for 278 products, covering the following categories but I'll look for particular crops which would be listed below in following code as a List. 
- Data are expressed in terms of area harvested, production quantity and yield.

5. Manure Applied 
- Url of dataset:https://www.fao.org/faostat/en/#data/GU
- Carbon dioxide, methane, and nitrous oxide gases associated with fuel combustion and electricity generation in agricultural make up the greenhouse gas (GHG) emissions from direct on-farm energy use in agriculture (including fisheries). 
- The FAOSTAT emissions database covers the entire world from 1970 to 2020. (with annual updates)

6. Land Use:
- Url of dataset: https://www.fao.org/faostat/en/#data/RL
- Area - The region/country
- Item - Agricultural land is the only category we need in Item
- Year - Timeframe(Years) from 1961 - 2020
- Unit - Unit of crop yield in 1000 ha
- Value - amount of land used for agricultural purpose
- Note - Above mentioned attributes are the ones needed for the analysis.

7. Fertilizer Use: 
- Url of dataset: https://www.fao.org/faostat/en/#data/RFB
- Area - The region/country
- Item - Different types of fertilizers
- Year - Timeframe(Years) from 1961 - 2020
- Unit - Unit of fertilizer import for agricultural use is tonnes
- Value - amount of fertilizer used for agricultural purpose
- Note - Above mentioned attributes are the ones needed for the analysis.

8. Economic Indicator: 
- Url of dataset: https://www.fao.org/faostat/en/#data/MK
- This dataset contains GDP per capita(in US dollars 2015 prices) for different countries from 2000 to 2019
- Share of Agricultural GDP in total GDP of a country from 2000 to 2019

9. Employment Indicator: 
- Url of dataset: https://www.fao.org/faostat/en/#data/OEA
- This dataset contains share of a Share of employment in agriculture, forestry and fishing in total employment of  different countries from 2000 to 2019.
- Second indicator is Agriculture Value added per worker for different countries from 2000 to 2019. This indicator provides information on the output of the agricultural, forestry and fishing sector by worker engaged. It is a measure of agricultural productivity. The data on the value added in agriculture, forestry, and fisheries (in US$, 2015 prices) is extracted from FAOSTAT and then divided by the number of people employed in agriculture,forestry and fishing extracted from ILOSTAT for a given year in a given country. In simple term we can refer this term as a agricultural productivity of a country.
