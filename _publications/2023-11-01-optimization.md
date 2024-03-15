---
title: "Enhanced use of contextual data for quantitative Compton Imaging"
collection: publications
permalink: /publication/2023-11-01-optimization
excerpt: 'In this work the scene information obtained from contextual sensors is used to construct a 3D voxel grid. A 3D object of interest within this grid is selected by an operator either manually or automatically through an object detection machine learning framework. A number of potential measurement positions and orientations (poses) around this object of interest are identified, and the sensitivity to each of the object voxels from each of these poses is computed.'
date: 2023-11-01
venue: '2023 IEEE Nuclear Science Symposium and Medical Imaging Conference (NSS/MIC)'
citation: 'K. Knecht <i>et. al.</i>, "Enhanced use of contextual data for quantitative Compton Imaging," in <i>Proc. NSS/MIC</i>, 2023.'
---
Portable radiation detection systems can be equipped with contextual sensors to allow free-moving 3D gamma-ray imaging through scene data fusion (SDF). While developed for free-moving measurements, SDF also has applications in cases that require multiple static measurements to generate quantitative 3D images, where the scene information can improve results. The scene information captured by these devices can be leveraged to determine optimal measurement positions for quantification measurements, such as in safeguards applications, where limited time is provided to quantify nuclear material present. 

In this work the scene information obtained from contextual sensors is used to construct a 3D voxel grid. A 3D object of interest within this grid is selected by an operator either manually or automatically through an object detection machine learning framework. A number of potential measurement positions and orientations (poses) around this object of interest are identified, and the sensitivity to each of the object voxels from each of these poses is computed. Ray tracing is used to estimate any attenuation term, and the detector response for the Compton imaging modality is used in computing sensitivity. The combination of positions which results in maximum total sensitivity with minimum variance in sensitivity across object voxels are identified as the optimal measurement positions. For large measurement spaces the optimization is computationally intensive, so a genetic algorithm is used to accelerate the computation of optimal positions.

We first demonstrate the feasibility of the optimization framework with a toy model. We then use a SDF-enabled gamma-ray imager to find optimal measurement positions for a mock material holdup loop with distributed sources. We present our approach and results by performing an optimization to produce quantitative Compton images in these low-count-rate environments and the minimization of associated uncertainties. 

[Download paper here](https://ieeexplore.ieee.org/abstract/document/10337904)

Recommended citation: K. Knecht <i>et al.</i>, "Enhanced use of contextual data for quantitative Compton imaging," 2023 IEEE Nuclear Science Symposium, Medical Imaging Conference and International Symposium on Room-Temperature Semiconductor Detectors (NSS MIC RTSD), Vancouver, BC, Canada, 2023, pp. 1-1, doi: 10.1109/NSSMICRTSD49126.2023.10337904.