# OH-Deer

## Project Overview

This project explores the ecology, expansion, and impact of the six deer species currently found in the UK using machine learning and spatial analysis.  
It begins with a core modelling task: **spatiotemporal forecasting of deer distribution**, built from NBN Atlas occurrence data combined with environmental layers such as land cover, elevation, NDVI, and human population density.

The expansion model forms the foundation for several applied analyses:

- **Species Expansion & Invasion Forecasting**  
  Modelling historical spread and predicting future distribution for all six deer species.

- **Road-Collision Risk Modelling**  
  Using predicted deer density, road networks, and traffic data to identify high‑risk collision zones.

- **Woodland Damage & Regeneration Risk**  
  Assessing where high deer density threatens woodland recovery and biodiversity.

- **Agricultural Impact Modelling**  
  Predicting crop damage risk based on deer presence, crop type, and seasonal movement.

- **Predator Reintroduction Scenario Modelling**  
  Simulating how lynx or wolf reintroduction could influence deer populations and human–wildlife conflict.

- **Multi‑Species Niche Comparison**  
  Comparing habitat preferences, niche overlap, and competitive dynamics among native and introduced deer species.



## Data Sources

This project uses species occurrence data downloaded from the **NBN Atlas** (https://nbnatlas.org/).  
All deer datasets were obtained through the NBN Occurrence Explorer by searching for each species individually:

- *Cervus elaphus* (Red Deer)  
- *Capreolus capreolus* (Roe Deer)  
- *Dama dama* (Fallow Deer)  
- *Cervus nippon* (Sika Deer)  
- *Muntiacus reevesi* (Muntjac)  
- *Hydropotes inermis* (Chinese Water Deer)

Due to licensing restrictions, **raw occurrence data is not included in this repository**.  
Users wishing to reproduce the analysis must download the datasets directly from NBN Atlas and place them in the project’s `data/` directory.  
All processing, cleaning, and modelling code is provided in the notebooks.
