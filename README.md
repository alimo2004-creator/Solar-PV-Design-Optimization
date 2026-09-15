# 🌞 Commercial Solar PV System Optimization

## Project Overview
This repository contains the design, simulation, and hardware configuration for a 30.09 kWp grid-tied/hybrid Solar PV system. The project focuses on maximizing energy yield through meticulous 3D spatial modeling, string-level shading analysis, and precise inverter matching.

## 🏗️ 3D Modeling & Shading Analysis
*   **Site Modeling:** A complete 3D representation of the installation site was constructed to simulate exact solar azimuth and elevation impacts throughout the year.
*   **Shading Mitigation:** Conducted a comprehensive heat-map shading analysis across all mounting surfaces. Panels exceeding optimal shading thresholds were systematically removed from the array to prevent string-level current degradation.
*   **Array Layout:** Final layout consists of 177 high-efficiency modules strategically placed to avoid roof obstacles and parapet shadows.

## 🔌 Electrical Configuration & Inverter Sizing
*   **Inverter Selection:** SMA Sunny Tripower Hybrid X 25.
*   **Sizing Factor:** Achieved a highly efficient 120.36% sizing ratio.
*   **String Architecture:** 
    *   MPP 1 & 2: 3 x 17 modules
    *   MPP 3: 3 x 13 modules
    *   MPP 4: 2 x 18 modules
*   **AC Cabling:** Detailed multi-string connectivity diagrams generated for safe and compliant grid feed-in at 220V (cos φ = 1).

## 🔋 Hardware & BESS Considerations
*   **Alternative Inverter Evaluation:** Specs evaluated for the Victron Energy MultiPlus-II 48/10000/140-100 (230V) for robust off-grid and battery integration.
*   **BESS Safety Systems:** System design considerations include Balance of Plant (BOP) compliance, specifically NFPA 855 fire safety, early off-gas detection (H2/CO), and Novec 1230 clean agent suppression for integrated battery storage.

## 📁 Repository Contents
*   `/Schematics`: AC cable diagrams and inverter connection topologies.
*   `/Simulations`: 3D building models and shading percentage heat-maps.
*   `/Hardware_Specs`: Datasheets for evaluated inverters and PV modules.
