---
permalink: /wave/
title: About WAVE
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Smart_City.png
excerpt: "WAVE is a seismic sensor network at the Campus Hamburg Bahrenfeld that transforms 19 km of unused telecommunication fibers into 19,000 seismic sensors using distributed acoustic sensing (DAS), expanding research possibilities in geophysics and physics while engaging the community through events and live data streams."
toc: true
toc_label: "Page content"
toc_icon: "list"  # corresponding Font Awesome icon name (without fa prefix)
toc_sticky: true
read_time: false
---

The [WAVE initiative <i class="fa fa-external-link" aria-hidden="true"></i>
](https://indico.desy.de/event/28485/) investigates and designs a seismic and geo-acoustic measurement network in and around and around the Science City Hamburg Bahrenfeld. WAVE is a unique and innovative infrastructure for geophysics, physics and especially for large-scale research facilities.

In a first step, the WAVE concept has already been tested under realistic conditions to demonstrate the feasibility and possibilities of such a network on site. To this end, the initiative carried out a proof-of-concept experiment on the DESY/UHH campus in Bahrenfeld in May 2021, using, among other things, a 12.6 km long, existing and continuous strand of currently unused telecommunications fiber as a series of seismic sensors. The wave field was recorded at high resolution, with 1 m intervals along the entire length of the fiber. In the following, we summarize the development of this measurement campaign, and present a selection of initial observations. 

Since then, we have expanded the network to currently 19 km of fiber, organized several [outreach]({{ "/outreach" | relative_url }}) and [Livestreams]({{ "/outreach/#livestreams" | relative_url }}) of the data, including during a [Taylor Swift Concert]({{ "/outreach/#taylor-swift" | relative_url }}). We hold regular Workshops and other events, and of course we also use the data for a range of interdisciplinary [scientific analysis]({{ "/science/#results" | relative_url }})!

## Map of the DAS-fiber track

In 2021 we started with a 12.6 km fiber test track and performed the proof-of-concept experiment. Now, we established a 19 km fiber paths providing us 19000 distributed seismic sensors on the Campus, reading out with a single DAS interrogator. 
The current fiber track is shown in the following map in yellow and contains
* 2 times 3.4 km EuXFEL tunnel some meters below the surface
* 1 times the PETRA ring, where the fiber goes partly through buildings, in tunnels and on cable trays
* one Campus loop 

In the northeast, the fiber runs through the 'Max von Laue' experimental hall and briefly follows the circular path of PETRA there. Zoom in for more detail.

<iframe width='100%' height='400px' src="https://api.mapbox.com/styles/v1/hadzii/ckzrg6q3r00pe14l9dhyemxx7.html?title=false&access_token=pk.eyJ1IjoiaGFkemlpIiwiYSI6ImNrdmF0cW92dTNibnQyb2xwM2c2Mzd6czgifQ.oLTcVRE0U4q1GuobdEevIQ&zoomwheel=false#10/53.5732/9.9245" title="WAVE-Hamburg" style="border:none;"></iframe>

## Georeferencing: Find the fiber!

Our approach involves using existing dark telecommunication fibers on campus, rather than laying new ones. This means we are working with unknown fiber paths and simply connecting the ends to form a continuous loop. The challenge lies in determining the exact geographical positions of these fibers, as their routes are not pre-determined or mapped. Additionally, some fibers may be coiled or have unexpected paths, adding to the complexity.

To address this, we use a method that involves striking the ground with a hammer to create vibrations. These vibrations are detected by our system, which works in combination with a GPS positioning system. By exciting the ground at specific GPS locations and times, we can identify these events in the data and pinpoint where the fibers are located. 

<figure class="half">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/iDAS.jpg" alt="DAS Interrogator">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/georeferencing.jpg" alt="Fiber Georeferencing">
  <figcaption>DAS interrogator and fiber georeferencing.</figcaption>
</figure>

With this technique, we can produce the detailed [geoplots <i class="fa fa-file-text" aria-hidden="true"></i>]({{ site.url }}{{ site.baseurl }}/posts/#geoplots) featured in our outreach materials and [blog <i class="fa fa-file-text" aria-hidden="true"></i>]({{ site.url }}{{ site.baseurl }}/posts/). The following animation shows a geoplot, where seismic waves from an Earthquake in China propagating along the EuXFEL tunnel. 

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/animations/anim_eq_map.mov" alt="">
  <figcaption>Animation during the Earthquake from China.</figcaption>
</figure> 

On the right, a typical representation for DAS data ([waterfall diagram]({{ site.url }}{{ site.baseurl }}/outreach/#waterfall-what-am-i-looking-at)) is shown, which color-codes the time series of strain amplitude (y-axis) for each fiber sensor (channel, x-axis). Here, the dark blue color represents compression and light yellow represents elongation of a fiber segment.
On the left, the evolution over time of the strain amplitudes (strain rate) recorded at all DAS sensors is projected onto the fiber track along the EuXFEL tunnel.

During the [Science City Day]({{ site.url }}{{ site.baseurl }}/outreach/#wave-field-and-science-city-day) at Campus Bahrenfeld, we actually offered the game "Find the Fiber." We set up a playground with a few hundred meters of fiber hidden beneath rubber mats. Visitors had to locate the fiber by walking or jumping on the checkerboard pattern of mats. At that time in June 2024, we didn't have a geoplot available for this playground, so visitors learned how to read a [waterfall diagram]({{ site.url }}{{ site.baseurl }}/outreach/#waterfall-what-am-i-looking-at) instead.

<figure class="half">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/WAVE-field.jpeg" alt="DAS Interrogator">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/WAVE-field-monitor.jpeg" alt="screen">
  <figcaption>Photo from the WAVE-field an a live view of the waterfall diagram.</figcaption>
</figure>

More scientific results and experiments with the WAVE network are [here]({{ site.url }}{{ site.baseurl }}/science/#results). 

## Other seismic sensors

In addition to seismic sensors, we also have other seismic sensors on campus from the various institutions whose data we can access. These include broadband seismometers with high sensitivity, even over long measurement periods, and geophones, which are more capable of measuring signals in the high-frequency range.  

## Where is WAVE headed?

Over the next years, we intend to realise a seismic and geo-acoustic measurement network in and around the Science City Hamburg Bahrenfeld. WAVE will become a unique and innovative infrastructure for geophysics and physics experiments and a core asset for the Science City and its partners.

![WAVE stages]({{ site.url }}{{ site.baseurl }}/assets/images/WAVE_evolution_stages.png)
{: .image-right}

One of the long-term goals is studying the optimal placement and characteristics of seismo-acoustic sensors. On the data side of things, we will establish common data transmission and processing pipelines, as well as create data sharing and usage policies. This specifically includes the handling and storing of data according to data protection laws.

Major scientific advances are foreseen in seismology and geophysical modelling, urban systems research, real-time machine learning, and, prominently, low-latency predictions for active disturbance reduction. WAVE will also foster the development and integration of novel sensors, such as quantum-based inertial sensors, to continuously increase its capabilities.

The internationally unique infrastructure and science network will establish best practices for vibration cancellation in large-scale and precision physics experiments, bringing new frontiers of precision measurements into reach, while simultaneously providing insight into the evolution of the Science City at and beneath its surface.

## Contact

Have we peaked your interest? Would you like to contribute? If you wish to contribute, or get an impression of what we work on, please [contact Prof. Celine Hadziioannou <i class="fa  fa-envelope-square" aria-hidden="true"></i>](mailto:celine.hadziioannou@uni-hamburg.de). 

