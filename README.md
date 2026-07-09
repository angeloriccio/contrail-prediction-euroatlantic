# Euro-Atlantic Contrail Prediction and Verification

Observation-based workflow for detecting, tracking, and attributing aircraft contrails over the Euro-Atlantic and North Atlantic region using geostationary satellite imagery, meteorological reanalysis, and historical aircraft trajectory data.

## Project Overview

Aircraft contrails can contribute to aviation climate forcing, especially when they persist, spread into contrail cirrus, and occur during nighttime or in regions with strong longwave radiative effects. This project aims to build a practical, reproducible workflow to detect and analyse persistent contrails from satellite observations and to link them probabilistically to aircraft trajectories and meteorological conditions.

The initial focus is on selected 2023 case-study periods over Western Europe and the North Atlantic flight corridor, where MSG/SEVIRI infrared observations, ERA5 meteorology, and OpenSky historical state-vector data can be jointly analysed.

## Scientific Aim

The main goal is to develop an observation-based framework for contrail prediction and verification.

The project investigates whether linear ice-cloud features observed in MSG/SEVIRI infrared imagery are:

- temporally persistent across consecutive satellite images;
- spatially consistent with aircraft trajectories at cruise altitude;
- located in meteorological environments favourable to persistent contrail formation;
- advected consistently with upper-tropospheric winds;
- suitable for building labelled datasets and validation products for contrail detection models.

## Study Area

The broad study region is the Euro-Atlantic and North Atlantic domain:

```text
20°N–70°N
60°W–40°E
