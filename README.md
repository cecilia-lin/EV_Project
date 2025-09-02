# Overview

In response to climate change, air quality concerns, and volatile fuel prices, we analyzed consumer preferences for Battery Electric Vehicles (BEVs) vs. Plug-in Hybrid Electric Vehicles (PHEVs) across Washington State counties, using a comprehensive registration dataset (1999–2025, >210k records).
We explore geographic patterns, price/range characteristics, and test whether preferences differ significantly by county.


# Research Question & Hypothesis

RQ: Is there a statistically significant difference in the preference for PHEVs vs. BEVs across Washington counties?

H₀ (Null): Vehicle type (BEV vs. PHEV) is independent of county.
H₁ (Alt): Vehicle type (BEV vs. PHEV) depends on county.

Hypothesis (directional): Counties show a significant preference for BEVs over PHEVs, reflected in higher BEV ratios across counties, driven by charging infrastructure, incentives, and technology advantages.

# Data

Primary Dataset: Electric Vehicle Population Data (WA)

Source: Washington State (Data.gov catalog)

Link: https://catalog.data.gov/dataset/electric-vehicle-population-data

Rows: ~210,165

Columns: 17 (key: County, Electric Vehicle Type, Electric Range, Base MSRP, Model Year)


# Key Findings

- BEVs dominate registrations in every county analyzed; BEV ratios > 0.5 statewide.

- King and Snohomish counties lead in absolute counts and show high BEV:PHEV ratios.

- Range vs. price: BEVs show substantially higher ranges than PHEVs for overlapping price bands.

- Temporal trend: Post-2018, BEV adoption accelerates sharply (model-year proxy).

- Statistics: Chi-square test strongly rejects independence (p ≪ 0.05), indicating county-level differences in BEV/PHEV preference distributions.
