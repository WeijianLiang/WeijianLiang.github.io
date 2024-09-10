---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## 1. Multiscale modeling of granular media

The behavior of granular is among the most perplexing phenomena that attract sustained interests from science and engineering. The response of granular media is determined by their underlying structure. Weijian strives to establish a multiscale computational framework for granular media, which enables:

* Handling large deformation in geotechnical problems;
* Capturing microstructural evolution inside sample;
* Considering particle morphology;
* Direct information transfer across multiple scales.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 750px; margin: auto;"> 
        {% include figure.html path="images/anchor_d5_dense.gif" title="" class="img-fluid rounded z-depth-1" %}
        <div class="caption center">
            <h3> Anchor pullout in sand, which enables direct dialogue between multiple scales.</h3>
        </div>
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-3 mt-3 mt-md-0" style="max-width: 750px; margin: auto;"> 
        {% include figure.html path="images/AnisotropicFooting_v4.gif" title="" class="img-fluid rounded z-depth-1" %}
        <div class="caption center">
            <h3>Strip footing highlighting the contrast between isotropy and anisotropy.</h3>
        </div>
    </div>
</div>

## 2. Contact Algorithm for Mesh-free Approach

Contact algorithm is one of the challenging aspects of mesh free approaches like MPM. Weijian strives to devise robust contact algorithm for meshless method for improving their capbility in model complex problems. See below for our proposed dual-mortar based contact algorithm for MPM.


<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 750px; margin: auto;"> 
        {% include figure.html path="images/stick_animation.gif" title="" class="img-fluid rounded z-depth-1" %}
    <div class="caption center">
        <h3>Rolling disk on inclined plane</h3>
    </div>
</div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 750px; margin: auto;"> 
        {% include figure.html path="images/ironing.gif" title="" class="img-fluid rounded z-depth-1" %}
    <div class="caption center">
        <h3>Ironing test, featuring the large deformation and large sliding</h3>
    </div>
</div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 750px; margin: auto;"> 
        {% include figure.html path="images/packing.gif" title="" class="img-fluid rounded z-depth-1" %}
    <div class="caption center">
        <h3>Compression of a packing of soft grains</h3>
    </div>
</div>
</div>

## 3. Mesh-free Methods and High-performance computing

Weijian also endeavors to devise innovative scheme for meshless method (e.g., Material Point Method) and high-performance computing for leveraging the computational efficiency, fully unleashing their capacity. Those attempts include:

* Proposing semi-implicit integration scheme for hydro-mechanical MPM;
* Designing flat-MPI parallelism scheme for MPM-DEM approach;
* Porting the multiscale approach onto Tianhe2 supercomputer.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 750px; margin: auto;"> 
        {% include figure.html path="images/intruder-cylinder.gif" title="" class="img-fluid rounded z-depth-1" %}
        <div class="caption center">
            <h3>Three-dimensional intruder pullout in sand. This simulation is equipped with the proposed flat-MPI parallelism scheme and carried out in the Tianhe2 supercomputer.</h3>
        </div>
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 750px; margin: auto;"> 
        {% include figure.html path="images/wave_animation.gif" title="" class="img-fluid rounded z-depth-1" %}
        <div class="caption center">
            <h3>Wave propagation in saturate granular soil with varying microstructure, isotropy (left) and anisotropy (right)</h3>
        </div>
    </div>
</div>