---
title: "M7.4 Earthquake in China"
categories:
  - news
  - results
tags:
  - earthquake
last_modified_at: 2021-05-21T23:25:52-05:00
header:
  teaser: /assets/images/earthquakes.jpg
---


We've captured a significant seismic event along our Distributed Acoustic Sensing (DAS) fiber network. On May 21, 2021, an earthquake of magnitude 7.4 struck Qinghai, China. Our data provides a fascinating comparison between traditional seismometer readings and the high-resolution capabilities of DAS technology.

Key Observations:

The sum of 600 data traces within the time window of the earthquake signal shows larger amplitudes compared to a single trace, highlighting the enhanced detection capabilities of DAS.
The unwanted noise at the beginning of the data track is notably reduced, improving the clarity of seismic readings.


<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/earthquake_snapshots.png" alt="">
  <figcaption> Earthquake in China recorded in Hamburg's WAVE network.</figcaption>
</figure> 

In the composite image, you can see many DAS data traces plotted vertically. The blue line indicates the single trace shown in the central plot, while the red area marks the 600 traces from which the sum trace was formed.
The lower graph reveals vertical lines corresponding to coherent seismic wavefronts, alongside spatial variations in the measured oscillation amplitudes that could indicate inhomogeneous subsurface structures. This illustrates the superior temporal and spatial resolution of DAS measurements.


<figure class="align-center">
  <video muted autoplay loop style="width: 85%; height: auto;" controls>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_eq_map.mp4" type="video/mp4">
  </video>
  <figcaption>Animation during the earthquake in China.</figcaption>
</figure>




The animation showcases earthquake waves propagating along the EuXFEL tunnel, triggered by the strong earthquake in China. On the right side, a waterfall diagram typical for DAS data displays the time series of strain amplitude for each fiber sensor, with dark blue indicating compression and light yellow showing elongation.
On the left, the evolution over time of the strain amplitudes recorded at all DAS sensors is projected onto the fiber track along the EuXFEL tunnel. Despite the wave length greatly exceeding the tunnel’s length, the spatial formation of wave crests and troughs is clearly visible as they propagate from East to West.
