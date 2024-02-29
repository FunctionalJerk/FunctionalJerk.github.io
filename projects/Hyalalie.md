---
layout: post
title: 'Hyalalie'
---

# Hyalalie

This summer my good friend Sebastian Fecke Diaz and I were invited by *Hochschule Niederrhein* to contribute to [Urbanorama-Festival](https://urbanorama-festival.de/) in Krefeld, Germany. 
Together we realized a sound installation, that ran from 23th of June until the 9th of July.  

The site was an old octagonal glass Pavillon, that once was build to serve as an ice-cream parlor but was abandoned for unknown reasons.
The Pavillon is seated in the middle of the avenue that connects the main station with the city's Theater and is surrounded by Cafés, Kiosks and tram-tracks. 

We had already started experimenting with wavesets-based granular synthesis[^fn1] and were determined to transfer our research onto a generative installation. 

The design department of *Hochschule Niederrhein* was so kind to help us print the following text onto the outside wall:  
  
`Die Klänge um den Glaspavillon auf dem Ostwall - vorüberziehende Passanten, vorbeifahrende Straßenbahnen - resonieren im Innern seiner gläsenernen Membran. Im Rahmen der Klanginstallation wird dem Pavillon ermöglicht seine Umwelt zu hören und sich ihr mitzuteilen. So lässt er sich bei dem Versuch beobachten, die Sprache seiner Umgebung durch mechanische Imitationen zu erlernen.`

`hy·a·la·lie: von altgriechisch hyalos, "Glas" und griechisch laléō „ich rede“`

<iframe 
src="https://player.vimeo.com/video/866247540?h=85f92d3b68&color=c9ff23&title=0&byline=0&portrait=0" 
width="597" 
height="336" 
frameborder="2" 
allow="autoplay; fullscreen; picture-in-picture" 
allowfullscreen
></iframe>

## technical stuff

This installation was programmed in SuperCollider running on a RaspberryPi 4©. 
Input source were two DIY contact-mics (Piezos) that were attached to the glass walls of the pavillon and amplified by a DIY preamp. 
These inputs would be recorded and analyzed for zero-crossings, if certain conditions were given. 
The resulting wavesets were then used to play one of many different algorithmic patterns, depending on various factors of randomness. 
We used four transducers or *electro-dynamical exciters*, mounted to the glass walls of the pavillon to turn them into speakers.  

<!--
It was quite a challenge to make a generative sound installation run dusk til dawn in a public space.
Sebastian and I have learned alot through this project and are very greatful for this opportunity.
-->
Our thanks to Patrick Wendtland, Lucas Brucks, and Clemens Brück of the design department of *Hochschule Niederrhein* for having and supporting us.  

---

[^fn1]: see T. Wishart (1994): Audible Design

