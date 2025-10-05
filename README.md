# Sediment Plumes in the Shannon Estuary — Open Challenge

*Goal*: Open paths to detect, understand, forecast, communicate, or mitigate sediment plumes in the Shannon Estuary — coast to Limerick reach.

## Why this matters
Storms, discharge, and wind/tide resuspend fine sediments, forming plumes that cut water clarity, stress oysters/seagrass, and disrupt navigation, aquaculture, and port work. A shared playbook for when, where, and why plumes occur helps schedule activities, protect habitats, and build trust. It can also attract investors and shape fair regulation. The Shannon is well placed to show the world how reliable energy harvesting and stewardship can align.

## Guiding questions (optional)
- How can plumes be reliably detected and described (extent, direction, intensity)?
- Which drivers (flow, rainfall, wind/waves, tide, vessels) trigger the strongest plumes?
- Can we provide useful nowcasts, alerts, or forecasts?
- What actions reduce impacts, and when should they happen?
- How to communicate uncertainty and involve local users?

## Example outcomes
- Detection/characterisation methods (EO, drone, in-situ)    
- Driver analysis or forecast prototype  
- Decision-support dashboard or workflow  
- Mitigation playbook (timing, sensitive-area maps)  
- Comms kit (story map, SOPs, uncertainty guide)  
- Reproducible code + clean data package  

## Scope & difficulty
- Shannon Estuary (coast ↔ Limerick); historic or new observations; possible upstream links  
- Financial flow, investment trust, and governance  
- *Difficulty*: Intermediate; up to Advanced with physics models or custom sensors  

## Resources (use/adapt as needed)

*Earth Observation*  
- Sentinel-2 L2A (NDTI, Red/NIR), with sunglint & intertidal masking  
- Optional Sentinel-1 SAR for surface roughness/wind  
- Sentinel-3 OLCI for wider context in cloud gaps  

*Hydro-met drivers*  
- River discharge & levels (OPW/ESB)  
- Tide phase/range, harmonic predictions  
- Wind, waves, rainfall (Met Éireann / Marine Institute)  

*Auxiliary layers*  
- Bathymetry, shoreline, intertidal flats  
- Protected habitats, aquaculture leases  
- Navigation channels, pilotage zones  
- Shoreline infrastructure  

*In-situ options*  
- Boat turbidity/CTD transects, moored loggers  
- Opportunistic water samples  
- Community photo logs with GPS/time  

*Tooling*  
- QGIS/SNAP/GEE  
- Python/R for event extraction, shape metrics, driver tables  
- Optional hydrodynamic/particle-tracking (Delft3D/Telemac)  

## Possible pathways
- EO-first detection → plume index + atlas  
- Driver/risk modelling → discharge–wind–tide combos, alert rules  
- In-situ + EO fusion → validate EO, generalise  
- Operational playbook → sensitive zones + timing windows  
- Decision communication → dashboard/story map, clear uncertainty  
- Nature-based mitigation → bank stabilisation, eelgrass, monitoring  

## Example metrics
- Detection skill for extreme events (precision/recall, hit/false alarm)  
- Forecast lead time at action thresholds  
- Usefulness: at least one partner acts on outputs  
- Maintainability: open code, simple inputs, clear SOPs
