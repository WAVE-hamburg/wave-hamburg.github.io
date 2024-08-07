---
permalink: /science/
title: Science
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Smart_City.png
excerpt: "We're working on exciting research projects that help us create interesting theses and publications. We're committed to exploring new ideas and making progress in our research."
toc: true
toc_label: "Page content"
toc_icon: "heart"  # corresponding Font Awesome icon name (without fa prefix)
toc_sticky: true
read_time: false
---

## Results 

In the following, we present a few results from the initial "Proof of Concept" measurement campaign in 2021, as well as a few more recent results. Keep an eye on this, it will be updated (semi-)regularly!

<figure class="half">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/iDAS.jpg" alt="">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/georeferencing.jpg" alt="">
    <figcaption>DAS interrogator and fiber georeferencing.</figcaption>
</figure>

### Signals along the DAS fiber

*Overview of whole fiber track:* Waterfall diagram of the records of all DAS sensors along the 12.6 km long fiber. The maximum amplitude of the time series at 20 s intervals is color-coded across the spatially distributed sensors and the 16 hour recording period. The arrows mark events that are described in the listing (click for details), numbered accordingly.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/summary_waterfall.png" alt="">
  <figcaption>Waterfall Diagram.</figcaption>
</figure> 

*Signals along EuXFEL tunnel:* Spectra of all DAS channels along the accelerator tunnel XTL, during accelerator operation of EuXFEL. Already at first glance, many elements that may cause disturbance or noise can be identified by their characteristic frequencies. Some prominent elements are marked for illustration.

<figures class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/XTL-spec-_smaller.png" alt="">
  <figcaption>Spectrogram from EuXFEL tunnel.</figcaption>
</figure> 



### Car signals

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/cars_composite.png" alt="">
  <figcaption>Car signals.</figcaption>
</figure> 

*Cars passing the DAS fiber:* Spatiotemporal DAS recording of passing cars is shown at the top. The fiber section between positions 10430 and 10800 is immediately adjacent to a road. A map of the road section is shown at the bottom left. At the bottom right is a recording of the passage of a single car, with horizontal lines framed in appropriate color corresponding to snapshots of the fiber excitation at the bottom center. Since the fiber passes the road twice in opposite directions, the waterfall diagram is mirrored about the horizontal at a distance of 10645m. The cars are clearly visible as diagonal stripes, and their slope gives immediate information about the speed of the cars (about 18 ± 5km/h). The first car appears at about second 60. Another car travels in the same direction starting at second 125. While the first car crosses a clearly slower road user traveling in the opposite direction towards the end of the road section about 15 seconds later, the second car apparently encounters three other vehicles. One of them leaves its parking place halfway, two others come towards it in close succession.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_car_map.mp4" alt="">
  <figcaption>Car animation.</figcaption>
</figure> 

*Animation of car driving along the fiber:* The same section of fiber as shown in the figure on the left. The high amplitudes in the DAS recordings, indicated by yellow color, follows the location of the car.

### Earthquake signals

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/earthquake_snapshots.png" alt="">
  <figcaption> Earthquake in China recorded in Hamburg's WAVE network.</figcaption>
</figure> 
*Earthquake in China recorded along the DAS fiber:* Comparison of seismometer data with DAS data. Shown is an earthquake that occurred on 21.05.2021 in Quinghai (China) with a magnitude of 7.4.
It can be seen that the amplitudes of the sum of 600 data traces in the time window in which the earthquake signal arrives are larger than those of the single trace. The amplitudes of the unwanted noise at the beginning of the data track are reduced. In the lowest plot, many DAS data traces are plotted below each other. The blue line marks the single trace shown in the center plot. The red area covers the 600 traces from which the sum trace was formed.
In the lower graph, in addition to the vertical lines corresponding to the coherent seismic wavefronts, spatial variations of the measured oscillation amplitudes can be seen. These may be related to inhomogeneous subsurface structure and illustrate how DAS measurements provide high temporal and spatial resolution.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_eq_map.mp4" alt="">
  <figcaption>Animation during the Earthquake from China.</figcaption>
