# Saudi Arabia: Data Centers vs. Water Stress

An interactive map of Saudi Arabia's active, under-construction, and planned data centers, overlaid on projected future water stress from the WRI Aqueduct 4.0 Water Risk Atlas.

**Live map:** [abutaleb012.github.io/saudi-datacenters-water-stress](https://abutaleb012.github.io/saudi-datacenters-water-stress/)

By **Ali Abutaleb, PhD** · [Portfolio](https://abutaleb012.github.io/) · Basis for an IAEE MENA 2026 conference abstract.

## The question

Saudi Arabia is building one of the largest data center corridors in the Middle East, and data centers use large amounts of water for cooling. Where are those facilities, and how stressed is the water supply around them?

## What the map shows

- **43 data centers**: 26 active, 3 under construction, and 14 planned or announced.
- **Water stress, 2065 to 2095**, business-as-usual scenario, for 482 HydroSHEDS sub-basins, in six classes from low (under 10%) to extremely high (over 80%), plus arid and low water use areas.
- **Key figures**: 60+ operational data centers, about 304 MW of existing IT capacity, about 2.7 GW planned, and an estimated 13.3 billion liters of water consumed in 2024.

Nearly the whole country falls in the extremely high water stress class, so there is no low-stress region to move to. The choice of cooling technology matters more than location.

## Data

- **Water stress:** WRI Aqueduct 4.0, BAU 2065 to 2095, through Esri Living Atlas (CC BY 4.0).
- **Data centers:** MCIT, BlackRidge Research, and Arizton.
- **Water consumption estimate:** Mordor Intelligence.

## Built with

Leaflet and a single self-contained `index.html`, with the sub-basin polygons embedded. An ArcGIS Online version of the map was also produced.

## Files

- `index.html`: the complete interactive map.
