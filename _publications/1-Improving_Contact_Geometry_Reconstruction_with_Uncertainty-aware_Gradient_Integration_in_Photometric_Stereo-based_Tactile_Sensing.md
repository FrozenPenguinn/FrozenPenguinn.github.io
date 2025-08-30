---
title: "Improving Contact Geometry Reconstruction with Uncertainty-aware Gradient Integration in Photometric Stereo-based Tactile Sensing"
collection: publications
category: manuscripts
permalink: # URL
# permalink: /publication/2009-10-01-paper-title-number-1
excerpt: # URL
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-05-25
venue: 'IEEE Sensors Journal'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: # URL
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Accurate measurement of contact geometry is essential for robotic perception and manipulation, enabling object recognition, pose estimation, and precise in-hand control. Photometric stereo-based tactile sensors provide high-resolution contact surface information by estimating local gradients from a single RGB image captured under directional lighting. However, conventional reconstruction methods integrate these gradients uniformly, without accounting for their reliability – making them susceptible to errors caused by imaging noise, occlusion-induced shadows, and reflectance ambiguities. To address these limitations, this paper proposes an uncertainty-aware integration framework that models the uncertainty of each gradient estimate and incorporates it as a spatially varying weight during geometry reconstruction. Gradient uncertainty is derived from the empirical distribution of photometric mappings obtained through sensor calibration, and the integration is formulated to approximate a maximum likelihood estimate of the underlying surface. A lookup table-based implementation is developed to support inference of both gradient and weight from observed image intensities. The proposed framework is validated through both simulation and real-world experiments using a custom-built tactile sensor. Compared to the conventional unweighted approach, our proposal significantly reduces global reconstruction error, suppresses integration artifacts, and improves the geometric consistency of the recovered contact surface.

<br/><img src='/images/1-ga.png'>