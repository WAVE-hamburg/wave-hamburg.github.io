---
permalink: /science/
title: Science
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Smart_City.png
excerpt: "Our team is actively working on diverse research projects. Physicists are involved in physics, gravitational wave detection, and accelerator projects, while geophysicists focus on ambient seismology. We also explore machine learning techniques for signal classification and prediction to advance our understanding of these fields."
toc: true
toc_label: "Page content"
toc_icon: "list"  # corresponding Font Awesome icon name (without fa prefix)
toc_sticky: true
read_time: false
---

In the following, we present a few results from the initial **Proof of Concept** measurement campaign in 2021 (12.6 km fiber track), as well as a few more recent results. Results about outreach projects such as Taylor Swift waves and soccer games are [here]({{ site.url }}{{ site.baseurl }}/outreach/). Keep an eye on this and our [blog]({{ site.url }}{{ site.baseurl }}/posts/), it will be updated (semi-) regularly!


<figure class="half">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/iDAS.jpg" alt="">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/georeferencing.jpg" alt="">
    <figcaption>DAS interrogator and fiber georeferencing.</figcaption>
</figure>

## What do the measurements of WAVE look like?

### Signals along the DAS fiber

In the following figure an Overview of whole fiber track is hown, it shows a  Waterfall diagram of the records of all DAS sensors along the 12.6 km long fiber. The maximum amplitude of the time series at 20 s intervals is color-coded across the spatially distributed sensors and the 16 hour recording period. 

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/summary_waterfall.png" alt="">
  <figcaption>Waterfall Diagram.</figcaption>
</figure> 

1. HF stations in European XFEL will be switched off for access.
2. HF stations in the European XFEL are switched on again after access.
3. Hitting the XTD9 cable tray with a hammer to determine the position.
4. Hammer hits in XTD2 against cable tray.
5. Hammer hits in XTL on concrete floor.
6. Tunnel announcement ”Interlock search”
7. Tunnel announcement ”Accelerator is switched on” (only in XTL).
8. Start of morning activity on campus.
9. Load switching operations on the power supply transformers on the DESY campus.



The following figure shows the spectra of all DAS channels along the XTL accelerator tunnel during the operation of EuXFEL. At first glance, many elements that may cause disturbances or noise can be identified by their characteristic frequencies. Some prominent elements are highlighted for illustration.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/XTL-spec-_smaller.png" alt="">
  <figcaption>Spectrogram from EuXFEL tunnel.</figcaption>
</figure> 


### Car signals

We have detected cars passing by the DAS fiber, as shown in the following figure. The fiber section between positions 10,430 and 10,800 is located immediately adjacent to a road. A map of the road section is shown at the bottom left, and at the bottom right is a recording of a single car passing, with horizontal lines framed in colors corresponding to snapshots of the fiber excitation at the bottom center.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/cars_composite.png" alt="">
  <figcaption>Car signals.</figcaption>
</figure> 

Since the fiber passes the road twice in opposite directions, the waterfall diagram is mirrored about the horizontal at a distance of 10,645 m. The cars are visible as diagonal stripes, and their slope provides immediate information about the speed of the cars, which is about 18 ± 5 km/h. The first car appears at about the 60-second mark. Another car travels in the same direction starting at the 125-second mark.

While the first car crosses paths with a slower road user traveling in the opposite direction about 15 seconds later, the second car apparently encounters three other vehicles. One of them leaves its parking place halfway, and two others approach in close succession.

The following  animation shows a car driving along the same section of fiber depicted in the figure on the left. The high amplitudes in the DAS recordings, indicated by yellow color, follow the location of the car.



<figure class="align-center">
  <video muted autoplay loop style="width: 85%; height: auto;" controls>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_car_map.mp4" type="video/mp4">
  </video>
  <figcaption>Car animation.</figcaption>
</figure>


### Earthquake signals

Now shifting focus from cars to earthquakes, the following figure illustrates an earthquake in **Qinghai, China, recorded on Maß 21, 2021** along the DAS fiber, comparing seismometer data with DAS data. The earthquake had a magnitude of 7.4. It can be seen that the amplitudes of the sum of 600 data traces in the time window in which the earthquake signal arrives are larger than those of a single trace. The amplitudes of the unwanted noise at the beginning of the data track are reduced.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/earthquake_snapshots.png" alt="">
  <figcaption> Earthquake in China recorded in Hamburg's WAVE network.</figcaption>
