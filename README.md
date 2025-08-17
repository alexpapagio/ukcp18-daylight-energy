# UKCP18 Daylight Energy

This project explores how **UKCP18 climate projections** can be translated into insights for **building services engineering**, focusing on future daylight availability in the UK and Ireland.

## Overview
- Data: **UKCP18 12km RCM, RCP8.5 scenario**
- Variables: surface solar radiation (rss), cloud cover (clt)
- Tools: `xarray`, `pandas`, `matplotlib`, `cartopy`
- Period: 1980–2080 (decadal trends)

## Key Findings
- Winter daylight energy increases by **≈ +100 Wh/m²/day** between the 2000s and 2080s.
- Cloud cover decreases in winter, consistent with radiation trends.
- Implications:  
  - **Lower lighting energy demand** in winter.  
  - **Higher risk of overheating** in summer due to stronger solar gains.  
  - Highlights the need for **climate-resilient daylighting and shading strategies**.

## Methods
1. Load and preprocess UKCP18 netCDF data.  
2. Convert solar radiation → **daily daylight energy**.  
3. Aggregate into **seasonal and decadal means**.  
4. Visualize as **maps and time series**.  
5. Translate into **building design insights**.

## Example Outputs
- Decadal maps of daylight energy (winter & summer).
- Time series of UK+Ireland mean daylight energy.
- Comparison of radiation and cloud cover trends.

---

