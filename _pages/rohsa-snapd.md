---
layout: page
title: ROHSA-SNAPD
description: "Spatially non-parametric recovery of intrinsic kinematic maps in pre- to post-merger galaxies"
permalink: /projects/rohsa-snapd/
nav: false
---

<!-- PARAGRAPH 1. -->

The majority of my PhD has involved developing and applying the kinematic deconvolution tool [ROHSA-SNAPD](https://github.com/isaackanowski/ROHSA_SNAPD), which I adapted from [ROHSA](https://github.com/antoinemarchal/ROHSA) by Antoine Marchal.

{\tt ROHSA-SNAPD} is designed to be easily applied to other 3D data and is agnostic to a specific emission line or wavelength.

I include here two example figures, the first is of an interacting galaxy observed by the KMOS<sup>3D</sup> survey and highlights the complex flux structure that the tool allows us to observe and analyse.

{% include figure.liquid path="assets/img/rohsa-snapd/fig1.png" alt="DESCRIBE FIGURE 1" class="img-fluid rounded z-depth-1" zoomable=false %}
<div class="caption">
  <strong>Figure 1.</strong> An interacting galaxy in the KMOS<sup>3D</sup> survey, as seen in 3-colour JWST imaging (left panel), observed H\(\alpha\) flux (middle panel) and deconvolved ROSHA-SNAPD flux (right panel).
</div>

<!-- PARAGRAPH 2. -->
The second figure shows the result of applying ROHSA-SNAPD to a mock observation of a kinematically complex \(z=2\) merger from the IllustrisTNG cosmological simulation in Kanowski et al. (2025). The deconvolved ROHSA-SNAPD kinematics agree well with the intrinsic simulation kinematics.

{% include figure.liquid path="assets/img/rohsa-snapd/fig2.png" alt="DESCRIBE FIGURE 2" class="img-fluid rounded z-depth-1" zoomable=false %}
<div class="caption">
  <strong>Figure 2.</strong> A mock observation of a \(z=2\) merger from the IllustrisTNG cosmological simulation (Kanowski et al. 2025).
</div>


The ROHSA-SNAPD code and an example application are available on the [Github page](https://github.com/isaackanowski/ROHSA_SNAPD).
