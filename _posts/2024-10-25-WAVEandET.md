---
title: "WAVE and the Einstein Telescope"
permalink: /ET/
categories:
  - news
tags:
  - science
  - gravitational waves
last_modified_at: 2024-10-25
header:
  teaser: /assets/images/ET_sketch.png
---


What does WAVE have to do with gravitational wave detection? Why are seismic sensor networks so important, especially for the next generation of gravitational wave detectors like the [Einstein Telescope (ET)](https://www.et-gw.eu/)? And what exactly are gravitational waves, and why are scientists so eager to detect them?

Let’s delve deeper into the world of gravitational wave detection and its connection to the WAVE project!

## Gravitational Waves

When massive celestial bodies like black holes merge, they spiral around each other, drawing closer and spinning faster. This motion releases gravitational waves—ripples in spacetime itself. These waves stretch and compress spacetime, though by incredibly tiny amounts. For instance, if a gravitational wave passed between Earth and the Sun, the 150-million-kilometer distance would change by less than an angstrom, smaller than an atom!

Despite these tiny distortions, gravitational waves reveal details about the universe’s most energetic events. The first detection, GW150914, in 2015 by Laser Interferometer Gravitational-Wave Observatory [LIGO](https://www.ligo.caltech.edu/), captured a black hole merger 1.4 billion light-years away, confirming Einstein’s theory and marking a new era in astronomy. Gravitational waves also come from neutron star collisions, like the 2017 GW170817 event, where scientists observed both gravitational waves and light, launching multi-messenger astronomy. Nearly 400 gravitational wave events have been detected so far.

Unlike electromagnetic telescopes that *see* the universe, gravitational wave detectors let us *hear* it. But detecting these waves is challenging because they are really really tiny, requiring incredibly sensitive instruments.

![Michelson Interferometer Image]({{ site.url }}{{ site.baseurl }}/assets/images/MI_pic_ENG.png) Credit: K.-S. Isleif

Gravitational wave detectors, like [LIGO](https://www.ligo.caltech.edu/), measure tiny distance changes between two suspended mirrors (which we call test masses), 4 km apart, using a laser interferometer. These mirrors are suspended on ultra-thin strings to simulate free-fall and isolate them from ground vibrations, reducing seismic noise interference. The mirrors, acting as test masses for gravitational waves, perfectly reflect laser light, allowing precise measurement of light travel time in two perpendicular directions.
When a gravitational wave passes, it stretches one interferometer arm while compressing the other, causing a shift in optical power that’s detected by a photodiode, revealing the gravitational wave signal. 

We need to detect very small position changes down to 1e-18 meters, so the test masses must stay almost perfectly still. However, many noise sources, from ground vibrations to local gravitational fluctuations (*"Newtonian noise"*), can disturb the masses. Even nearby footsteps can create slight gravitational pulls! Reducing this Newtonian noise is key to enhancing gravitational wave detection.


## Seismic noise
Seismic waves can result from tectonic shifts, human activity, ocean waves, and many other sources. They can produce noise in the gravitational wave detector by shaking it and moving the test masses. You can learn more about seismic waves [here](https://wave-hamburg.eu/media/Insta-0-seismic/). 

![Summary Image]({{ site.url }}{{ site.baseurl }}/assets/images/ET_env_noise_ENG.png) Credit: K.-S. Isleif

To suppress seismic noise, we make the suspensions of the mirrors super long, and combine several stages, so we actually have a multistage-pendulum, on which shiny mirrors are hanging.  This is what we call passive isolation system. 
But this is not enough, and, additionally, the suspensions produce resonance frequencies (you know these frequencies when [bridges can be destroyed](https://www.youtube.com/watch?v=XggxeuFDaDU)), which needs to be damped, actively. 
Active noise cancellation involves measuring the noise from the ground or the system, and then either adjusting components in the detector (such as the suspensions) to counteract this noise during operation, or to remove the noise during the data analysis. For this we use, again, laser interferometers! Yes, we have small laser interferometer to improve the big laser interferometer gravitational wave detector.. But we also use seismic instruments like geophones and seismometers.

**And this is where WAVE comes in!**

Could Distributed Acoustic Sensing (DAS) help? Is a large seismic sensor network like WAVE beneficial for gravitational wave detectors? And can we even address the challenging issue of non-shieldable Newtonian noise, a problem yet to be solved in the future Einstein Telescope? These are the exciting questions that WAVE scientists are exploring!

## Newtonian noise

As we aim to improve the sensitivity of gravitational wave detectors, such as the [Einstein Telescope (ET)](https://www.et-gw.eu/), Newtonian noise, caused, for example, by seismic noise, will limit the sensitivity and thus the detection of cool cosmological events which are even heavier or further away than those detected so far. Seismic waves cause tiny fluctuations in ground density, effectively mass changes, which in turn alter the local gravitational force. These fluctuations near a sensitive detector can interfere with its ability to detect gravitational waves, making Newtonian noise a significant challenge.
![WAVE in ET Image]({{ site.url }}{{ site.baseurl }}/assets/images/NN.png) Credit: K.-S. Isleif

Suspensions can’t block Newtonian noise because it’s a gravitational force, and gravity can’t be shielded. To suppress it, we need new strategies. One idea is to measure Newtonian noise and subtract it from the gravitational wave signal. But Newtonian noise is incredibly faint, making it difficult to detect. While some scientists are developing Newtonian noise sensors, these are as complex to build as gravitational wave detectors. In fact, a gravitational wave detector is itself a Newtonian noise sensor!

Instead of measuring Newtonian noise directly, we can track its source — seismic waves!

**That's one reason for building the WAVE network!**

The goal is to capture the full seismic wave field—often quite complex—and use this data to predict Newtonian noise through a smart algorithm or machine learning. Since the density of the ground affects how seismic waves create Newtonian noise, precise, site-specific measurements are crucial. This approach needs extensive data to accurately capture the complex seismic wave field and predict Newtonian noise, especially for sensitive detectors like the Einstein Telescope. To gather this data, Distributed Acoustic Sensing (DAS) can be used, providing thousands of sensors to create a detailed seismic picture.

## WAVE

Since DAS uses optical fibers, it functions like an array of thousands of seismic sensors spaced every meter along kilometers of fiber. By wrapping the fiber around the vacuum chambers and beam path of the detector, it can precisely map environmental vibration, creating detailed profiles that show noise levels throughout the detector. This detailed mapping enables *noise hunting*, allowing us to improve noise cancellation not only for seismic and Newtonian noise but maybe even for unexpected noise sources we may not yet fully understand. DAS could reveal unknown noise origins, offering new insights and enhancing the overall sensitivity of the detector. 

![Seismic Waves Image]({{ site.url }}{{ site.baseurl }}/assets/images/ET_env_noise_with_fiber_ENG.png) Credit: K.-S. Isleif

While DAS has not been implemented in a gravitational wave detector to date, there are plans to implement it especially in future generation detectors such as the Einstein Telescope, which is a planned detector in Europe. 


## Some additional information 

### Einstein Telescope (ET)
The Einstein Telescope [ET](https://www.et-gw.eu/) will be Europe’s next-generation gravitational wave detector, designed to improve sensitivity by 1 order of magnitude compared to current detectors like LIGO and reach lower frequencies (1-10 Hz), where seismic and Newtonian noise must be suppressed by even one million! Its development will involve a major multinational effort over the next decade, with members of the WAVE team contributing strategies and sensors for seismic and Newtonian noise cancellation.

![Einstein Telescope Image]({{ site.url }}{{ site.baseurl }}/assets/images/ET_sketch.png) Credit: K.-S. Isleif

ET will be larger, with 10 km long interferometer arms, increasing sensitivity to detect smaller gravitational waves. It will also feature three overlapping interferometers arranged in an isosceles triangle, with each side containing two arms, thus multiple detectors in one experiment. 

Additionally, the Einstein Telescope [ET](https://www.et-gw.eu/) will be built 200-300 meters underground to reduce seismic and ambient noise, crucial for low-frequency detection. However, large seismic sensor arrays, like those achieved through Distributed Acoustic Sensing (DAS) by simply deploying fibers, are being investigated by WAVE. We are exploring how to optimally use this wealth of data to map and cancel both seismic and Newtonian noise in the ET.


### More Gravitational Wave Detectors - current and planned

There are multiple gravitational wave detectors which are already in operation, while even more are being planned. The detectors currently in operation are the Laser Interferometer Gravitational-Wave Observatory [LIGO](https://www.ligo.caltech.edu/) in the USA, [KAGRA](https://gwcenter.icrr.u-tokyo.ac.jp/en/) in Japan and [VIRGO](https://www.virgo-gw.eu/) in Italy. For a future generation of detectors, there are plans to build the Einstein Telescope [ET](https://www.et-gw.eu/) in Europe and Cosmic Explorer [CE](https://cosmicexplorer.org/) in the USA. While they all rely on the Michelson interferometer topology, the detectors vary both in size and sensitivity. LIGO has armlengths of about 4 km, while Virgo has 3 km. 

In addition to the earthbound detectors, there will be a gravitational wave detector which will operate in space, the Laser Interferometer Space Antenna [LISA](https://www.lisamission.org/). This detector will have three satellites and have a different interferometry scheme and will have arm lengths of 2.5 Million kilometers! The satelites will trail behind earth while sending laser beams inbetween them in a giant triangle. This will enable the detection of low frequency gravitational waves. These waves come from older parts of the universe. The planned launch date for the LISA mission is in 2035.


<!---
## Gravitational Waves and their Detection
When large celestial bodies, such as black holes, merge, they spiral around each other beforehand, getting closer to each other and turning faster and faster. During this process, energy is released in the form of gravitational waves, which can be described as ripples in spacetime. These ripples travel at the speed of light and stretch and bend space time. While gravitational waves were predicted by Alrbert Einstein, the first direct detection of a gravitational wave was in 2015. The wave originated from a black hole merger which occured around 1.4 billion lightyears from the earth. Since then, around 400 gravitational waves have been detected. Analysing these waves gives us new insights into the universe and will enable multi messenger astronomy. While other space telescopes, such as the James Webb telescope use electromagnetic radiation (light) as their source of information, gravitational wave detectors use gravity. As this information comes from different forces, they compliment each other, similar to seeing and hearing. 

As the amplitude, or strength, of these waves is very small at fractions of an atomic length, coming in at around  $1 \times 10^{-21}$ m. Due to the ripples being so tiny, the detectors that are used for this need to be both able to be both extremely sensitive and very stable. This stability is impacted by miniscule changes, such as small seismic waves which occur naturally in the crust of the earth.

Gravitational wave detectors work on the basis of laser interferometers. These are high precision instruments which measures relative length changes. The most common interferometer topology is the so-called michelson interferometer. In this, light from a laser is split into two equal parts, which follow different paths, commonly knwn as interferometer arms. Using mirrors, also known as test masses, the light is then reflected at the end of the arms being sent back to the splitter. Here, the light from both arms is overlapped. This overlap is called the interference, which is measured.

![Michelson Interferometer Image](MI_pic.jpg) Credit: K.-S. Isleif

When the interferometer experiences arm length changes due to a gravitational wave which passes through it, the output of the interferometer can measure this change.  In order to ensure that the length change is sufficiently large to be detected, gravitational wave detectors have arm lengths of several kilometres. However, these large interferometers are subject to multiple noise sources, which cause the components to move around, obscuring the signal. The solution for this is to implement multiple stages of active and passive noise cancellation, where additional sensors are employed in order to keep the individual components stable. 

![Summary Image](ET_env_noise.png) Credit: K.-S. Isleif

Two of the noise sources which affect gravitational waves are seismic and Newtonian noise. Seismic noise is defined as seismic waves which propagate through the earth. This can be due to the shifting of tectonic plates, human activity, tidal movement or a multitude of other reasons. More about seismic weaves can be found [here](https://wave-hamburg.eu/media/Insta-0-seismic/). Newtonian noise describes the local changes in the gravitational field of the earth which are constantly taking place. This is due to density fluctuations in the ground. Both of these noise sources couple into the detector acting on the suspended mirrors. Unless adressed, this will reduce the sensitivity of the detectors.

![WAVE in ET Image](NN.png) Credit: K.-S. Isleif

The approaches to noise suppression can be put into the categories of passive and active noise mitigation. Passive noise mitigation describe the parts of the detector design which reduce the amount of noise even reaching the components. An example of this is the fact that the optical components, such as the mirrors at the end of the interferometer arms,are suspended. These suspensions have a height of multiple meters and incorporate multiple stages. This decouples some of the ground motion from the test masses. Another example is using platforms with springs which also dampen the ground motion. 

Active noise cancellation involves measuring the noise from the ground or the system and then either adjusting components in the detector (such as the suspensions) to even it out while running or to remove the measured movement when analysing the data. 

One of the approaches for active noise mititgation in using Distributed Acoustic Sensing, which is the sensor we use in the WAVE project. As DAS uses optical fibres, it behaves as many sensors in a continuous line. By potentially wrapping the fiber around the vacuum chambers and the beam path, the environmental noise can be accurately depicted by creating arrays which show the noise thourghout the detector. This can enable a targeted response in the different parts of the detector.

![Seismic Waves Image](ET_env_noise_with_fiber.png) Credit: K.-S. Isleif

While DAS has not been implemented in a gravitational wave detector to date, there are plans to implement it especially in future generation detectors such as the Einstein Telescope, which is a planned detector in Europe. 

## Gravitational Wave Detectors today
There are multiple gravitational wave detectors which are already in opertation, while even more are being planned. The detectors currently in operation are the Laser Interferometer Gravitational-Wave Observatory [LIGO](https://www.ligo.caltech.edu/) in the USA, [KAGRA](https://gwcenter.icrr.u-tokyo.ac.jp/en/) in Japan and [VIRGO](https://www.virgo-gw.eu/) in Italy. For a future generation of detectors, there are plans to build the Einstein Telescope [ET](https://www.et-gw.eu/) in Europe and Cosmic Explorer [CE](https://cosmicexplorer.org/) in the USA.These detectors vary both in size and sensitivity.  

In addition to the earthbound detectors, there will a gravitational wave detector which will operate in space, the Laser Interferometer Space Antenna [LISA](https://www.lisamission.org/). This detector will have threee satelites and have a different interferometry scheme and will have arm lengths of $2.5 \times 10^{6}  m$. 

## Einstein Telescope (ET)
![Einstein Telescope Image](ET_sketch.png) Credit: K.-S. Isleif

The Einstein Telescope will be a new gravitational wave detector in Europe with the goal of gaining about seven orders of magnitude of sensitivity compared to current gravitational wave detectors as well as reaching lower frequencies in the band from 1-10 Hz. Developig and building the ET will be large, multinational effort which will span the next decade. However, parts of the setup of the detector which will ensure the gain in senstivity  have been decided. 

Firstly, the ET will have arm lengths of 10 km. The lengths of the arms is one of the factor which determines how sensitive a detector is. A longer armlength gives a larger relative arm length change, making it possible to detect smaller gravitational waves. 

Secondly, the ET will consist of three itnerferometers which will overlap each other. ET will be built in the shape of an isosceles triangle, where each side will include two interferometer arm. The start and end points of the three interferometers will be at the corners of the triangle, with readout ports and mirrors of which the laser is reflected of. The interferometers will be equal to each other. Using multiple measurement intrsuments is a well know technique to ensure that noise is eliminated. 

Thirdly, the ET will be built below ground, at a depth of 200 - 300 m. Going this far below the surface reduces both the seismic and the ambient noise which the detector experiences. As seismic noise is very prevalent in the lower frequency band targeted by ET, reducing the amount of it experienced by the detector is a vital step in ensuring sensitivity. 
 
However, there will still be a need for additional seismic sensors within the detector to actuate and measure the seismic activity. One of these sensors will be Distributed Acoustic Sensing. 

In order for the ET to be successfull endeveour, both seismic and Newtonian noise needs to be further suppressed by sensors.
The WAVE collaboration is currently investigating Distributed Acoustic Sensing as a future sensor for the cancellation of seismic and Newtonian noise in the Einstein Telescope.

When seismic waves go through a gravitational wave detector, they can move the mirrors of the interferometer. In the output, it's impossible to distinguish between a length change in the arm and a movement of the mirror itself. Therefore, dampening this movement or knowing which movement is due to seismic activity rather than gravitational waves it imperative. 

We plan on using the technology of WAVE, distributed acoustic sensing (DAS) to measure this seismic activity





The basic design used in most detectors is a Michelson interferometer. A laser beam is split into two equal parts, each traveling down a separate arm of the interferometer, where mirrors reflect them back. When the two beams are recombined, any difference in their travel distance—caused by passing gravitational waves—creates an interference pattern. This interference pattern reveals tiny variations in arm length caused by spacetime distortions.
Gravitational wave detectors work on the basis of laser interferometers. These are high precision instruments which measures relative length changes. The most common interferometer topology is the Michelson interferometer. Here, light from a laser is split into two equal parts, which follow different paths, commonly known as interferometer arms. Using mirrors, also known as test masses, the light is then reflected at the end of the arms being sent back to the splitter. Here, the light from both arms is overlapped. This overlap is the sum of both arms and is called the interference. This interference is then measured. 
When the interferometer experiences arm length changes due to a gravitational wave which passes through it, the output of the interferometer can measure this change.  In order to ensure that the length change is sufficiently large to be detected, gravitational wave detectors have arm lengths of several kilometres. However, these large interferometers are subject to multiple noise sources, which cause the components to move around, obscuring the signal. The solution for this is to implement multiple stages of active and passive noise cancellation, where additional sensors are employed in order to keep the individual components stable. 



The approaches to noise suppression can be put into the categories of passive and active noise mitigation. Passive noise mitigation describes the parts of the detector design which reduce the amount of noise reaching the components. An example of this is the fact that the optical components, such as the mirrors at the end of the interferometer arms, are suspended. These suspensions have a height of multiple meters and incorporate multiple stages. This decouples some of the ground motion from the test masses. Another example is using platforms with springs which also dampen the ground motion. 
--->
