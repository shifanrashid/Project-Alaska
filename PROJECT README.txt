A. Power Output Test
Connect the prototype to a generator and a power monitoring system. Simulate different tidal flow speeds and measure voltage, current, and power output.
Expected Data: 
Voltage (V), current (A), and power (W) at different water velocities.
Analysis: Compare results to target power generation benchmarks to ensure the design meets the required energy production levels.

Need to gather: Power Output of similar underwater Turbines at certain velocities



B. Cost Efficiency Evaluation
Track material and production costs. Calculate cost per kWh of energy generated.
Expected Data: 
Total cost of prototype development. Estimated cost per kWh based on test results.
Analysis: Compare projected electricity costs with current diesel-based costs to evaluate economic viability.

Need to gather: Production cost and Material cost of similar underwater Turbines


MeyGen Project (Scotland): This project features four 1.5 MW turbines. 
These turbines reach their rated power output at a current speed of 3 m/s. 
Source: Wikipedia, The Cool down

21,024,000 kWh/year per 4 turbine
5,256,000 kWh/year per turbine
Cost per turbine: $16 million


SeaGen Turbine (Northern Ireland): SeaGen turbine has a capacity of 1.2 MW. 
Source: Wikipedia, Data.gov

3,994,000 kWh/year per turbine
Cost per turbine: $24 million

ORPC's TidGen® Power System (USA): Deployed in Cobscook Bay, Maine, a single TidGen system is rated at 80 kW of output at a water velocity of 2.25 m/s, with a peak output of 160 kW at 3.5 m/s.

350,400 kWh/year per turbine
Cost per turbine: Unknown Not publicly disclosed, but industry estimates suggest $1–2 million based on similar tech







C. Diesel Fuel Replacement
We are not going to fully replace diesel fuel. But we plan to cut off a significant chunk. After this, we will have to calculate how much money we are saving by the replaced electricity. We need to figure out how much Savoonga currently spends on Diesel fuel. 

Diesel Fuel Consumption: Approximately 261,967 gallons for electricity generation.​
Source: PublicNow

Power Generated: 3,327,000 kWh
Diesel Fuel Cost: The total expenditure on diesel fuel was about $1,227,700.​
Cost per kWh: 0.37$ 
Average Price per Gallon: The average cost was approximately $4.69 per gallon. 


to Cut off 20% of diesel fuel usage we need to generate: 665400 kWh 
Cost for this by diesel:
Cost for this with Turbines:
to Cut off 30% of diesel fuel usage we need to generate: 998100 kWh
Cost for this by diesel:
Cost for this with Turbines:




How the Python Data Visualization Program will work:

will take a xlsx file that has V, A, and water velocity through test data and will calculate generated power in a year
will compare our turbine in graphs with other tidal turbines (market standards)
will ask how much diesel fuel we want to cut off
will output default cost estimates from the number of turbines required
will give current budget vs new budget (after turbine installation) in another generated graph


input V, A -> Apply formula -> Output P in year > Graph it next to other P 



