---
layout: page
title: Wind Energy
description: Learn more about blade-resolved wind turbine and wind farm simulations using WAKE3D.
img: assets/img/phaseVI.tile.png
importance: 2
category: Applications
---

Much of my research focuses around the application of wind energy and developing predictive physics software tools.
The goal of this research is to develop aerodynamically-accurate simulation software whereby the wind turbine models 
are resolved geometrically (known as blade resolved) in contrast to lower-fidelity models which used parameterized models 
to generate wakes. Though the development of our multiscale CFD tool, WAKE3D, we are able to solve problems with spatial scales 
ranging from 10+ km all the way down to sub-micron levels at the blade! Some highlights regarding this work are shown below 
including the highest fidelity simulation of a wind turbine to date.

<h2>Wake Breakdown, Turbulence, and Interactions</h2>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/windturbine-wake.gif" title="Wind Turbine Turbulent Wake" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
Wind turbines generate complex wake structures which mix with free air to reenergize the flow but over vast distances. 
These wakes can cause significant drops in energy generation efficiency of neighboring downstream wind turbines. 
Understanding these interactions and engineering mitigation strategies can result in significant increases in energy production each year.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include youtube.html id='OuV3ZwdWntI' class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Wake interactions between two wind turbines.
</div>

<h2>Wind Farm Simulations</h2>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include youtube.html id='NHNL5JRQnHQ' class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Much of this wind energy research was performed on the NCAR-Wyoming Cheyenne and Yellowstone supercomputers. <br/>
    This video highlights the work done as part of my Ph.D. dissertation research.
</div>


<div class="row">
    <div class="col-sm-mt-3 mt-md-0" >
        {% include youtube.html id='OuV3ZwdWntI' class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/phaseVI.10ms.fast.gif" title="Wind Turbine Turbulent Wake" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Isocontour visualization of the tip vortices generated by the NREL Phase VI wind turbine. Uniform inflow of 10 m/s.
</div>

<article>
    {%- include WE_papers.html %}
</article>
