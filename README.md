# NYISO Fuel Mix Analysis (2023 - 2025)

This project provides an interactive exploratory data analysis (EDA) and visualization suite for the **New York Independent System Operator (NYISO)** fuel mix and generation patterns from 2023 through 2025.

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset Description](#-dataset-description)
- [Key Questions Addressed](#-key-questions-addressed)
- [Visualizations Included](#-visualizations-included)
- [Setup & Requirements](#-setup--requirements)

---

## 🔍 Project Overview
Understanding the electrical grid's fuel mix is critical for assessing carbon intensity, grid reliability, and the progress of renewable energy integration. Using historical monthly generation data, this notebook processes, cleans, and visualizes NYISO's energy generation profile in terms of both absolute generation (Terawatt-hours, TWh) and relative percentage shares.

## 📊 Dataset Description
The primary dataset (`nyiso_fuel_mix_monthly_2023_2025.csv`) includes monthly generation metrics (MWh) categorized across key fuel sources:

*   **Fossil Fuels:**
    *   `natural_gas_mwh`: Traditional natural gas plants.
    *   `dual_fuel_mwh`: Generation capable of burning multiple fuels (primarily gas and oil).
    *   `other_fossil_mwh`: Residual fossil-fuel combustion sources.
*   **Zero-Emission & Carbon-Free:**
    *   `nuclear_mwh`: Nuclear power facilities.
    *   `hydro_mwh`: Hydroelectric generation.
*   **Renewables:**
    *   `wind_mwh`: Utility-scale wind turbines.
    *   `other_renewables_mwh`: Biomass, solar, and other miscellaneous clean energy resources.
*   **Aggregates:**
    *   `total_mwh`: Monthly sum total of all grid generation.

## 💡 Key Questions Addressed
1. What is the overall share of each energy resource over the analyzed period?
2. How does the fuel mix fluctuate seasonally or month-to-month to meet heating and cooling demands?
3. How are clean energy and carbon-free sources (Nuclear, Hydro, Wind, Renewables) tracking year-over-year compared to fossil sources?

## 📈 Visualizations Included
This notebook generates several high-quality static and interactive plots:

1.  **Overall Pie Chart Share:** A clean visual breakdown of the full 3-year aggregate fuel mix percentages.
2.  **Interactive Monthly Stacked Bar Chart:** A dropdown-controlled visualization allowing toggles between total output in **TWh** and **% Share** across the 36-month timeline.
3.  **Interactive Yearly Stacked Bar Chart:** An aggregated annual comparison chart detailing transition trends between 2023, 2024, and 2025 with on-bar text labels.

Presentation and Website: [Link](https://www.figma.com/make/Xd47oD8Kmbr2TP1qB0sVOL/Energy-Mix-Use-Case?code-node-id=0-6&p=f&t=WDEIXrmIhY5Ixrcf-0&fullscreen=1&preview-route=%2F%3Fpresentation%3D1)
