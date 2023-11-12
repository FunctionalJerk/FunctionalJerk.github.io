---
layout: post
title: 'Synth'
---

# DIY Granular-Synth

This project was part of my Bachelor-studies at *Institute for Music and Media @ Robert-Schumann-Hochschule Düsseldorf.*  
It was submitted on June 17th of 2022.  


Combining the functioning principles of plate-reverbs and recent experiences with piezoelectric sensors,
I came up with the idea to build a reverb-machine from some kind of stringed instrument.

One idea followed the next and the project grew pretty big. 
It is still ongoing with a long todo-list,
but I want to present a functioning prototype to start out this documentation nonetheless.  
Here's a short demo: 

<video width="100%" height="336" controls>
  <source src="{{ site.url }}/assets/vid/projects/{{page.title}}/demo.mp4" type="video/mp4">
</video>  

At current time, there are basically two devices:
1. : A Zither, that was prepared with speakers and piezoelectric sensors.  
It serves as a makeshift reverb-device, aswell as an input source for the actual synth.
2. : A granular synth, programmed in [*SuperCollider*](https://supercollider.github.io/) and running on a *BeagleBone Black*, equipped with a [*Bela-Cape*](https://eu.shop.bela.io/collections/bela-and-bela-mini/products/bela-cape).  
It takes audio input and stores it in a buffer on the press of a button.   
The recorded audio is then rearranged in adjustable patterns, rates and various other parameters.  

Here's a short list of it's current features:

- stereo i/o
- presets
- MIDI-input
- three assignable faders with value-pickup
- rotary encoder
- trigger button

Once I have solved some of it's current problems, I will upload a better demo video, aswell as a detailed build-documentation to [GitHub](https://github.com/FunctionalJerk/bela-grainsynth). 
As of now, there's only source Code to be found there. 

## Pictures

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/Zither_crop.jpg)

Zither after cleaning & before prepping.

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/Zither_inside.jpg)

Inside the Zither after prepping.

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/Synth_front.jpg)

The face or UI of the synth.

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/Synth_inside.jpg)

The inside of the Synth, showing the wiring. 
I know this is a crude job, but remember this is just a prototype.

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/Synth_side.jpg)

Side-view of the Synth, showing the connections.

---

* footnotes will be placed here
{:footnotes}

# Related projects: 

- [°mm ↓m​:​°​,]({{ site.url }}/projects/mm-m)
