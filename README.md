# Impact of Downsampling on sEMG Signals

## Overview

--This repository contains a comprehensive analysis of the impact of downsampling on sEMG (surface electromyography) signals. The dataset used for this analysis is sourced from the EMAHA DB7 dataset (which is currently not publicly available). The dataset consists of sEMG signals recorded from four channels on the right hand while performing various Activities of Daily Living (ADLs) in three different hand postures, both at normal and fast paces.

## Files and Contents

- **Filtering.mlx**: This file contains the code to apply a 20Hz High-Pass filter and a 50Hz Band-Stop filter to the sEMG signals, preparing them for further analysis.

- **Impact_of_Downsampling_on_sEMG_signals.mlx**: This file contains the code for the entire experiment. Here's an overview of the steps performed:

    1. Removal of the rest and release phases from the signals.
    
    2. Downsampling of the normal-paced signal.
    
    3. Calculation of correlations between normal-paced and fast-paced signals, as well as correlations between downsampled and fast-sampled signals.
    
    4. Visualization of the complete analysis results.
    
## Experiment Details

The primary focus of this analysis is to understand how downsampling affects sEMG signals acquired during different activities and hand postures, both at normal and fast paces. The experiment involves signal preprocessing, downsampling, and correlation analysis to gain insights into the impact of downsampling on sEMG data.

Please note that the dataset used in this analysis is from the EMAHA DB7 dataset, which is currently not publicly available.

For more details on the analysis and the findings, refer to the code files and visualizations provided in this repository.
