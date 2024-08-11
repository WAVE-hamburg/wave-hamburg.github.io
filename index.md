---
title: "WAVE"
layout: splash
entries_layout: grid
read_time: false
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Smart_City.png
  actions:
    - label: "Learn more"
      url: /wave/
    - label: "Activities <i class=\"fa fa-file-text\" aria-hidden=\"true\"></i>"
      url: /posts/
excerpt: "The [WAVE initiative](https://indico.desy.de/event/28485/) investigates and designs a seismic and geo-acoustic measurement network in and around the Science City Hamburg Bahrenfeld. WAVE is a unique and innovative infrastructure for geophysics, physics and large-scale research facilities."
intro: 
  - excerpt: 'A key element of WAVE is the use of modern seismic sensors, in particular distributed acoustic sensing (DAS). This technology uses fiber optic cables as sensitive seismic sensors. It enables ground motion data to be recorded at an unprecedented spatial density over long distances.'
feature_row_outreach:
  - image_path: assets/images/Stream_Soccer.png
    alt: "Outreach"
    title: "Outreach"
    excerpt: "Concerts, soccer and visitors send vibrations through the research campus. We showcase these live on Twitch, explanations on [Instagram <i class=\"fab fa-instagram\" aria-hidden=\"true\"></i>](https://www.instagram.com/wave.hamburg/) and present [results]({{ site.url }}{{ site.baseurl }}/posts/)."
    url: /outreach/
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/2024_taylors_waves_spectrogram_annotated.png
    title: "Swiftquakes"
    excerpt: "Have a look at our [results]({{ site.url }}{{ site.baseurl }}/posts/), screenshots and animations from the Taylor Swift Concert in the Volksparkstadion in Hamburg 2024."
    url: "https://wave-hamburg.eu/tags/#taylorswift"
    btn_label: "Posts <i class=\"fa fa-file-text\" aria-hidden=\"true\"></i>"
    btn_class: "btn--primary"
  - image_path: assets/images/ScienceCityDay_nofaces.jpeg
    alt: "WAVE-field"
    title: "Wave field"
    excerpt: "In June 2024, we debuted a prototype of our WAVE Field—a playground designed for visitors of Science City Day to explore the WAVE seismic network."
    url: "https://wave-hamburg.eu/outreach/#wave-field-and-science-city-day"
    btn_label: "Read more"
    btn_class: "btn--primary"
feature_row_science:
  - image_path: /assets/images/iDAS.jpg
    alt: "Scientists looking at the DAS system."
    title: "Science"
    excerpt: 'The WAVE team is interdisciplinary and involved science projects from geophysics, seismology, physics - especially accelerator and gravitational wave physics, informatics and engineering.'    
    url: /science/
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row_team:
  - image_path: /assets/images/Team/2023_WAVE_group_photo.JPEG
    title: "The WAVE Team"
    excerpt: 'We are a young collaboration of seismologists, physicists, engineers and computer scientists. Meet our team from the University of Hamburg, DESY, Helmut Schmidt University, GFZ Potsdam, and XFEL, working together on seismic and geophysical research.'
    url: "/team/"
    btn_label: "Read More"
    btn_class: "btn--primary"
related: true
tags:
  - outreach
  - news
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_science" type="left" %}

{% include feature_row id="feature_row_outreach" %}



# Livestream


Experience real-time campus vibrations live on Twitch, now featuring our enhanced filtered waterfall diagram!


<html>
  <body>
    <!-- Add a placeholder for the Twitch embed -->
    <div id="twitch-embed"></div>

    <!-- Load the Twitch embed JavaScript file -->
    <script src="https://embed.twitch.tv/embed/v1.js"></script>

    <!-- Create a Twitch.Embed object that will render within the "twitch-embed" element -->
    <script type="text/javascript">
      new Twitch.Embed("twitch-embed", {
        width: 1000,
        height: 365,
        channel: "wave_hamburg",
        // Only needed if this page is going to be embedded on other websites
        parent: ["embed.example.com", "othersite.example.com"]
      });
    </script>
  </body>
</html>


[Twitch <i class="fab fa-twitch" aria-hidden="true"></i>](https://www.twitch.tv/wave_hamburg){: .btn .btn--primary}

![Screenshot]({{ site.url }}{{ site.baseurl }}/assets/images/Campusday_twitch_QR Kopie.png){: .align-left} If you cannot see the embedded video, try going [here <i class="fab fa-twitch" aria-hidden="true"></i>](https://m.twitch.tv/wave_hamburg) or scan the QR code, or wait for the [next livestream](/outreach/#upcoming). 


{% include feature_row id="feature_row_team" type="right" %}
