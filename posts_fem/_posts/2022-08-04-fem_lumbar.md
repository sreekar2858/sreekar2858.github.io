---
layout: post
title: Stress in lumbar spine under specific loads - ABAQUS
subtitle: 
cover-img: /assets/img/fem/fem_1_bg.jpg
thumbnail-img: /assets/img/fem/biomech_spine1.jpg
tags: [FEM, ABAQUS]
---

<h3>Note</h3>
Hello, this webpage is still under development. The content is not yet worked on/ finalized and the links are not yet working. Please check back later. Thanks!

<!-- 
<p style="text-align: center; font-size:30px">Hey There!</p>

<div style="text-align: justify; padding: 0px 0px 0px -50px"> Sorry, the page you are looking for is not built completely or deployed yet. &emsp; Hopefully, It will be up and running in no time.&emsp;<br><br></div>
<img src="/assets/img/under_construction.png" alt="Sky" style="display: block; margin-right: auto; margin-left: auto;">

<p style="text-align: justify; font-size:30px">Check out other pages!! </p>

<a href="/2022-08-04-post1/" target="_blank" title="Certificate link">Test Page</a> -->

<h3>Abstract: </h3>
<p>
The objective of this work is to develop a method to simulate the biomechanics of the lumbar spine. A process is currently being used to convert a CT scan of a lumbar spine into a simulation model. The process includes converting the CT scan to a geometry file, creating a mesh of the bone and soft tissue, and assigning material properties to each element of the bone based on the bone density. Finally, the model is solved using Abaqus Explicit. Optimization techniques are used to tune uncertain material properties to match the kinematics of the simulation model to actual cadaveric test results. In addition, techniques have been explored to greatly reduce the computational time for the model. The soft tissue, discs, and ligaments were replaced with simplified mechanical constrains (ball-in-socket joints and non-linear, 3 dimensional torsional springs) and the vertebrae are rigid. This technique can be used for all or a portion of the spine.Further efforts are being pursued to simplify the workflow from CT scan to simulation model. This model can be used to simulate the performance of implants including total disc replacement and fusion techniques such as interbody spacers with rods and pedicle screws.
</p>