</figure> 

In the lower plot, many DAS data traces are plotted below each other. The blue line marks the single trace shown in the center plot. The red area covers the 600 traces from which the sum trace was formed. In the lower graph, in addition to the vertical lines corresponding to the coherent seismic wavefronts, spatial variations of the measured oscillation amplitudes can be seen. These may be related to inhomogeneous subsurface structures and illustrate how DAS measurements provide high temporal and spatial resolution.


 The following animation depicts seismic waves from a strong earthquake (magnitude 7.4) with for the same earthquake in China on May 21, 2021 traveling through the EuXFEL tunnel. On the right, a typical representation for DAS data (waterfall diagram) is shown, which color-codes the time series of strain amplitude (y-axis) for each fiber sensor (channel, x-axis). In this diagram, dark blue represents compression, and light yellow represents elongation of a fiber segment.




<figure class="align-center">
  <video muted autoplay loop style="width: 85%; height: auto;" controls>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_eq_map.mov" type="video/mov">
  </video>
  <figcaption>Animation during the Earthquake from China.</figcaption>
</figure>


On the left, the evolution of the strain amplitudes (strain rate) recorded at all DAS sensors is projected onto the fiber track along the EuXFEL tunnel. Although the length of the waves greatly exceeds that of the tunnel, the spatial shaping of the wave crests and troughs is clearly visible as they propagate from East to West.



The following animation focuses on the **2023 Turkey-Syria earthquake**, a devastating event with a magnitude of 7.5 that occurred on February 6, 2023. This recording captures the seismic activity along the EuXFEL tunnel.


<figure class="align-center">
  <video muted autoplay loop style="width: 85%; height: auto;" controls>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_EQ_turkey.mp4" type="video/mp4">
  </video>
  <figcaption>Animation during the Earthquake from Turkey.</figcaption>
</figure>

On the right, a typical representation for DAS data is shown using a waterfall diagram, which color-codes the time series of strain amplitude (y-axis) for each fiber sensor (channel, x-axis). In this diagram, dark blue indicates compression, while light yellow indicates elongation of a fiber segment, as illustrated on the waveform on the far right.

On the left, the evolution of strain amplitudes (strain rate) over time, recorded at all DAS sensors, is projected onto the fiber track along the EuXFEL tunnel.

### Vibrotruck sweeps


The Vibrotruck from Baudynamik Heiland & Mistler GmbH was used to excite a frequency sweep.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/vibrotruck.jpg" alt="">
  <figcaption> Vibrotruck.</figcaption>
</figure> 

The ground motion excited  by the Vibrotruck is evident in the vibration spectra measured in the EuXFEL accelerator tunnel, which clearly show the ground vibrations exerted on the subsurface approximately 100 meters away in the following plot.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/sweeps_signal_spectrogram.png" alt="">
  <figcaption> Spectrogram of 4 Vibrotruck sweeps in the DAS fiber.</figcaption>
</figure> 

### Interfering vibration sources

In the following plot, the spectrogram of a single DAS channel over a two-hour period is shown which reveals an irregular signal in the frequency range around 5.2 Hz, which impacts the experimental operations at PETRA.


<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/5-2Hz-line.png" alt="">
  <figcaption> Spectrogram over two hours showing 5.2 Hz signal.</figcaption>
</figure> 

The frequency components of acoustic signals were measured near a transformer station on the DESY site and is shown in the following plot.


<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/trafo.png" alt="">
  <figcaption> Spectrogram of DAS (top) and reference signal (bottom) near a transformer station.</figcaption>
</figure> 

 The lower graph displays the electronically measured variation of the 50 Hz mains frequency. The upper spectrogram shows the time variation over a one-hour period of the signal from a single position of the optical fiber near the transformer. A vibration at the 5th harmonic of the mains frequency, at 300 Hz, is visible, with fluctuations that precisely follow the behavior of the mains frequency.

## Scientific results

### **2025**

### **_Title: Towards the Clustering of Large Distributed Acoustic Sensing Datasets_** ###

**_Authors:_** Oliver Bölt, Conny Hammer, and Céline Hadziioannou

