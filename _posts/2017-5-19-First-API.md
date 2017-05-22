---
layout: post
title: Random Forest Tree Illustrator API
---

I've recently built a little Python Flask API in an attempt to learn HTML, CSS, and JavaScript. My API illustrated random forest trees using interactive D3.js objects and AJAX POST requests.

<div style="border-style:solid; text-align:center"><img src="http://imgur.com/RkWPvsh" width="500"></div>

A live demo showcasing interactions with the sliders and collapsing/expanding the trees can be found on YouTube [here](https://www.youtube.com/watch?v=D8_yesxONsM).

The random forest model came from a quick and dirty binary classifier that differentiated the Python versions (2.7 or 3.x) of 14,000 Python questions scraped from [Stack Overflow](https://stackoverflow.com/). The classifier had a petty area-under-curve (AUC) of roughly 69% on the hold-out dataset, but it served the purpose of my first adventure into the frontend world.

<div style="text-align:center"><img src="http://imgur.com/PUXijl5" width="500"></div>

While I am embracing the freedom of the open sourced world, my academic years gave me the good manners of research citation, so here is a list of people I am thankful for:

- [Paul Burkard](https://github.com/pburkard88) who walked me through [Kyle Mix](https://github.com/kmix27)'s API template codes
- [Andrew Blevins](https://github.com/andrewdblevins) for patiently answering all of my questions - even the eccentric ones
- Mike Bostock and his amazing [collapsible indented tree](https://bl.ocks.org/mbostock/1093025)
- [MasterMaps](http://mastermaps.com/) which is the company behind the [d3 slider](http://thematicmapping.org/playground/d3/d3.slider/)

My source code and README are accessible [here](https://github.com/katharinax/sf17_ds6_mystuff/tree/master/local/project3).
