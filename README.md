# Low-Cost IoT Sensor Evaluation for Precision Agriculture

This repository contains the dataset and supporting materials used in the experimental evaluation of low-cost sensors for environmental monitoring in precision agriculture.

## Dataset

The dataset includes 3,279 measurements per variable:

- Ambient temperature (°C)
- Relative humidity (%)
- Soil temperature (°C)
- Soil moisture (ADC values)
- pH

## Methodology

Data were collected using a Raspberry Pi Pico W and low-cost sensors under semi-controlled environmental conditions. Measurements were recorded every 20–30 seconds.

## Markdown
Soil moisture values are obtained using a YL-69 sensor, which provides analog readings based on soil electrical conductivity (ADC values). These readings do not represent direct volumetric water content and should be interpreted accordingly.

## Purpose

The dataset is provided to support reproducibility and allow further analysis of sensor performance in agricultural IoT applications.

## Author

Jorge A. Cárdenas Magaña
