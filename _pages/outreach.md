---
permalink: /outreach/
title: Outreach
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Smart_City.png
  actions:
    - label: "Twitch"
      url: https://www.twitch.tv/wave_hamburg
excerpt: "We are streaming WAVE data live. Follow us on Twitch."
toc: true
toc_label: "Page content"
toc_icon: "list"  # corresponding Font Awesome icon name (without fa prefix)
toc_sticky: true
read_time: false
tags:
  - outreach
---

## Livestreams 


<html>
  <body>
    <!-- Add a placeholder for the Twitch embed -->
    <div id="twitch-embed"></div>

    <!-- Load the Twitch embed JavaScript file -->
    <script src="https://embed.twitch.tv/embed/v1.js"></script>

    <!-- Create a Twitch.Embed object that will render within the "twitch-embed" element -->
    <script type="text/javascript">
      new Twitch.Embed("twitch-embed", {
        width: 800,
        height: 365,
        channel: "wave_hamburg",
        // Only needed if this page is going to be embedded on other websites
        parent: ["embed.example.com", "othersite.example.com"]
      });
    </script>
  </body>
</html>


![Screenshot]({{ site.url }}{{ site.baseurl }}/assets/images/Campusday_twitch_QR Kopie.png){: .align-left} If you cannot see the embedded video, try going [here <i class="fab fa-twitch" aria-hidden="true"></i>](https://m.twitch.tv/wave_hamburg) or scan the QR code.

A map of the WAVE network and the event locations is shown in following figure.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/WAVEmap_annotations.png" alt="Maps annotation">
</figure> 


### Upcoming Events {#upcoming}

| When | Type  | What | Where | Stream start | 
| --- | --- | -------------| -----------------------| ----- | 
| **30.08.2024** | <i class="fa fa-music" aria-hidden="true"></i> | *Deichkind*  | Trabrennbahn | |
| **04.09.2024** | <i class="fa fa-music" aria-hidden="true"></i> | *Justin Timberlake* | Barclays arena | |
| **13.09.2024** | <i class="fa fa-music" aria-hidden="true"></i> | *Scorpions* | Barclays arena  | |


### Passed {#passed}

| When | Type  | What | Where | Link | 
| --- | --- | -------------| -----------------------| ----- | 
| **10.08.2024** | <i class="fa fa-futbol" aria-hidden="true"></i> | *Soccer*  | Volksparkstadion  |  |
| **23.07.2024** | <i class="fa fa-music" aria-hidden="true"></i> | *Taylor Swift*  | Volksparkstadion | [summary]({{ site.url }}{{ site.baseurl }}/outreach/#taylor-swift); [posts <i class="fa fa-file-text" aria-hidden="true"></i>](https://wave-hamburg.eu/tags/#taylorswift) |
| **24.07.2024** | <i class="fa fa-music" aria-hidden="true"></i> | *Taylor Swift*  | Volksparkstadion | [summary]({{ site.url }}{{ site.baseurl }}/outreach/#taylor-swift); [posts <i class="fa fa-file-text" aria-hidden="true"></i>](https://wave-hamburg.eu/tags/#taylorswift)  |
| **05.07.2024** | <i class="fa fa-futbol" aria-hidden="true"></i> | *EM24 Portgual-Frankreich*  | Volksparkstadion  | [summary]({{ site.url }}{{ site.baseurl }}/outreach/#public-hearing-em24) |



### What am I looking at?? {#what-am-i-looking-at}

Over the past time of livestreams we investigated different settings and visualisations of the live streams. An overview of all livestream waterfall diagrams can be found [here]({{ site.url }}{{ site.baseurl }}/news/OverviewTwitchStreamsWaterfalls.md).

The WAVE fiber network spans 19 km and allows us to measure campus vibrations, or 'wiggles,' every 10 meters when events occur, visualized in a waterfall diagram. Our latest real-time viewer of the waterfall diagram is integrated into our Twitch livestream. The following clip was recorded during a soccer game on August 10, 2024, and captures signals from the Volksparkstadion arriving on campus as drums and crowd stomping echoed through the stadium.

<iframe src="https://clips.twitch.tv/embed?clip=AwkwardIronicDinosaurBleedPurple-LF8cjTdah4hKfCY9&parent=wave-hamburg.eu/outreach/" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="700">
</iframe>


Each vertical line in the image indicates how much a specific section of the fiber is vibrating. Yellow represents strong vibrations, while green indicates quieter areas.

Starting from the left, you can see the vibrations currently detected in DESY's PETRA tunnel. Since the tunnel is a few meters underground, vibrations from car traffic, wind, and other surface activities are minimal, resulting in mostly green areas. The same is true for the XFEL tunnel, which also appears 'quiet' and green.

As you move further to the right in the waterfall diagram, the fiber approaches the surface and roads on the DESY/Bahrenfeld campus. Here, car traffic, swaying trees, and urban activity create more vibrations, causing these sections of the fiber to show yellow.

The entire image scrolls upward to represent the passage of time.

**These are tiny vibrations!** Although you wouldn't feel them, our measurement device is extremely sensitive.

You’ve probably felt the ground shake when a big truck passes by. It’s the same effect, just much weaker, and results from numerous trucks, cars, swaying trees, and other surface activities happening simultaneously.

On the left of the video clip, you can see a geoplot where the fiber track is georeferenced onto the campus map, showing vibrations at specific geopositions. Each bubble represents a different frequency window: slow vibrations on the campus are depicted at low frequencies, such as 4 Hz, while faster vibrations, like those from acoustics or pumps, are shown at higher frequencies. The size of each bubble indicates the signal strength.

### Taylor Swift

With our WAVE glass fiber sensor network, we listen to vibrations underground with a thousand ears. On July 23rd and 24th 2024, Taylor Swift performed at the Volksparkstadion Hamburg, just 2 km from our experiment!

During the two concerts, we offered a livestream of our vibration measurements.
We broadcasted our measurements on the Livestream on 23th of July at 18:00 -- 23:00 CEST
and again on 24th of July at 18:00 -- 23:00 CEST.
Watch this space, we will update with more results over the next few days.
"Swiftquakes?!" Don't worry, these are not real earthquakes!

These are tiny vibrations! You would not feel them, our measurement device is really sensitive..
You've probably felt the ground shaking a bit when a big truck passes nearby? It's the same effect, just caused by lots of happy people dancing.

We already knew that we should able to pick up vibrations of concerts happening in the Volksparkstadion, since we have already picked concerts e.g. by Metallica in the past. Lots and lots of fans jumping and dancing at the same time will cause the ground to "swing along" a bit.

![Screenshot]({{ site.url }}{{ site.baseurl }}/assets/images/2024_taylors_waves_livestream_shakeitoff_credit.png)
{: .image-right}

#### Spectrogram

From the waterfall plot, shown on the left in the Livestream, we calculated a 
[spectrogram <i class="fa fa-file-text" aria-hidden="true"></i>]({{ site.url }}{{ site.baseurl }}/results/TaylorSwiftResults1/) of the Taylor Swift concert, with some songs annotated. 

![Screenshot]({{ site.url }}{{ site.baseurl }}/assets/images/2024_taylors_waves_spectrogram_annotated.png)

The brighter yellow colors indicate stronger vibrations. The 'ladder structures' shift up and down with the beats per second of the song -- this is probably a result of the fans jumping to the beat, and with that, they generate specific frequencies.

#### PETRA's heartbeats

On the right in the Livestream we showed for the first time DAS data on a map along the PETRA ring. With this visualisation, we are able to show [PETRA's heartbeat during the Taylor Swift concert in Hamburg live! <i class="fa fa-file-text" aria-hidden="true"></i>]({{ site.url }}{{ site.baseurl }}/media/TaylorSwiftHeartbeats/).

<iframe width="560" height="315" src="https://www.youtube.com/embed/norXqxITPoc?si=xr4ncOx6BKgFqiPT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The ‘rainbow blobs’ show the strength of the arriving signals along the fiber but filtered for different frequency bands. So the wider a specific colour band is, the stronger are the waves vibrating in that range. They also help understand from what direction the signal is coming and help us observe along what path the waves are traveling.
This is what we measured during the entire concert with a ring of optical fiber around the PETRA III accelerator ring of DESY, sped up 100 times. 

#### *Shake it Off* - along the EuXFEL

We animated the seismic signals also along the full fiber track, including the EuXFEL which goes 3.4 km until Schenefeld.
You see that the [seismic waves from Love Story and Shake it Off <i class="fa fa-file-text" aria-hidden="true"></i>]({{ site.url }}{{ site.baseurl }}/media/TaylorSwiftWaveinEuXFEL/) reached all the way through the 3.4km long EuXFEL tunnel! These two songs were chosen for the animation as they produced one of the strongest signals in the DAS system.

<iframe width="560" height="315" src="https://www.youtube.com/embed/jO0U1UXkDII?si=ijcdmTCG8y7NT-PG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



For more results of the Taylor Swift concert and some explanations, check also our [blog <i class="fa fa-file-text" aria-hidden="true"></i>]({{ site.url }}{{ site.baseurl }}/posts/#taylorswift)!


### Public hearing EM24 

Can We Hear the Goals from the Euros Underground?
With our WAVE fiber-optic network, we listen to underground vibrations with a thousand ears. On July 5th, 2024, during the quarter-finals between France and Portugal at the Volksparkstadion Hamburg—just 2 km from our experiment—we livestreamed our vibration measurements throughout the match. When goals were scored, the celebrations created vibrations that we could detect! This was an exciting opportunity to test the sensitivity of our setup and see if we could capture these vibrations within the fiber network.

![Screenshot]({{ site.url }}{{ site.baseurl }}/assets/images/20240705_WAVE_EM_Livestream.png)
{: .image-right}

**What happened when a goal was scored?**

Before this football match, we already knew that we should able to pick up vibrations of concerts happening in the Volksparkstadion, since we have already picked up a concert by Metallica in the past. Lots and lots of fans jumping and dancing at the same time will cause the ground to vibrate a bit.

We expected that the fans in the stadion will celebrate and jump around when a goal is scored. Indeed, we were able to pick up the football fans getting excited and jumping around during the penalty shooting. We will upload some images here soon!


## WAVE Field and Science City Day

On Saturday, June 1, 2024, from 11:00 AM to 7:00 PM, the WAVE team participated in Science City Day at the DESY campus. Visitors explored the fascinating world of our fiber-optic seismic network, discovering where the fiber was buried and learning how it works. Attendees had the chance to generate their own seismic waves and find out what happens when you jump around on a bouncy castle. It was a day filled with hands-on fun and learning! 


For more details about the event, click [here <i class="fa fa-external-link" aria-hidden="true"></i>]( https://www.sciencecityday.de/programm/wave-field-huepfburg/) or have a look to our [blog post <i class="fa fa-file-text" aria-hidden="true"></i>]({{ site.url }}/news/ScienceCityDay/). 

![Science City Day]({{ site.url }}{{ site.baseurl }}/assets/images/SCHWebHeader.jpg)
{: .image-right}
