# Exploratory Data Analysis of Electric Vehicle Adoption in the USA

## 📌 Project Overview

This project provides an exploratory data analysis (EDA) of vehicle registration counts by fuel type in order to evaluate state-level EV adoption, benchmark performance against the national average, and identify regions where EV infrastructure investment may be strategically prioritized.

Studying EV adoption rates helps measure progress toward cleaner and more sustainable transportation. As governments and industries work to reduce emissions and reliance on fossil fuels, EV adoption becomes as a key indicator of energy transition. Understanding geographic differences in adoption supports informed infrastructure planning and strategic investment decisions.

## 🎯 Problem Statement

This analysis aims to:

 * Measure EV adoption rates across U.S. states

 * Compare state-level adoption against the national benchmark

 * Identify leading and lagging states

 * Highlight regions where EV infrastructure expansion may be most impactful

 ## 📂 Dataset Description

 The dataset used contains vehicle registration counts for each U.S. state, categorized by fuel type.

Each row represents one state.
Columns represent absolute registration counts for:

 * Electric (EV)
 * Plug-In Hybrid Electric (PHEV)
 * Hybrid Electric (HEV)
 * Biodiesel
 * Ethanol/Flex (E85)
 * Compressed Natural Gas (CNG)
 * Propane
 * Hydrogen
 * Methanol
 * Gasoline
 * Diesel
 * Unknown fuel

 ### Note: The dataset contains absolute counts and does not include a time dimension. The data is synthetic and used for analytical demonstration purposes.

 ## 🛠 Tools Used

 * SQL (MySQL) – Data aggregation, metric computation

 * Excel – Result verification

 * Tableau – Data visualization

## 📊 The Analysis

### State-Level Distribution of EV, PHEV, HEV, and Gasoline Vehicles

#### Key Findings

 * Gasoline vehicles dominate across all states, accounting for over 80% of total registered vehicles.
 * EV adoption rates remain relatively low nationwide, with the highest shares observed in California (3.41%), followed by the District of Columbia (2.60%) and Hawaii (2.37%).
 * The District of Columbia records the highest PHEV (1.19%) and HEV (5.80%) shares, indicating stronger hybrid adoption relative to most states. HEVs demonstrate broader appeal compared to EVs and PHEVs across the majority of states.
 * The lowest EV, PHEV, and HEV adoption rates are observed in states such as North Dakota and Mississippi, highlighting regional disparities in electrification.

 #### Interpretation

 Overall, vehicle registration data suggests that electrification of US vehicles remains in an early adoption phase, with hybrid technologies (PHEV and HEV) acting as a transitional step in many states.

 ### Top and Bottom 5 States by EV Adoption Rate

 ![Top and Bottom 5 States by EV Adoption Rate](Tableau/States%20with%20the%20highest%20EV%20adoption%20rates.png)

 


 