</figure> 
*Animation of Earthquake waves propagating along EuXFEL tunnel:* Propagation of seismic waves caused by a strong earthquake (magnitude 7.4) with epicenter in China through the EuXFEL tunnel.
On the right, a typical representation for DAS data (waterfall diagram) is shown, which color-codes the time series of strain amplitude (y-axis) for each fiber sensor (channel, x-axis). Here, the dark blue color represents compression and light yellow represents elongation of a fiber segment.
On the left, the evolution over time of the strain amplitudes (strain rate) recorded at all DAS sensors is projected onto the fiber track along the EuXFEL tunnel.
Although the length of the waves exceeds that of the tunnel many times over, the spatial shaping of the wave crests and troughs can be clearly recognized as they propagate from East to West.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_EQ_turkey.mp4" alt="">
  <figcaption>Animation during the Earthquake from Turkey.</figcaption>
</figure> 
*Animation of 2023 Turkey-Syria Earthquake recorded along EuXFEL tunnel:* 
Recording of the destructive magnitude 7.5 Turkey-Syria earthquake on February 6, 2023.
On the right, a typical representation for DAS data (waterfall diagram) is shown, which color-codes the time series of strain amplitude (y-axis) for each fiber sensor (channel, x-axis). Here, the dark blue color represents compression and light yellow represents elongation of a fiber segment, as illustrated on the waveform on the very right.
On the left, the evolution over time of the strain amplitudes (strain rate) recorded at all DAS sensors is projected onto the fiber track along the EuXFEL tunnel.

### Vibrotruck sweeps

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/vibrotruck.jpg" alt="">
  <figcaption> Vibrotruck.</figcaption>
</figure> 

Vibrotruck of the company Baudynamik Heiland & Mistler GmbH exciting the frequency sweep seen on the right. 

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/sweeps_signal_spectrogram.png" alt="">
  <figcaption> Spectrogram of 4 Vibrotruck sweeps in the DAS fiber.</figcaption>
</figure> 
*Ground motion excited by the Vibrotruck:* Vibration spectra measured in the accelerator tunnel of EuXFEL very clearly show the ground vibrations that a so-called vibrotruck exerts on the subsurface about 100m away.

### Interfering vibration sources

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/5-2Hz-line.png" alt="">
  <figcaption> Spectrogram over two hours showing 5.2 Hz signal.</figcaption>
</figure> 

Spectrogram of the recordings of a single DAS channel over a period of two hours. An irregular signal in the frequency range around 5.2 Hz can be seen, which affects the experimental operation at PETRA.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/trafo.png" alt="">
  <figcaption> Spectrogram of DAS (top) and reference signal (bottom) near a transformer station.</figcaption>
</figure> 

Frequency components of acoustic signals measured near a transformer station on the DESY site. The lower graph shows the electronically measured variation of the 50 Hz mains frequency. The upper spectrogram shows the variation over time of a one-hour section of the signal from a single position of the optical fiber near the transformer. One can see a vibration at the 5th harmonic of the mains frequency at 300 Hz, whose fluctuations exactly follow the behavior of the mains frequency.

## Projects

Ongoing projects (non-exhaustive):

* General Data Analysis
* Identification of traffic and other localized sources with Machine learning approaches
* Seismic wave propagation studies
* Newtonian Noise Cancellation in Gravitational Wave Detectors
* Seismic impact on Accelerators
* Structural Health Monitoring with DAS
* ..and more!

Do you think you can help us with these projects, or do you have ideas of your own? Please contact us!

## Vision

Over the next years, we intend to realise a seismic and geo-acoustic measurement network in and around the Science City Hamburg Bahrenfeld. WAVE will become a unique and innovative infrastructure for geophysics and physics experiments and a core asset for the Science City and its partners.

One of the long-term goals is studying the optimal placement and characteristics of seismo-acoustic sensors. On the data side of things, we will establish common data transmission and processing pipelines, as well as create data sharing and usage policies. This specifically includes the handling and storing of data according to data protection laws.

Major scientific advances are foreseen in seismology and geophysical modelling, urban systems research, real-time machine learning, and, prominently, low-latency predictions for active disturbance reduction. WAVE will also foster the development and integration of novel sensors, such as quantum-based inertial sensors, to continuously increase its capabilities.

The internationally unique infrastructure and science network will establish best practices for vibration cancellation in large-scale and precision physics experiments, bringing new frontiers of precision measurements into reach, while simultaneously providing insight into the evolution of the Science City at and beneath its surface.

