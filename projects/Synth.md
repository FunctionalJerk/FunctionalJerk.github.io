---
layout: post
title: 'Synth'
---

# Bela-Synth

Combining the functioning principles of plate-reverbs and recent experiences with piezoelectric sensors,
I came up with the idea to build a reverb-machine from some kind of string instrument.
One idea followed the next and the project grew pretty big. 
It is still an ongoing project with a long todo-list,
but I want to present a functioning prototype to start out this documentation.

At current state, there are basically two devices.
One is a Zither, that was prepared with speakers and piezoelectric sensors. 
It would serve as a makeshift reverb-device, aswell as an Input source for the actual synth.



The other is a granular synth, programmed in SuperCollider that's running on a *BeagleBone Black*.
It takes audio input and - on the press of a button - stores it in a buffer.   
This audio data is then rearranged in adjustable patterns, rates and various other parameters.  
I will upload a detailed build-documentation to GitHub shortly, but here's a list of it's current features:
<!--- For detailed build-documentation, check out this project's [GitHub-repository](). --->
- stereo i/o
- presets
- MIDI-input
- three controls with value-pickup
- rotary encoder
- trigger button

---
* footnotes will be placed here
{:footnotes}

# Related projects: 

- [°mm ↓m​:​°​,]({{ site.url }}/projects/mm-m)