---
layout: post
title: SpaceRoyale.io
description: A fast-paced battle royale
img: /img/blaster_minimized.gif
---

Years ago a friend of mine and I attempted to build an online multiplayer game after having finished up our first complete project, *Space Pirates* (apparently we took naming the project as seriously as we did the concept). That project was a top-down local multiplayer game in which players attempted to avoid slamming their 17th-century-looking wooden space ships into planets while navigating basic orbital mechanics and firing broadsides at one another.. It was silly fun, and if I ever manage to dig up some screenshots or, better yet, a working build, I'll certainly share. The latter project was an attempt at something akin to <a href="https://subsetgames.com/ftl.html">FTL</a>, one of several fantastic projects of *Subset Games*, but with online multiplayer.  

We attempted to build this brutally overscoped multiplayer game in ActionScript, yep, and shelved it after banging our heads against <a href="https://help.adobe.com/en_US/FlashPlatform/reference/actionscript/3/flash/net/Socket.html">Sockets</a> for a bit, getting only limited functionality from our efforts. Later reviving the desire to create something multiplayer, we came up with <a href="https://github.com/sjdodge123/spacepirates.io">SpaceRoyale.io</a>, when battle royales (BR) were exploding in popularity.  
<div style="text-align:center">
	<img class="two" src="{{ site.baseurl }}/img/spaceroyale_banner.png" alt="" title="SpaceRoyale.io"/>
</div>  
<br/>
Our take on a BR attempted to assuage some of our gripes with the genre in the following ways:  
- Pacing a game to keep players consistently engaged  
- Providing an experience accessible to players with different time commitments  
- Maintaining a flow for players wherein they never felt under- or overwhelmed by challenges presented as they increased in skill  

The resulting prototype (sadly not hosted at the moment) offered fast-paced, short game sessions, bypassed the typical BR loot mechanic in favor of customizable loadouts in a pre-game lobby, featured multiple weapons, passive traits, and special abilities, and used a collectible system similar to that in <a href="https://supercell.com/en/games/brawlstars/">Brawl Stars'</a> *Showdown* mode. In lieu of the actual game, gifs!
<div class="img_row" style="text-align:center">
	<img class="two" src="{{ site.baseurl }}/img/blaster.gif" alt="" title="Blaster action."/>
</div>
<br/>
In the above, a player is retreating from a bot with the blaster. You can see the "blood seeker	" ability triggered towards the end, increasing player agility when enemies nearby are near death. Next, you can see that we simply had to have a laser beam. One that terminates at an arbitrary range apparently..
<div class="img_row" style="text-align:center">
	<img class="two" src="{{ site.baseurl }}/img/particlebeam.gif" alt="" title="Particle beam!"/>
</div>
<br/>
One of the three special abilities you can choose when determining your loadout in the game lobby is the directional shield, shown below.
<div class="img_row" style="text-align:center">
	<img class="two" src="{{ site.baseurl }}/img/shield.gif" alt="" title="The directional shield ability."/>
</div>
<br/>
Another ability, the pulse wave, allows you to pull enemies towards you. The force applied might be a bit much here, but it makes for some fun situations.
<div class="img_row" style="text-align:center">
	<img class="two" src="{{ site.baseurl }}/img/pulsewave.gif" alt="" title="The pulse ability."/>
</div>
<br/>
I intend to write a much-delayed post mortem on the project in which I'll go into detail on how the game's structured and discuss some of the difficulties faced in our first attempt at building something with this client-server model. There's a lot to discuss here, as I learned a ton building an entire game without an established framework. It's a painstaking way to develop, but, having done this multiple times now, I wouldn't go back and change my approach if I could. Between this project and <a href="{{ site.baseurl }}/pickets">Pickets</a>, I've built functional tools for handling audio, rendering sprite sheets, handling collision efficiently with quad trees, and, most importantly, learned the hard way how these game systems ought to and ought not to interact..

 We'll host the game again at a point!
<br/><br/><br/>