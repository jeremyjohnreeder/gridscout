---
layout: post
title: Google killed Gmap4! :O
author: Jeremy Reeder
date: 2018-08-30
tags: google map gmap4
---

Google recently changed its API usage policy, effectively putting the
non-profit [Gmap4][gmap4] out of business. That's unfortunate, as Gmap4 was
designed to benefit disaster-management organizations and was doing a great
deal of good in that realm. Since [GridScout™][gridscout] used Gmap4 for its
aerial views, that feature currently won't work. While this does not affect
GridScout's primary goal of searching Google Maps and performing bulk
collection of MGRS location data, it does make it harder to verify the
relevance of unfamiliar search results. The maker of Gmap4 has made appeals to
Google in hopes of coming to an agreement, but Google refused. In order to
continue using the Google Maps API in his volunteer efforts, he'd have to shell
out $46,000 per year. So Gmap4 is now gone. Bummer.

<div class="gallery" markdown="1">
![R.I.P. Gmap4][gmap4-rip]
![As of 2018-07-15, free use of Gmap4 has been discontinued.][gmap4-notice]
*We'll miss you, Gmap4.*
</div>

I am now considering alternatives to Gmap4, so that I can restore GridScout's
aerial-view feature.

*Update: [I replaced the aerial viewer.][update]*


[gmap4-notice]: {{ '/images/gmap4-discontinued.png' | prepend: site.url }}
[gmap4-rip]:    {{ '/images/gmap4-tombstone.jpg' | prepend: site.url }}

[gmap4]:        https://mappingsupport.com/p/gmap4.php
[gridscout]:    {{ site.url }}
[update]:       {{ '/2018/11/17/aerial-views-reenabled.html' | prepend: site.url }}
