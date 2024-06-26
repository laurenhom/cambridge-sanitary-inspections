# Cambridge Sanitary Inspections
Created: March 2024

ETL and EDA process for analyzing sanitary inspection data from Cambridge Open Data. At the time of this project, data from May 12, 2021 to March 19, 2024 with violations occurring between September 23, 2021 to March 1, 2024.

This project is based on the [Cambridge Open Data Program Civic Innovation Challenge Inventory](https://data.cambridgema.gov/General-Government/Civic-Innovation-Challenge-Inventory/x96z-hdnh/about_data). Data comes from the [Sanitary Inspections dataset](https://data.cambridgema.gov/Inspectional-Services/Sanitary-Inspections/ryb9-qzmw/about_data) and the question to be answered based on the dataset is: 

<blockquote>
How can Cambridge better utilize and present this data to protect public health and safety and improve community access to inspection information?
</blockquote>

Each row in the dataset is an inspection result. This exploratory data analysis (EDA) is in preparation with building a [Tableau dashboard](https://public.tableau.com/views/CambridgeSanitaryInspections2021-2024/CambridgeSanitaryInspections2021-2024?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link) to address this question. 

The project is not intended to ridicule or diminish any particular establishment, but rather to educate the City of Cambridge and its residents. For more information on sanitary codes, see food sanitary codes for Massachusetts: [105 CMR 590.00: State sanitary code chapter X: Minimum sanitation standards for food establishments)
](https://www.mass.gov/doc/merged-food-code-111618/download). Neighborhoods in Tableau Dashboard comee from the [Cambridge Neighborhoods spatial files](https://data.cambridgema.gov/Geographic-Information-GIS-/Cambridge-Neighborhood-Polygons/k3pi-9823/about_data) on the Cambridge Open Data site.

## Repository Files:
1. [Cambridge Sanitary Inspections Project.ipynb]([Cambridge Sanitary Inspections Project.ipynb](https://github.com/laurenhom/cambridge-sanitary-inspections/blob/main/Cambridge%20Sanitary%20Inspections%20Project.ipynb)) — Jupyter notebook containing ETL and EDA
2. [Sanitary_Inspections_20240324.csv](Sanitary_Inspections_20240324.csv) — Sanitary Inspections dataset downloaded from [Cambridge Open Data Sanitary Inspections site](https://data.cambridgema.gov/Inspectional-Services/Sanitary-Inspections/ryb9-qzmw/about_data), used for Tableau dashboard
3. [Cambridge_Neighborhood_Polygons_20240324.csv](Cambridge_Neighborhood_Polygons_20240324.csv) — Polygon files of Cambridge neighborhoods from [Cambridge Open Data Cambridge Neighborhood Polygons site](https://data.cambridgema.gov/Inspectional-Services/Sanitary-Inspections/ryb9-qzmw/about_data) used to create Tableau Dashboard

## Tableau Dashboard Link: 
[Cambridge Sanitary Inspections Tableau Dashboard](https://public.tableau.com/shared/6PPXQ4573?:display_count=n&:origin=viz_share_link)
