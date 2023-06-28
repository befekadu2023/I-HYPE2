# I-HYPE2
This is a modified HYPE hydrological and water quality modelling tool (Version 5.5.1) that replaces the operator-splitting sequential calculation numerical scheme of the HYPE version 5.5.1 by the implicit fourth order Gear-Nordsieck numerical scheme that uses adaptive time step and truncation error control mechanism. It transforms the differential equations used by HYPE to solve percolation, lateral soil fluxe, and evapotranspiration into a state-space formulation and solves the fluxes generated from all soil layers simultaneously. This version of HYPE is referred to as I-HYPE.
