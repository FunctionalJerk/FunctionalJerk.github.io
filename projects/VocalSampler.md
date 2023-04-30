---
layout: post
title: 'VocalSampler'
---

# tSNE-VocalSampler

In this project I aimed to connect the results of my artistic research on vocal melodies and on mining audio-data. 
It was part of my bachelor studies in *Music and Media* at *Robert-Schumann-Hochschule Düsseldorf*.  

<video width="100%" height="336" controls>
  <source src="{{ site.url }}/assets/vid/projects/{{page.title}}/demo.mp4" type="video/mp4">
</video>  

Samples within a library were analyzed and mapped by the t-SNE algorithm through a [*python-script*](https://github.com/ml4a/ml4a-ofx/blob/master/scripts/tSNE-audio.py) provided by [*Machine learning for Artists*](https://ml4a.github.io/ml4a/). 

Out comes a 2D-Scatterplot where each point represents a vocal-sample. 
These samples can now be sequenced and resynthesized live, through a gui that was programmed in *SuperCollider*.

For further information, please refer to this project's [GitHub-repostitory](https://github.com/FunctionalJerk/tSNE-VocalSampler).  


# Todo

This was a fun little exercise, but there's still alot to explore here!  
In future versions of this application, I want to implement a 3D-Scatterplot and various serial interfacing options, like:  
MIDI-out, MIDI-clock, Ableton's LinkClock, tty and CV.  

Instead of an audio library, I want to use the abovementioned script on a single audio recording of everyday human interaction.  
I will also try to provide a more generally applicable version of this and check out some of the different GUI-layouts provided by *SuperCollider*.  

---
* nessecary line
{:footnotes}


# Related projects: 

- [Audio Data Mining]({{ site.url }}/projects/DataMining)
- [°mm ↓m​:​°​,]({{ site.url }}/projects/mm-m)
