---
layout: post
title: Yelp Explorer
description: Interactive Query Tool for Yelp Data
image: assets/images/yelp-explorer/foodtable.jpg
---
An interactive query tool for Yelp data. Built using Bokeh version 0.12.6 and the Yelp Fusion API. See [source](https://github.com/swetharevanur/dataviz/tree/master/yelp_explorer).

I introduced a **credibility metric that integrates a business's rating and review count**. This ensures that 5-star establishments with 1000 reviews are given a higher score than 5-star establishments with 20 reviews.

Interact with the widgets to query a subset of Yelp businesses to plot. Hover over the circles to see more information about each movie. The warmer the circle color, the higher the business's credibility score. The larger the circle, the more pricy the business is.

<iframe src="https://player.vimeo.com/video/227491238" width="640" height="480" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>
<br>
Inspired by the [Bokeh IMDb demo](https://demo.bokehplots.com/apps/movies).
