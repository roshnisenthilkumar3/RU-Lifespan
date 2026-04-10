# Data

## Source
UCI AI4I 2020 Predictive Maintenance Dataset
https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

## Download
Download the dataset from the link above and place the extracted CSV at:
backend/data/raw/ai4i2020.csv

## Dataset Overview
- 10,000 rows, 14 features
- Simulates real predictive maintenance data from manufacturing equipment
- Failure rate is approximately 3% — the dataset is heavily imbalanced

## Columns
- UDI — unique identifier
- Product ID — product serial number with quality variant (L, M, H)
- Type — product quality type (Low, Medium, High)
- Air temperature [K] — air temperature in Kelvin
- Process temperature [K] — process temperature in Kelvin
- Rotational speed [rpm] — rotational speed in RPM
- Torque [Nm] — torque in Newton metres
- Tool wear [min] — tool wear in minutes
- Machine failure — target variable (0 = no failure, 1 = failure)

## Failure Modes
- TWF — tool wear failure
- HDF — heat dissipation failure
- PWF — power failure
- OSF — overstrain failure
- RNF — random failure