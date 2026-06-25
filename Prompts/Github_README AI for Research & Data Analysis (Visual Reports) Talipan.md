### Data Analytics & Visual Report

#### Dataset Focus: Davao Region Renewable Energy Output Index (Mock CSV Analysis)

#### 1. Data Cleaning Protocol Log
- **Raw Input Problem:** The CSV file contained multiple missing row cells for Solar and Hydro output across several years, along with mixed numerical formatting styles (e.g., MW vs. kW).
- **AI Cleaning Instruction:** `"Scan this dataset. Identify all null rows in the Output column and replace them with the median value for that specific Province-Source group. Convert all mass metrics to standard Megawatts (MW). Output the first 5 rows of the cleaned table."`
- **Result:** Successfully normalized 30 row inputs across three provincial clusters.

#### 2. Visualizations Generated
*(Embedded High-Contrast Bar Chart showing Solar vs. Hydro Output Divergence from 2019-2023)*


[Image Matrix: 2019-2023 Davao Region Solar Output Growth Chart]


#### 3. Human Analytical Narrative (The 'Why' Factor)
"The bar chart clearly shows hydro output declining from 76 MW to 61 MW, while solar output nearly quadrupled in the same period. While the automated AI analysis summary attributed this purely to increased solar installations, human cross-referencing of local weather advisories reveals this period matched a severe regional El Niño dry spell affecting dam inflow.

This drop emphasizes the urgent need for NEDA and local LGUs to invest heavily in hybrid grid resilience infrastruct
