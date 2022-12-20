---
layout: page
title: Next-Generation-Neural-Data-Analysis
description: "(2021-2022) Development of NGNDA, a tool for massive parallel analysis of brain data."
img: assets/img/research_4.png
importance: 4
category: research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/research_4_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/research_4_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

**Project Description:** NGNDA is a tool in development for massive parallel analysis of brain data. NGNDA includes Matlab codes for multiscale (multiband) connectivity analysis of human electrophysiological (EEG) and fMRI data. Within the fMRI pipeline, NGNDA allows for the analysis of CIFTI (representation of brain regions as greyordinates) AND NIFTI data from different studies. The tool has been designed for deployment in a High Performance Cluster (HPC) with shared resources.

**Lab:** Computational Neuroscience Lab at Boston Children’s Hospital

**Advisors:**  Dr. Caterina Stamoulis

**Other project members:** Sean Parks 

**Role:** Project Programmer as Research Assistant II

**Personal Contribution:**  
For resting-state fMRI data, developed and adapted prior scripts to process data from the Human Connectome Project - Aging study:
- Preprocess resting state fMRI data 
- Reduce the spatial dimensionality of the Human Connectome Project resting state fMRI data to set of brain regions (parcels)
- Denoise fMRI data by removing signal components (modes) that are outside of the expected frequency range and those with amplitudes outside a statistically estimated range
- Compute connectivity matrices for denoised (mode-reduced and resynthesized) raw data and individual mode band data, using multiple approaches (signal cross-correlation, cross-coherence and Mutual Information (MI)
- Calculates multiple network properties (including those in the Brain Connectivity Toolbox (Sporns, 2010) as well as an additional measure of network robustness (natural connectivity) using a user-defined set of thresholds to threshold connectivity matrices and create corresponding adjacency matrices (binary and weighted) from this network properties are estimated.   
 For task-based fMRI data, developed scripts to preprocess data from the Human Connectome Project - Aging study:
- Preprocess task fMRI data for Human Connectome Project resting task fMRI data

**Manuscript In Progress:**  
Parks, S., Kodibagkar, A., Stamoulis, C., Proposed Title: NGNDA: A Novel Computing Infrastructure for Massive Analyses of High-Dimensional Brain Networks and Next-Generation Research in the Neurosciences

