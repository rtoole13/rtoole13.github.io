---
layout: post
title: Boids
description: A boid algorithm sandbox
img: /img/boids.gif
---
<div>
In its current state, a very primitive <a href="https://en.wikipedia.org/wiki/Boids">Boids</a> algorithm, employing the three rules of <b><i>separation</i></b>, <b><i>alignment</i></b>, and <b><i>cohesion</i></b>.
{% if jekyll.environment == "development" %}
    <iframe width="1000" height="750" src="https:/rtoole13.github.io/boids" frameBorder="0"></iframe>
    <p>Check out the repository <a href="https://github.com/rtoole13/boids">here!</a></p>
    <p>Dedicated page <a href="https:/rtoole13.github.io/boids">here</a>.</p>
{% else %}
    <iframe width="1000" height="750" src="{{ site.baseurl }}/boids" frameBorder="0"></iframe>
    <p>Check out the repository <a href="https://github.com/rtoole13/boids">here!</a></p>
    <p>Dedicated page <a href="{{ site.baseurl }}/boids">here</a>.</p>
{% endif %}

</div>
