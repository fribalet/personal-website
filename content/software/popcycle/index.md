---
title: Popcycle
date: "2014-12-01"
---
[Popcycle](https://github.com/armbrustlab/popcycle) is an R package (available at[Github](https://github.com/armbrustlab/popcycle)) that offers a reproducible approach to process, calibrate and curate flow cytometry data collected by [SeaFlow](https://seaflow.netlify.com).<br/>
The software package performs 3 key analyses:
1. ```Gating```: Classification of phytoplankton cell populations using a mixture of manual gating and a semi-supervized clusterting algorithm.
2. ```Light scatter conversion```: Convert light scattering of each particle to cell diameter ([fsc-size-calibration](https://github.com/armbrustlab/fsc-size-calibration)) and carbon content ([fsc-poc-calibration](https://github.com/armbrustlab/fsc-poc-calibration)).
3. ```Population data```: Perform aggregate statistics along with error propagation for the different populations.
The cell population identification (```gated``` data) and diameter and carbon content (```calibrated``` data) of each OPP are saved as separate text files with a similar file structure as the RAW data. The metadata, gating scheme, and aggregated statistics for each step are saved to a SQL database using SQLite3.

### Tutorials
Visit our [wikipage](https://github.com/armbrustlab/popcycle/wiki/SeaFlow-data-analysis-tutorial) to get started.

### Team
- [Chris Berthiaume](https://armbrustlab.ocean.washington.edu/people/beethiaume/)
- [Annette Hynes](https://armbrustlab.ocean.washington.edu/people/hynes/)
- [François Ribalet](https://francoisribalet.netlify.com)