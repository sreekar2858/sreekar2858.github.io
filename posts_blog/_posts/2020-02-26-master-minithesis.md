---
layout: post
title: Development of an intelligent simulation-based model for design evaluation of cooling channels for L-PBF
subtitle: Masters - Mini-Thesis
cover-img: /assets/img/minithesis_bg.png
thumbnail-img: /assets/img/minithesis_tuning.png
# share-img: /assets/img/minithesis_tuning.png
tags: [CFD, AM, ANN, AI, OpenFOAM]
---

It is not practicable to analyse numerous support structure patterns, so a computational investigation using Computational Fluid Dynamics (CFD) solver must be employed to study the thermal and flow characteristics. It is also vital to balance the simulation runtime and accuracy. 
The workflow for this project uses a feedback loop. A CFD/ CHT simulation is run using OpenFOAM to generate a simulation dataset for a selected number of support shapes in patterns. An AI model is trained to fit the dataset with chosen inputs and outputs. Validate the ANN model with test data. Once the ANN model is trained to acceptable validation accuracy, it can also be employed to study new input data to achieve the ideal heat transfer coefficient and flow properties.
This process eliminates the CFD simulation from the loop which can be tedious. Validation accuracy and loss are used as a metric to evaluate if the ANN model is over-or-under fitting the dataset. This project’s scope is to successfully implement an ANN model into the development cycle, and research on novel shapes can be significantly reduced with similar results as computational simulation.

