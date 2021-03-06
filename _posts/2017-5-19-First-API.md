---
layout: post
title: Random Forest Tree Illustrator API
---

I've recently built a little Python Flask API in an attempt to learn HTML, CSS, JavaScript, and application deployment. My API ([Yes! Click me! It works!](https://katharina-rfd3.herokuapp.com/)) illustrates random forest trees using interactive D3.js objects and AJAX POST requests.

<div id="this"><style>
#this {
border-style:solid;
border-color:#000000;
border-width: 1px;
text-align:center;
}
</style><img src="http://i.imgur.com/GXhNWkX.png" width="800"></div>

A live demo can be found on YouTube [here](https://www.youtube.com/watch?v=D8_yesxONsM) that showcases interactions with the slider as well as collapsing and expanding the trees.

The random forest model came from a quick and dirty binary classifier that differentiates the Python versions - 2.7 or 3.x - of 14,000 Python questions scraped from [Stack Overflow](https://stackoverflow.com/). The classifier has a petty area-under-curve (AUC) of roughly 69% on the hold-out set, but it serves the purpose of my first adventure into the frontend world.

<div style="text-align:center"><img src="http://i.imgur.com/PUXijl5.jpg" width="500"></div>

While I am embracing the freedom of the open sourced world, my academic years gave me the good manners of research citation, so here is a list of people I am thankful for:

- [Paul Burkard](https://github.com/pburkard88) who walked me through [Kyle Mix](https://github.com/kmix27)'s API template codes
- [Andrew Blevins](https://github.com/andrewdblevins) for patiently answering all of my questions - even the eccentric ones
- Mike Bostock and his amazing [collapsible indented tree](https://bl.ocks.org/mbostock/1093025)
- [MasterMaps](http://mastermaps.com/) which is the company behind the [d3 slider](http://thematicmapping.org/playground/d3/d3.slider/)

My source code and README file are accessible [here](https://github.com/katharinax/sf17_ds6_mystuff/tree/master/local/project3).
