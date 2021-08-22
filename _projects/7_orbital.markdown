---
layout: post
title: Orbital
description: 2D astrodynamics
img: /img/intersection_calculation.gif
---
<div>
    Progress on a KSP-esque orbital mechanics game.
    <div style="text-align:center">
        <img class="two" src="{{ site.baseurl }}/img/ui_and_stuff.gif" alt="" title="WIP UI"/>
    </div>
    <br/>

    Particle systems used to represent an asteroid harvesting station's operable radius.
    <div style="text-align:center">
        <img class="two" src="{{ site.baseurl }}/img/particle_fun.gif" alt="" title="Particles!"/>
    </div>

    One may spawn several ships as well..
    <div style="text-align:center">
        <img class="two" src="{{ site.baseurl }}/img/ship_spawn.gif" alt="" title="Ships!"/>
    </div>

    Near-intersections are tracked
    <div style="text-align:center">
        <img class="two" src="{{ site.baseurl }}/img/intersection_calculation.gif" alt="" title="Intersections"/>
    </div>

    One may plot future maneuvers
    <div style="text-align:center">
        <img class="two" src="{{ site.baseurl }}/img/maneuver-nodes_adjust.gif" alt="" title="Maneuvers"/>
    </div>

    <br/>

    {% if jekyll.environment == "development" %}
        <p>Check out the actual project hosted <a href="https://rtoole13.github.io/Orbital">here</a>, and the repository <a href="https://github.com/rtoole13/Orbital">here!</a></p>

        <p>Most progress being made at this point is currently in a private repo. Sorry!</a></p>
    {% else %}
    	<p>Check out the actual project hosted <a href="{{ site.baseurl }}/Orbital">here</a>, and the repository <a href="https://github.com/rtoole13/Orbital">here!</a></p>

        <p>Most progress being made at this point is currently in a private repo. Sorry!</a></p>
    {% endif %}
    <br/>
</div>
