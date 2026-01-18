---
layout: default
title: 'axismundi'
---

# Axis Mundi

After being asked to produce an audio installation for a festival celebrating the 8th birthday of [Callshop Radio](https://callshopradio.com/), Lennart Posch and I got together to conceptualize this project.
We decided to build a sonic sculpture that would process and sonify the electromagnetic interferences in the room.  
I had already been digging myself into the rabbit hole of point-to-point-soldering, strongly inspired by the works of Peter Vogel and Iona Vreme Moser.  
So I started the building process, while Lennart planned the staging and scenic elements.  
He invited the phenomenal bass-baritone [Thomas Huy](https://en.dlopera.com/thomas-huy) to perform with the sculpture on the day of the festival, which worked wonderfully. 
In order for that to work, I mixed Thomas' vocals with the EMF signals in the processing stage.  
An old valve radio would serve as a base for the sculpture and as a source of strong EMI.

#### Build

I copied the circuit of the [Electrosluch Mini City®](https://store.lom.audio/products/elektrosluch-mini-city-diy-kit-1) for the input stage of the sculpture and designed a layout:

![electroslush]({{ site.github.url }}/assets/img/projects/{{ page.title }}/electroslush.svg){: width="100%" }  
*P2P layout of the Electrosluch for the input stage*

I did the same with the [Ruby Guitar Amp®](https://www.runoffgroove.com/ruby.html) for the output stage: 

![ruby]({{ site.github.url }}/assets/img/projects/{{ page.title }}/ruby.svg){: width="100%" }  
*P2P layout of the Ruby guitar amp*

For the processing (between input -and output-stage) I used a RaspberryPi® running a custom SuperCollider sketch. 

#### Pics:

{% include image-gallery.html folder="/assets/img/projects/axismundi/proto" %}  
*Unfinished sound-scultpure during the build process – © @flordefuega*

{% include image-gallery.html folder="/assets/img/projects/axismundi/gallery" %}  
*© Thomas Schoger – @schogette_*
