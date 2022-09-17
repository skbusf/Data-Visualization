# **Exploratory Analysis of Automotive Industry in terms of CO2 Emissions**

#### **Summary:**
This analysis is inteded to study the contribution of the Automotive sector to the global Greeen Gouse Gas emissions in particular CO2 as it is the major cause for Global Warming. Data was sourced from various credible sources and Tableau and Tableau Prep Builder were used for this study. 

#### **Introduction:**

Global Warming and Climate change are 2 key phenomena the world is challenging now. Behind these phenomena lies the increase in greenhouse gases in our atmosphere. A greenhouse gas is any gaseous compound in the atmosphere that is capable of absorbing infrared radiation thereby holding the heat in the atmosphere. By increasing the heat in the atmosphere greenhouse gases are responsible for the greenhouse effect leading to global warming i.e., increasing the amount of heat in the atmosphere.

The major greenhouse gases are Carbon Dioxide (CO2), Methane (CH4), Nitrous Oxide (N2O), and Fluorinated Gases. Carbon Dioxide is the most significant contributor with almost 79% of the greenhouse gases.

Carbon Dioxide enters the atmosphere through the burning of fossil fuels like coal and natural gas, biological materials, trees, solid waste, and chemical reactions, like in the production of cement. Electricity generation and Transportation contribute most to carbon dioxide emissions which is the reason I chose transportation for this study to find how modes of transportation, passenger vehicles, in particular, are contributing to the carbon dioxide emissions.

In this study, I want to broadly answer if the auto industry is moving towards a better future in terms of CO2 emissions by answering the research questions below.

Research Questions:

1. What is the contribution of the auto industry to CO2 emissions?
2. How are manufacturers and vehicle types performing in terms of emissions?
3. How are alternate fuel vehicles like a hybrid, plugin hybrid, and electric vehicle sales and their impact on CO2 emissions?

#### **Methodology:**

The datasets were sourced from

