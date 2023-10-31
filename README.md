
# Supply Chain Optimization Using Python

This project focuses on optimizing the supply chain operations by considering two types of plants, one with low capacity and another with high capacity, located across five different countries. The objective is to build a linear programming model to minimize the total cost of satisfying consumer demand in all these countries while adhering to various constraints. Additionally, the project incorporates data visualization and interactive widgets to facilitate the comparison of different scenarios.


## Assumptions for Additional Data:
Storage Costs: Storage costs are calculated as 10% of the fixed costs per year. To obtain the daily storage cost per unit, 10% of the monthly fixed costs are divided by 30.

CO2 Emissions: CO2 emissions from shipping are calculated based on the assumption that cargo ships run on diesel. It's estimated that 1 liter of diesel emits 2640g of CO2. The CO2 emissions for each shipment are computed by multiplying the distance between the country ports by a factor of 10.82. This factor is derived from the average mileage of a cargo ship (576 miles per gallon) and represents the CO2 emissions in grams per ton weight per kilometer.

Shipping Mode: The project assumes that shipping occurs exclusively through sea freight. The selected ports for shipping are:

Port of New York (USA)
Port of Hamburg (Germany)
Port of Tokyo (Japan)
Port of Santos (Brazil)
Port of Mumbai (India)
Delivery Lead Time: A standard delivery lead time of 3 days is assumed for shipments within the same country. For international shipments, the delivery lead time is determined based on the average time it takes to travel from one of the above ports to the destination country, with an additional 3 days for inland transportation within the destination country.

This project aims to provide a comprehensive supply chain optimization solution, taking into account not only cost considerations but also environmental impact and practical shipping logistics.

