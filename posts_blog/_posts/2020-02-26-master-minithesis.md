---
layout: post
title: Development of an intelligent simulation-based model for design evaluation of cooling channels for L-PBF
subtitle: Masters - Mini-Thesis
cover-img: /assets/img/minithesis_bg.png
thumbnail-img: /assets/img/minithesis_tuning.png
# share-img: /assets/img/minithesis_tuning.png
tags: [CFD, AM, ANN, AI, OpenFOAM]
---

<h3>Note</h3>
Hello, this webpage is still under development. The content is not yet worked on/ finalized and the links are not yet working. Please check back later. Thanks!

<h4>Abstract:</h4>
<p>
In this thesis an Artificial Neural Network (ANN) model has been submitted to intelligently evaluate cooling channel with the help of simulation database. A case of rectangular cooling duct is considered with different cross-section support structures in a staggered position to lead conjugate heat transfer. A multi-region steady-state turbulent simulation has been carried out in OpenFOAM with chtMultiRegionSimpleFOAM solver for various support structures and reynolds numbers. The results are interpolated and saved at coarse grid locations of both domains (fluid, solid) to reduce the amount of data stored; which create a database of mesh (point cloud) and parameters linked to the location.<br>

The simulation database was used to train a neural network model. Graph Neural Networks (GNN) was chosen for its ability to relate the mesh points and also capture the geometric features. The trained GNN model, developed in python is used to predict the temperature distribution in the cooling channel for untrained geometry and validate the accuracy with the actual temperature distribution from simulation results.<br>
</p>

<h4>Introduction:</h4>
<p>
Technological advancements enabled Additive Manufacturing (AM) to be promising and potentially supersede conventional manufacturing in mass production. Development from the past years in accuracy and efficiency of AM allows it to have relatively less impact on the environment and produces zero waste delivering high-quality components. Unlike traditional manufacturing, AM enables the fabrication of lighter, stronger, and more complex parts with less hassle. Laser Powder Bed Fusion (LPBF) is one of the most popular AM processes which is used to fuse the metal powder to form the desired shape. LPBF operate on laser energy to melt (pure-or-alloyed) metal particles; with size ranging from approx. 20 to 60 microns in successive layers.<br>
Due to the nature of AM technique, it is possible to construct hollow/ infill structures tailoring the mechanical characteristics of the part relevant to the application. AM needs temporary support structures that hold certain shapes (such as overhangs) in place until the printing is done. In some cases, it is not feasible to remove these support structures. It is possible to exploit these support structures in high-or-low temperature applications to cool/ heat the component by flowing fluid through the geometry allowing conjugate heat transfer (CHT). The cavity that fluid passes through with the support structures can be referred to as cooling channels. Several computational/ experimental studies must be carried out to maximize the effect of heat transfer with little to no effects on structural and flow characteristics.<br>
To study the effects of support structures on structural, thermal, and fluid characteristics Artificial Neural Networks (ANN) can be utilized. ANN has several neurons in layers that are trained based on the given input and output. A trained model is validated against test data to compute the validation accuracy and loss of the prediction. 
</p>

<h4>Methodology:</h4><br>

<img src="/assets/img/minithesis_methodology_1.jpg" alt="Methodology" width="100%">