---
layout: page
title: Neuron Segmentation Algorithms
description: "(2020) Testing of State-of-the art Neuron Segmentation Algorithms"
img: assets/img/research_7.png
importance: 7
category: research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/research_7_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Image from:  
Li, Rui, et al. "Precise segmentation of densely interweaving neuron clusters using G-Cut." Nature communications 10.1 (2019): 1-12.

**Project Description:** Most existing neuron reconstruction software is only applicable to single neurons. However, there is a need to conduct neuron morphology reconstruction for interweaving neuron clusters. The goal of this project is to test state-of-the-art neuron segmentation algorithms separating neuron clusters into individual neurons to the mouselight dataset, which contains neural wiring diagrams for over 1000 long projecting neurons in the mouse brain. G-Cut is a program allowing automatic segmentation of individual neurons from interweaving neuron clusters. G-Cut achieves segmentation by maximizing global fitness for branches in the graph. For this project, I simulated connected graphs with multiple neurons in the mouselight dataset and applied G-Cut to this data.

**Lab:** Neurodata Lab at Johns Hopkins University

**Advisors:**  Dr. Joshua Vogelstein, Tommy Athey (Ph.D. Candidate)

**Role:** Independent Project as Research Intern

**Personal Contribution:**
- For this project, I simulated connected graphs with multiple neurons in the mouselight dataset and applied G-Cut to this data.
- I Added an edge between 2 neurons to simulate a connected graph containing multiple neurons (neuron cluster) 
- I then calculated the number of correctly assigned vertices on the 2 new graphs
- I found that 74.4% Vertices were preserved for 100 simulated neuron pairs
- I found that G-Cut was not ideal for neurons with long projecting axons due to the algorithm’s assumption that axon branches extend directly out from the soma

