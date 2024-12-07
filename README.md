# Marimba MRITC Pipeline Demo Data

## Overview

This Marimba Pipeline example data was derived from the RV _Investigator_ voyage IN2018_V06 which investigated the status and recovery of deep-sea coral communities on seamounts in Australian marine reserves. The original voyage took place between November 23 and December 19, 2018, from Hobart, Tasmania. This example data has been specifically curated as demonstration data for use with the [Marimba MRITC Demo Pipeline](https://github.com/csiro-fair/mritc-demo-pipeline) demonstration code.


## Dataset Structure

The dataset consists of 10 subdirectories (025, 026, 045, 057, 060, 064, 114, 119, 128, 168), each containing:
- 100 low-resolution still images (JPG format)
- 1 one-minute video clip (MP4 format)
- 1 CSV file containing associated sensor data


### Directory Structure Example:

```
.
├── 025/
│   ├── 025.CSV
│   ├── GH010025.MP4
│   ├── IMG_0001.JPG
│   └── ... (100 JPG files total)
├── 026/
│   ├── 026.CSV
│   ├── GH010026.MP4
│   ├── IMG_0001.JPG
│   └── ... (100 JPG files total)
... (and so on for all 10 directories)
```


## Source Data

This example data was derived from a larger dataset collected during the RV _Investigator_ voyage IN2018_V06. The original high-resolution dataset can be accessed at: https://doi.org/10.25919/5cff30a66a6c6


## Purpose

This down-sampled example data provides a manageable subset of data for researchers and developers working with Marimba Pipelines while maintaining the structure and characteristics of the original data collection.


## Original Data Collection Context

- **Research Vessel:** RV _Investigator_
- **Voyage:** IN2018_V06
- **Title:** Status and recovery of deep-sea coral communities on seamounts in iconic Australian marine reserves
- **Date:** November 23 - December 19, 2018
- **Location:** 
  - Latitude: 41°10'48"S to 44°25'48"S
  - Longitude: 146°0'0"E to 148°57'36"E


## License

This example data is licensed under [CC BY-NC-SA 4.0](license.txt).


## How to Use

1. Clone this repository to get the example data:
   ```bash
   git clone https://github.com/csiro-fair/mritc-demo-data
   ```
2. Follow the instructions in the Marimba MRITC Demo Pipeline [README.md](https://github.com/csiro-fair/mritc-demo-pipeline/README.md) file to process this data using Marimba


## Contributing Organizations

- CSIRO (Australia)
- Marine National Facility (Australia)
- Parks Australia (Australia)
- University of Tasmania (Australia)
- And other collaborating institutions


## Contact

For inquiries related to this repository, please contact:

- **Chris Jackett**  
  *Software Engineer, CSIRO*  
  Email: [chris.jackett@csiro.au](mailto:chris.jackett@csiro.au)


## Acknowledgments

This example data was derived from data collected on the Marine National Facility (MNF) RV _Investigator_ voyage IN2018_V06. We acknowledge the contribution of all original research participants and organizations involved in the data collection.

