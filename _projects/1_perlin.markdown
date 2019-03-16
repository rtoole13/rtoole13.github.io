---
layout: post
title: Perlin
description: A Perlin noise sandbox
img: /img/perlin_thumbnail.gif
---
<div>
This tool utilizes <a href="https://en.wikipedia.org/wiki/Perlin_noise">Perlin noise</a> to generate dynamic vector fields that propel particles across a canvas. The project leans heavily on the work of <a href="http://staffwww.itn.liu.se/~stegu/simplexnoise/simplexnoise.pdf">Stefan Gustavson</a>, who created a noise library in Java, <a href="https://github.com/josephg/noisejs">Seph Gentle</a>, who converted that library to JavaScript, and <a href="https://codepen.io/DonKarlssonSan/post/particles-in-simplex-noise-flow-field">Johan Karlsson</a>, who wrote an awesome article/tutorial on the subject, and whose code provided a foundation for this tool.  
<br/>
<br/>
{% if jekyll.environment == "development" %}
    <p>Check out the tool <a href="https://github.com/rtoole13/perlin">here</a>, and the repository <a href="https://github.com/rtoole13/perlin">here!</a></p>
{% else %}
	<p>Check out the tool <a href="{{ site.baseurl }}/perlin">here</a>, and the repository <a href="https://github.com/rtoole13/perlin">here!</a></p>
{% endif %}
<br/>
A few creations:
</div>

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/grid.png" alt="" title="grid-like vector field"/>
	<img class="col one" src="{{ site.baseurl }}/img/bw_2.png" alt="" title="vector field behavior independent in the x and y directions"/>
	<img class="col one" src="{{ site.baseurl }}/img/other_rainbow.png" alt="" title="you can adjust the background color"/>
</div>
<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/highway.png" alt="" title="variable vector field behavior on the same canvas"/>
	<img class="col one" src="{{ site.baseurl }}/img/dandies.png" alt="" title="a strange composite of slow and fast particles and variable and static vector fields"/>
</div>

<div>
<br/>
<p>I wanted to grant as much control as possible over elements of the canvas, from the more intuitive particle speed and acceleration contribution from the field, labeled as "field factor" under the particle subfolder in the gui, to the much less intuitive field parameters, labeled rather misleadingly as "volatility." These parameters control the variability of vectors' directions and magnitudes in the field across space. The behavior ought to be inverted, but, as it stands, a small "volatility" implies that that parameter of the vectors in the field will be more variable than it otherwise would be with high volatility.
</p>
<p>
Oh, and the neat little gui is thanks to <a href="https://github.com/dataarts/dat.gui"> dat.gui</a>, an incredibly useful tool for sandboxes.
</p>
</div>