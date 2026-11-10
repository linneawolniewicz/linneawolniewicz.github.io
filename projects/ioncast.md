---
layout: project
type: project
image: img/ioncast/TEC_maps.png
title: "Ionospheric Forecasting: HelioLab and NASA JPL"
date: 2026
published: true
labels:
summary: "Global ionospheric forecasting with vision, graph, and recurrent models, from FDL's HelioLab to NASA JPL"
---

I work on machine learning methods to forecast the state of Earth's ionosphere, a region of the upper atmosphere that affects GNSS positioning and radio communications. This research combines global maps of **Total Electron Content (TEC)** with solar and geomagnetic drivers to model how the ionosphere changes, especially during geomagnetic storms.

### NASA Jet Propulsion Laboratory (2026)

From March to June 2026, I continued this research as an intern with NASA JPL's **Machine Learning and Instrument Autonomy Group**, mentored by Dr. Umaa Rebbapragada and working with Dr. Olga Verkhoglyadova and Dr. Ryan McGranaghan. Building on the HelioLab dataset and forecasting models, I optimized deep learning architectures to reduce computational runtime and resource costs, and developed a comprehensive evaluation pipeline across geomagnetic storm conditions.

Our latest work, *Ionospheric Forecasts Across Geomagnetic Conditions: Comparing Vision, Graph, and Recurrent Models*, compares an autoregressive **Vision Transformer**, a **GraphCast-inspired Graph Neural Network**, and a **ConvLSTM** for global TEC forecasts up to three hours ahead. We evaluate forecasts across storm intensities, geographic regions, local times, and forecast horizons, and examine how forecasting the physical drivers affects model performance. The goal is to understand where each model works well and how reliably it captures ionospheric variability under different space-weather conditions.

[Read about the 2026 workshop paper](/publications/ionospheric_forecasts.html)

### FDL's HelioLab (2025)

The project began during my June–October 2025 internship with Frontier Development Lab's HelioLab, as part of the Ionosphere–Thermosphere Digital Twin project. My team and I developed a machine-learning-ready dataset combining heterogeneous solar and geomagnetic drivers with ionospheric observations, along with forecasting models called **IonCast** and **Ionopy**.

We presented three related works at the Machine Learning for the Physical Sciences workshop at NeurIPS 2025, with related work also presented at AGU 2025:

- [Connecting the Dots: A Machine Learning Ready Dataset for Ionospheric Forecasting Models](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_358.pdf)
- [IonCast: A Deep Learning Framework for Forecasting Ionospheric Dynamics](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_360.pdf)
- [Forecasting the Ionosphere from Sparse GNSS Data with Temporal-Fusion Transformers (Ionopy)](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_327.pdf)
