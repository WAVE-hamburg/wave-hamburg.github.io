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
toc_icon: "heart"  # corresponding Font Awesome icon name (without fa prefix)
toc_sticky: true
read_time: false
categories:
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
        width: 600,
        height: 365,
        channel: "wave_hamburg",
        // Only needed if this page is going to be embedded on other websites
        parent: ["embed.example.com", "othersite.example.com"]
      });
    </script>
  </body>
</html>


{% capture notice-2 %}
**Upcoming livestreams:** 
* 10.08.2024 Soccer match at Volksparkstadion (2 km away from campus), start 20:30 CEST
* 30.08.2024 Deichkind on the Trabrennbahn (100m away from campus)
* 04.09.2024 Justin Timberlake in the Barclays arena (2 km away from campus)
* 13.09.2024 Scorpions Barclays arena (2 km away from campus)
{% endcapture %}

<div class="notice">{{ notice-2 | markdownify }}</div>


<figure class="align-left">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/Campusday_twitch_QR.png" alt="qrcode" width="1cm">
</figure> 
If you cannot see the embedded video, try going [here](https://m.twitch.tv/wave_hamburg) or scan the QR code.



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

### Public hearing EM24 

Can we hear the goals from the Euros below ground?

With our WAVE glass fiber, we listen to vibrations underground with a thousand ears. On the 5th of July 2024, when France and Portugal met at the Volksparkstadion Hamburg for the quarter finals, just 2 km from our experiment, we livestreamed our vibration measureements during the match. When goals are scored, the celebrations cause the kind of vibrations that we can measure! We tested how sensitive our setup is and whether we can see the vibrations within the fiber.

![Screenshot]({{ site.url }}{{ site.baseurl }}/assets/images/20240705_WAVE_EM_Livestream.png)
{: .image-right}

What am I looking at??

Along our 16 km of glass fiber, we measure how much it vibrates, or 'wiggles', about every 10 meters. Each horizontal line in the image shows you how much that particular section of glass fiber is wiggling. Red means that there are strong vibrations, blue shows the bits where it's quieter.

Starting from the top, you see how much vibrations are currently felt in DESY's PETRA tunnel. Since that tunnel is a few meters underground, there are not a lot of vibrations from car traffic, wind and such. So it's pretty blue. The same is true for the vibrations in the XFEL tunnel - also pretty 'quiet', and blue.

Going further down in the image, we reach the part of the fiber that is near the surface, and roads, on the DESY/Bahrenfeld campus. The car traffic, trees swaying in the wind, and general urban activity all generate vibrations, so those sections of the glass fiber are wiggling more - and show up red!

The whole picture is moving towards the left: that's time passing by.


## WAVE Field and Science City Day

On Saturday, 1st June 2024 from 11:00 - 19:00, the WAVE team was be present at the Science City Day, to show you what the measurements with our fiber-optic seismic network look like. Can you find out where our fiber is buried? Can you generate seismic waves? What if you hop around on a bouncy castle?? Come try it out on the DESY campus! More information here: https://www.sciencecityday.de/programm/wave-field-huepfburg/.

![Science City Day]({{ site.url }}{{ site.baseurl }}/assets/images/SCHWebHeader.jpg)
{: .image-right}
