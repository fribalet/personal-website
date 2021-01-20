---
title: Popcycle
date: "2014-12-01"
---
[Popcycle](https://github.com/seaflow-uw/popcycle) is an R package that offers a reproducible approach to process, calibrate and curate flow cytometry data measured by SeaFlow.<br/>
The software package performs 3 key analyses
1. ```Gating```: Classification of phytoplankton cell populations using a mixture of manual gating and a semi-supervized clusterting algorithm.
2. ```Light scatter conversion```: Convert light scattering of each particle to cell diameter ([fsc-size-calibration](https://github.com/seaflow-uw/fsc-size-calibration)) and carbon content ([fsc-poc-calibration](https://github.com/seaflow-uw/fsc-poc-calibration)).
3. ```Population data```: Perform aggregate statistics along with error propagation for the different populations.
The cell population identification (```gated``` data) and diameter and carbon content (```calibrated``` data) of each OPP are saved as separate text files with a similar file structure as the RAW data. The metadata, gating scheme, and aggregated statistics for each step are saved to a SQL database using SQLite3.
