This analysis was done for the paper Applications of GIS (ENVSCI801) at Auckland Unviversity of Technology (AUT) in Semester 1 2024.
# Auckland Solar Potential Analysis
New Zealand is a country that primarily uses renewable sources most of its electricity and aims to be 100% renewable by 2030 (MBIE, 2023). Fitting solar panels to roofs on a large scale could potentially greatly support this goal. This report determines roofs areas that are valid for solar panel placement and further identifies the top 30% of buildings based on solar potential in the target areas3.

## Introduction
The target areas identified for this project are the Auckland Airport Industrial zone, Manukau, East Tāmaki, and Ōtāhuhu. Figure 1 shows the chosen priority areas along with the polygon feature class containing the footprints of the buildings taken from Land Information New Zealand (LINZ) aerial imagery in and around the areas.

![Map showing the target areas with building footprints overlaid.](figures-report/priorityareas-nbkgd.png)

The amount of solar radiation an area receives is subject to great variability through not only each day but annually and seasonally. In order to determine the amount of radiation the combined effects of direct, reflected and diffuse radiation needs to be calculated for each area and over the entire time period (ESRI, 2024). Ideal panel locations can be further narrowed down by choosing roofs that face up (low slope) and/or face north, as New Zealand is in the southern hemisphere this is the direction of most solar radiation (Khanna, 2024).

## Methodology
The criteria used for the analysis is outlined in Table 1 and Table 2, while the datasets used is shown in Table 3.

