---
layout: post
title:  "Styling Google Maps"
date:   2015-01-21 23:30
categories: design, development
---
Ever had a need to drop a Google Map in your design, but didn’t want Google’s default tan color scheme feeling out of place in your design? Here’s how you can customize a Google Map's style, both on embedded and static maps.

The easiest way to style a Google Map is to use the interactive [Styled Maps Wizard](http://gmaps-samples-v3.googlecode.com/svn/trunk/styledmaps/wizard/index.html). Here, you can easily design and preview a map style to fit your design. You can change colors, levels of details, label displays, etc. It’s very easy to quickly build styles this way, and you can easily export the JSON needed for the Google Maps API, or simply export a styled static Google Map. 

One thing to note - if you’re exporting a static map I highly suggest you set the `scale` parameter to 2x. This will allow for higher resolution files, useful for larger (and Retina) designs.

![A Styled Google Map](/assets/google-map-styled.png)
*<center>A map I recently used in a sustainability site design</center>*