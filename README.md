# Nigeria-SocioEconomic-Analysis
Evaluating the Impact of Nigeria’s Structural Economy on Human Development (2017–2025)


<img src="Images/Nigeria%20SocioEconomic%20Analysis%20(Page1).png" width="700">

## Summary

This project evaluates the structural health of the Nigerian economy and the effects of recent macroeconomic gains on the average Nigerian. 
The dashboard analyzes the intersection of human capital (education and healthcare), infrastructure, and macro-economic stability.

## Project Workflow

Step 1: Data Acquisition: Sourced multi-sectoral data from the NBS, WHO, and the World Bank to create a holistic view of the Nigerian economy.
(Download the datasets from the files uploaded)

Step 2: Data Cleaning & Transformation: Data was extracted from the earlier stated sources and cross-referenced to ensure metric alignment based on matching timelines, then consolidated into a unified master dataset in Excel before staging into Power Query.

Step 3: Modeling & DAX: Developed a custom DAX measure to handle the Electricity Access chart visuals and ensure it remained dynamic.

<details>
<summary><b>Click to view the Electricity Gap DAX measure</b></summary>

<br>

Electricity Gap = 100 - MAX(Nigeria_Development_Indicators_[Electricity Access(%)])

</details>

Step 4: Visualization: Applied a customized Nigeria-centric palette (#008751 for Green, #605E5C for medium-dark Grey) and the Nigerian flag as a background to increase aesthetic appeal. 

## Key Insights

- The huge dip in the unemployment rates (2022), resulted from a change in the unemployment measurement method by NBS to match the new global International Labour Organisation (ILO) guidelines. After 2023, the numbers show a continuous downward trend in both Youth and Total Unemployment.

- The 38.8% electricity gap represents about 86 million Nigerians without access to power. However, even those with electricity access, do not enjoy stable and consistent electricity supply.

- The data shows that ~ 63% of our adults are literate, yet the majority remain in the informal sector, showing that literacy alone is not sufficient to create a productive and industrialized economy, as many of the formal sources of employment (e.g. banking, telecommunication, technology) lack the capacity to absorbed the vast size of the unemployed population.

- The UHC index of 48 shows and 0.45 doctor to patient ratio shows that even if people are educated, they are physically vulnerable, which will affect overall productivity.

- The Inflation and poverty rate in Nigeria show a highly positive relation. With increasing prices, the volume of goods an amount of money can buy is consistently reducing, further expanding lack and want.

## Recommendations

