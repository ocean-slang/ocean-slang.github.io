---
layout: page
title: Airborne remote sensing of submesoscale dynamics and phytoplankton
description:  
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

Abstract: Submesoscale dynamics can induce significant vertical fluxes of phytoplankton, nutrients, and carbon, resulting in biological and climatological impacts such as enhanced phytoplankton production, phytoplankton community shifts, and carbon export. However, resolving these dynamics is challenging due to their rapid evolution (hours to days) and small spatial scales (1-10 km) of variability. The Modular Aerial Sensing System (MASS), an airborne instrument package measuring concurrent ocean dynamics and hyperspectral ocean color, provides a powerful tool to study the influence of submesoscale dynamics on phytoplankton and carbon. In this study, we present the first airborne observations pairing snapshots of sub-kilometer ocean velocities and their derivatives  (i.e. vorticity, divergence, and strain) with concurrent ocean color and sea surface temperature. We developed airborne proxies of chlorophyll-a and particulate organic carbon, which explained about 66.2% and 56.2% of in situ variability without atmospheric correction, suggesting that MASS can capture phytoplankton variability. We also explored relationships between concurrent vorticity, divergence, strain, sea surface temperature, chlorophyll-a, and hyperspectral variables to illuminate the submesoscale processes that alter phytoplankton distributions. This study demonstrates the value of merging bio-optical and physical airborne remote sensing data to better understand the influence of submesoscale dynamics on oceanic ecosystems and organic carbon. We highlight the potential for suborbital remote sensing for studying processes that impact phytoplankton ecosystems and carbon transport without the spatiotemporal aliasing affecting in situ sensors.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/overview.png" title="overview of study region, plane lines, chl-a and SST variability" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
The S-MODE study region (black polygon) is overlaid on Sentinel-3 log-10 chlorophyll-a from October 29, 2021 (0.3 km resolution, time of collection (TOC): 18:44 - 18:47 UTC). Black lines indicate the repeated vessel and MASS transects. b) A zoomed-in view of Transects A and B overlaid on Sentinel-3 chl-a and b) sea surface temperature from the same day (1 km resolution, TOC: 17:01 - 18:42Z). Transect A was flown over 5 times and the lines will be referred to as A1 (TOC: 19:36 - 19:57 UTC), A2 (TOC: 20:23 - 20:41 UTC), A3 (TOC: 20:44 - 21:01 UTC), A4 (TOC: 21:06 - 21:23 UTC), and A5 (TOC: 21:52 - 22:09 UTC). Transect B was flown over 2 times and the lines will be referred to as B1 (TOC: 20:31 - 20:51 UTC) and B2 (TOC: 21:01 - 21:28 UTC). Flights over these transects made parallel overlaps with the ship (TOC: 12:44 - 21:29 UTC). Distance along track in kilometers for Transect A (line A2 analyzed in Sections 5 and 6) are denoted by black circles and white numbers in panel b.)</div>

Text

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/plane_schematic.png" title="plane schematic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Schematic describing the dependency of the swath width and spatial resolution of ocean color data on the altitude of the Twin Otter aircraft (top left). The hyperspectral camera on MASS faces downwards, measuring upwelling radiance (L<sub>t<\sub>(lambda)) from the sea surface and the atmosphere below. FODIS measures hyperspectral downwelling irradiance (E<sub>d<\sub>(lambda)) and is mounted on the top of the aircraft. MASS is equipped with a lidar, DoppVis instrument, pyrometer, hyperspectral camera, video, and longwave infrared (right box). MASS instruments analyzed in this study are starred. Schematic is not to scale.)</div>

text

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/model_scatter.png" title="plane schematic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Band ratios are plotted against corresponding in situ measurements, log-10 chlorophyll-a (a) and log-10 particulate organic carbon (b). Airborne model predicted log-10 chlorophyll-a plotted against corresponding ship-based log-10 chlorophyll-a (c). Airborne model predicted log-10 particulate organic carbon plotted against corresponding ship-based log-10 particulate organic carbon (d). Points are colored by line number. Data points used to train the multiple regression model are outlined in light gray. 1:1 lines in solid black.</div>

text

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/agreement.png" title="plane schematic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Along-track log-10 chl-a (a) and log-10 POC (b) for the three longest and clearest lines: A1 (orange), A2 (blue), and A3 (green). One-second binned ship-based chl-a (dark green) and POC (purple) (c). Ship based observations greater than 2 hours apart from plane observations denoted by dashed lines in (c), and ship observations within 2 hours denoted by solid lines in (c). Full swath view of high-chlorophyll feature (d-f) with central line time in UTC labeled below swath.</div>

text

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/colocated-1.png" title="co-located physical and bio measurements" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Δ&#961 (black), &#946ΔS (gray), &#945ΔT (red) measured by the R/V Oceanus plotted against distance along the track (a). Δ&#961 denotes the density change from the start of the track, where distance along track is 0 km. ΔT and ΔS are the changes in temperature and salinity from the start of the track. ΔT and ΔS are scaled by their corresponding thermal expansion and salinity contraction coefficients (&#946,#945). SST (red), log-10 chlorophyll-a (dark green), and log-10 particulate organic carbon (purple) plotted against distance along track (b). PC3, PC4, and PC5, representing spectral shifts potentially associated with phytoplankton community shifts, plotted against distance along track (c). Kinetic energy flux plotted against distance along track (d). Five features of interest denoted by gray shaded regions (b-d).</div>

text

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/F3_F5.png" title="Example of 2 features of interest, aligning convergence/divergence features with ocean color" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Full swath SST, full swath log-10 chlorophyll-a, 1-D PCs 3-5, full swath vorticity, full swath divergence, and full swath strain plotted against distance along track for feature of interest, F3. Distance across track plotted on y-axis as y (m). PC’s normalized to have a mean of 0 and a standard deviation of 1. Vorticity, divergence, and strain normalized by Coriolis parameter. Central line time was 20:28 UTC. SST, log-10 chlorophyll-a, PCs 3-5, vorticity, divergence, and strain as in Fig. \ref{Fig:f1} for F5 (g-l). Central line time was 20:25 UTC. SST is cut off due to camera acquisition failure.</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cartoon.png" title="schematic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Schematics that illustrate a few of the dynamical mechanisms driving local surface chl-a enhancement or reduction (a-f). Upwelling of the deep chlorophyll maximum (DCM) induced by surface divergence brings high chl-a water towards the surface (a). Upwelling of nutrients induced by surface divergence can spur the growth of phytoplankton in nutrient-limited regimes (b). Surface convergence of phytoplankton at the surface can lead to high chl-a patches in regions of downwelling (c). Dense filaments pinching off of high chl-a water masses can converge and downwell, leading to enhanced surface chl-a associated with a vertical extent (d). Ageostrophic secondary circulation (red arrows) associated with submesoscale fronts can induce vertical velocities impacting surface phytoplankton concentrations (e). Stirring of larger chl-a gradients can generate submesoscale filamentous structure (f). Schematics that demonstrate how different measurement integration depths between sensors can affect ocean color and SST measurements from MASS (g,h). Approaching the front from the warm side, the chl-a front is detected by MASS before the SST front due to its deeper integration depth. Integration depths can also cause SST gradients to be sharper than chl-a gradients.</div>