- [https://www.epa.gov/](https://www.epa.gov/)
- [https://www.bea.gov/](https://www.bea.gov/)
- [https://ourworldindata.org/](https://ourworldindata.org/)

I didn't have to do a major cleanup of the data as most of the datasets were in ready-to-use form, but I used tableau prep builder for fixing the null values, adding new meaningful columns to create a link between the datasets and pivot function of the Tableau as well. A part of the analysis is made for the data between the years 2000-2020 and another for 1975 to 2020. All the links between datasets are for the years column. Briefly, the analysis follows the pattern of Why the transportation sector is chosen, drilling down to the US as it is the second largest contributor of greenhouse gases, why passenger vehicles, emissions by manufacturers, and vehicle types.

#### **Analysis:**

1. Greenhouse Gas Emissions by country

![Emissions by Country](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/EmissionsByCountry.png)

- We see that the United States and China are the 2 major contributors to greenhouse gas emissions in the world accounting for 11.6% (5771 MTCO2e) and 24.3% (12055 MTCO2e) of the total emissions respectively.
- Due to the unavailability of credible data for other countries this analysis is focused on the United States only.
<br>
<br>
2. Global Green House Gas Emissions in percentage by Sector and Subsector

![Emissions by Sector](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/EmissionsBySector.png)

- From the above visualization it is evident that Energy Sector is the major contributor to global greenhouse gas emissions with a 73.2% contribution.
- Under the energy sector Transportation is a significant contributor with 16.2% of greenhouse gas emissions emitted by the energy sector which is the sector in focus for this study.
<br>
<br>
3. Category-wise Contribution to Transportation Sector in the United States

![Emissions by Transportation Sector](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/EmissionsByTransportationSector.png)

- For the year 2019 Vehicles have contributed to 75% of emissions in the transportation sector.
- As the United States is a car cultured country for means of travel it is justifiable that 75% of the emissions are contributed by vehicles.
- This study focuses on Vehicular emissions specifically CO2.
<br>
<br>
4. Green House Gas Emissions of United States from 2000-2019

![Emissions by Year](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/EmissionsByYear.gif)

- From the animation above it is evident that the greenhouse gas emissions of the United States are slightly on a downtrend.
- Let us explore further to see what the contribution of the passenger vehicles to this trend is.
<br>
<br>
5. CO2 Emissions by Manufacturers

![Emissions by Manufacturers](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/EmissionsByManufacturers.png)

- CO2 emissions have decreased over the years for every manufacturer of vehicles.
- Stellantis has shown the least improvement whereas Mazda significantly decreased their emissions of CO2 in grams per mile traveled
- All the native American manufacturers (Stellantis, Ford, and GM) comparatively have the highest emissions probably because they sell more heavy vehicles like pickup trucks.
- Honda is the only manufacturer that has remained consistently low in emissions with Stellantis being the least performer lately.
<br>
<br>
6. Miles Per Gallon (MPG) by Manufacturers

![MPG by Manufacturers](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/MPGByManufacturers.png)

- Miles Per Gallon is increasing over the years for each manufacturer's vehicles.
- Again, Honda is the best in MPG and Stellantis the least among all the manufacturers for the year 2020.
<br>
<br>
7. Change of Weight and Horsepower of the vehicles for all the manufacturers

![Weight and HP by Manufacturers](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/WeightAndHPByManufacturer.png)

- Interestingly the average horsepower and average weight of the vehicles for all the manufacturers have increased over the years.
- Although weight and horsepower have increased, MPG has increased and CO2 Emissions have come down. Probable reasons for this strange pattern are the transition from 2-stroke to 4-stroke engines, and an increase in the sales of Electric, Plugin-Hybrid Electric, and Hybrid Vehicles to name a few.
- We will explore this further below.
<br>
<br>
8. Dashboard for Parameters by Vehicle Type

![Dashboard by Vehicle Type](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/DashboardByVehicleType.png)

From the dashboard, we can infer the following

- CO2 Emissions and MPG by vehicle types show a positive sign as CO2 emissions are decreasing and MPG is steadily going up.
- Pickup Vehicles and sedans have the highest and lowest CO2 emissions and vice versa for MPG respectively.
- Production share synonymous with sales is steadily increasing for pickups and has surpassed sedans in the year 2020.
<br>
<br>
9. Sales of Electric, Plug-in Hybrid, Hybrid, and Passenger Cars

![Sales of Alternate Energy Vehicles](https://github.com/skbusf/Data-Visualization-Automotive-Industry/blob/main/Images/SalesOfVehicleTypes.png)

- Since 2011, their inception year, Electric vehicle sales are growing significantly.
- Plugin Hybrid and Hybrid Electric vehicles sales are growing as well whereas from 2015 passenger vehicle sales are almost constant implying the alternate energy vehicle share is increasing in the passenger vehicle segment.
<br>
<br>
#### **Conclusion:**

The following conclusions are made from the analysis

- Transportation sector is a major contributor to CO2 Emissions, passenger vehicles, in particular, contribute the most.
- Manufacturers and Vehicle types are moving towards a better future in terms of CO2 emissions and MPG, but the sales of vehicles play a substantial role i.e., if more vehicles are sold and driven then the benefits that are caused by improving emission rates and mpg will subside.
- As Pickup vehicles have fared lower in comparison with sedans for MPG and CO2 Emissions the matter of concern is the steady increase of the share of pickup trucks and overtaking Sedans in the year 2020.
- Sales of electric vehicles, hybrids, and plugin hybrids are increasing substantially but what about the source of electricity for those vehicles? Is it through the burning of Fossil fuels or Renewable energy?
- Although the sales of electric vehicles are increasing, are electric vehicles contributing to the decrease in CO2 emissions in the United States? This is to be studied.

Electric vehicles have given a greater hope for the transportation sector to reduce emissions since their inception in 2011 as they produce no CO2 emissions. Accelerating Electrification and boosting energy efficiency are critical near-term strategies to stem transport emissions in the hope of a better tomorrow.