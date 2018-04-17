---
title: Video Post Test
date: 2014-06-01 03:14:02 Z
categories:
- articles
tags:
- video
layout: article
modified: 
excerpt: A post with a YouTube video.
ads: false
image:
  feature: blog.jpg
  teaser: blog.jpg
---

Here's a sample video to test FitVid.js

If this is working correctly the video should fill the main content container.

<iframe width="560" height="315" src="//www.youtube.com/embed/9e1nPyHXCFQ" frameborder="0"> </iframe>

<iframe width="560" height="315" src="//evaquemere.github.io/elena-de-platz-en-platz/" frameborder="0"> </iframe>

<!-- The StoryMap container can go anywhere on the page. Be sure to
    specify a width and height.  The width can be absolute (in pixels) or
    relative (in percentage), but the height must be an absolute value.
    Of course, you can specify width and height with CSS instead -->
<div id="mapdiv" style="width: 100%; height: 600px;"></div>

<!-- Your script tags should be placed before the closing body tag. -->
<link rel="stylesheet" href="https://cdn.knightlab.com/libs/storymapjs/latest/css/storymap.css">
<script type="text/javascript" src="https://cdn.knightlab.com/libs/storymapjs/latest/js/storymap-min.js"></script>

<script>
// storymap_data can be an URL or a Javascript object
var storymap_data = '//www.oisif.fr/eva.json';

// certain settings must be passed within a separate options object
var storymap_options = {};

var storymap = new VCO.StoryMap('mapdiv', storymap_data, storymap_options);
window.onresize = function(event) {
    storymap.updateDisplay(); // this isn't automatic
}
</script>