Presented at [EGU 2025 <i class="fa fa-external-link" aria-hidden="true"></i>](https://www.egu25.eu/)

**_Link:_** Download [here <i class="fa fa-external-link" aria-hidden="true"></i>](https://meetingorganizer.copernicus.org/EGU25/EGU25-17842.html )

**_Short description/Abstract:_** Distributed Acoustic Sensing (DAS) measures strain or strain rate along an optical fiber with a high spatial and temporal resolution. The typical channel distance is in the order of a few meters while the sampling frequency can reach 1 kHz or higher, which makes it possible to record a wide range of seismic signals.

The optical fibers used for DAS can be several kilometers long and measurements take place over days, weeks or months, resulting in very large datasets of up to several terabytes per day. However, due to this large amount of data, it is challenging to get a good impression of the different types of seismic signals present in the data, since a manual inspection can become immensely time-consuming.

In this study we aim to automatize this process by clustering the data to detect and categorize different types of seismic signals. A 2D continuous wavelet transform (CWT) is used to automatically extract features from the data. In contrast to many other approaches, this allows to not only use temporal information, but to also include the spatial dimension to further distinguish between different seismic sources and wave types.

The clustering is performed in two steps. First, a Gaussian Mixture Model (GMM) is used to cluster the features. Then, the final clusters are obtained by merging similar components of the GMM.

The application of the proposed procedure to different large DAS datasets provides valuable results. Identified clusters show different spatial and temporal patterns and correspond to seismic signals originating from various sources, such as car traffic, tramways or machinery.

### **_Title: Seismic Noise Contributions to EuXFEL Bunch Arrival Time Jitter from Ocean-Generated Microseism_** ###

**_Authors:_** Erik Genthe, Marie Kristin Czwalinna, Björn Lautenschlager, Holger Schlarb, Celine Hadziioannou, Oliver Gerberding, and Katharina-Sophie Isleif

Published in [High Power Laser Science and Engineering, 2025 <i class="fa fa-external-link" aria-hidden="true"></i>]( https://www.researching.cn/hpl)

**_Link:_** Download [here <i class="fa fa-external-link" aria-hidden="true"></i>](https://www.researching.cn/HiringPubPDF/HPL-2024-0173.pdf)

**_Short description/Abstract:_** Measurements of the bunch arrival times at the European XFEL show noise contributions in the spectral range between 0.05 Hz and 0.5 Hz with peak-to-peak jitter of up to 25 fs. Correlation with Distributed Acoustic Sensing (DAS) measurements confirms the seismic origin. The seismic noise in this frequency band is known to be ocean-generated microseism. Both primary and secondary ocean-generated microseism were identified using seismometers and a numerical ocean wave model. Whereas secondary microseism has a strong impact on the bunch arrival time, primary microseism has no notable effect. Rayleigh waves cause the effect, while Love waves have minimal impact. In the presented cases, the noise originates from the North Atlantic and/or the North Sea. The amplitude of the noise depends on the local weather conditions and is much stronger in winter. Ocean-generated microseism is a significant bottleneck that must be addressed to achieve femtosecond bunch arrival time stability in the sub-Hz regime.


### **2024**

### **_Title: Impact of ocean-generated microseism on the European X-ray Free Electron Laser_** ###

**_Authors:_** Erik Genthe

Presented at [AG Seismology 2024 <i class="fa fa-external-link" aria-hidden="true"></i>](https://www.conferences.uni-hamburg.de/event/396/)

**_Short description/Abstract:_** Measurements of the bunch arrival times at the European XFEL show noise contributions in the spectral range between 0.05 Hz and 0.5 Hz with peak-to-peak jitter of up to 25 fs. Correlation with Distributed Acoustic Sensing (DAS) measurements confirms the seismic origin. The seismic noise in this frequency band is known to be ocean-generated microseism.

Both primary and secondary ocean-generated microseism were identified using seismometers and a numerical ocean wave model. Whereas secondary microseism has a strong impact on the bunch arrival time, primary microseism has no notable effect. Rayleigh waves cause the effect, while Love waves have minimal impact.
In the presented cases, the noise originates from the North Atlantic and/or the North Sea. The amplitude of the noise depends on the local weather conditions and is much stronger in winter. Ocean-generated microseism is a significant bottleneck that must be addressed to achieve femtosecond bunch arrival time stability in the sub-Hz regime.

### **_Title: Exploring Unsupervised Clustering of Seismic Noise Sources in Urban DAS Data: A Methodology Guide_** ###

**_Authors:_** Antonia Kiel, Céline Hadziioannou and Conny Hammer

Presented at [EGU 2024 <i class="fa fa-external-link" aria-hidden="true"></i>](https://www.egu24.eu/)

**_Link:_** Download [here <i class="fa fa-external-link" aria-hidden="true"></i>](https://presentations.copernicus.org/EGU24/EGU24-8486_presentation.pdf)

**_Short description/Abstract:_** Since 2021 Distributed Acousic Sensing (DAS) is used to measure the strain rate along a 12 km long optical fiber at the DESY (Deutsches Elektronen-Synchrotron) campus within the WAVE initiative.

A large variety of seismic sources with different frequency characteristic can be observed in the data.

To detect different types of signals in this large dataset, different Machine Learning techniques are compared and a methodology guide is introduced, recommending which clustering technique to use in different applications.

### **_Title: Coherent and Incoherent Noise Cancellation using Distributed Optical Fiber Sensors_** ###

**_Authors:_** Reinhardt Rading, Katharina Sophie Isleif

Presented at [IEEE Photonics Society Summer Topicals 2024 <i class="fa fa-external-link" aria-hidden="true"></i>](https://2024.ieee-sum.org/)

**_Link:_** Download [here <i class="fa fa-external-link" aria-hidden="true"></i>](https://ieeexplore.ieee.org/document/10614511)

**_Short description/Abstract:_** This paper determines the sensitivity of distributed optical fiber sensors by estimating its self-noise and describing how to cancel coherent and incoherent noises, and localize sources based entirely on the sensor recordings.

## Projects

Ongoing projects (non-exhaustive):

* General Data Analysis
* Identification of traffic and other localized sources with Machine learning approaches
* Seismic wave propagation studies
* Newtonian Noise Cancellation in Gravitational Wave Detectors
* Seismic impact on Accelerators
* Structural Health Monitoring
* ..and more!

Do you think you can help us with these projects, or do you have ideas of your own? Please [contact us <i class="fa  fa-envelope-square" aria-hidden="true"></i>](mailto:celine.hadziioannou@uni-hamburg.de)!

## Vision

Over the next years, we intend to realise a seismic and geo-acoustic measurement network in and around the Science City Hamburg Bahrenfeld. WAVE will become a unique and innovative infrastructure for geophysics and physics experiments and a core asset for the Science City and its partners.

One of the long-term goals is studying the optimal placement and characteristics of seismo-acoustic sensors. On the data side of things, we will establish common data transmission and processing pipelines, as well as create data sharing and usage policies. This specifically includes the handling and storing of data according to data protection laws.

Major scientific advances are foreseen in seismology and geophysical modelling, urban systems research, real-time machine learning, and, prominently, low-latency predictions for active disturbance reduction. WAVE will also foster the development and integration of novel sensors, such as quantum-based inertial sensors, to continuously increase its capabilities.

The internationally unique infrastructure and science network will establish best practices for vibration cancellation in large-scale and precision physics experiments, bringing new frontiers of precision measurements into reach, while simultaneously providing insight into the evolution of the Science City at and beneath its surface.

## Workshops

### First WAVE workshop.
The first WAVE workshop took place as a hybrid event on Friday the 13th of May 2022, from 9:00 to 14:30.

In the workshop we have:

* Presented the results of the demonstration experiment/campaign
* Learned about the use of machine learning for the seismic network (Talk by Prof. Conny Hammer, UHH)
* Discussed the future steps in designing and realising the network
* Exchanged information about ongoing research and activities related to the seismic network
* The workshop schedule is detailed [here <i class="fa fa-external-link" aria-hidden="true"></i>](https://indico.desy.de/event/34125/timetable/#20220513). If you would like to have a look at the workshop material, please [contact us <i class="fa fa-envelope" aria-hidden="true"></i>](mailto:celine.hadziioannou@uni-hamburg.de).

### Second WAVE workshop.
WAVE day: on July 13, 2023 at DESY we had an in-person WAVE meeting, focused on presentations of recent results and discussions about research projects. The workshop schedule is detailed [here <i class="fa fa-external-link" aria-hidden="true"></i>](https://www.conferences.uni-hamburg.de/event/380/timetable/#20230713).
