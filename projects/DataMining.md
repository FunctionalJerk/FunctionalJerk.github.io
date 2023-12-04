---
layout: post
title: 'DataMining'
---

# Audio Data Mining

This project was was part of my bachelor studies in *Music and Media* at *Robert-Schumann-Hochschule Düsseldorf*.  
It was dedicated to the methods for extracting and comparing the *fundamental frequencies[^f0]*, that occur within inconspicuous areas of everyday human interaction.  
The data was sourced in a prior project, which aimed to collect variations of human vocal melodies in interjections. This idea was strongly inspired by *Conversation Analysis and sociolinguistics[^ca]*.  

After doing some research, I ended up using the package [*intonation*](https://github.com/usagi5886/intonation) for the [*R-programming-language*](https://www.r-project.org/) to extract and visualize these melodies.  
These results would later be needed for [other projects]({{ site.github.url }}/projects/{{ page.title }}#related-projects) 

Building on the same audio library, I realised my own version of the [*AudioTSNEViewer*](https://ml4a.github.io/guides/AudioTSNEViewer/) by *Machine Learning for Artists*:

<video width="100%" height="336" controls>
  <source src="{{ site.url }}/assets/vid/projects/{{page.title}}/tsne.mp4" type="video/mp4">
</video>  

[Visit the tSNE Vocal Sampler]({{ site.url }}/projects/VocalSampler) and [listen to °mm ↓m​:​°​,]({{ site.url }}/projects/mm-m) to get an idea of how to use this data to generate algorithmic scores and synthesize sound. 

## Todo

There's a lot still to explore here. 
The python-script that was used to create the *t-SNE plot[^tsne]* looks for similarities in harmonic content. 
To apply it to my idea of relative vocal harmony, each sample needs to be put in relation to it's speakers vocal range. 
I will soon rewrite it, so that it compares the actual intonation contained in the samples. 

---
* nessecary line
{:footnotes}

[^f0]: [wikipedia.org/wiki/Fundamental_frequency](https://en.wikipedia.org/wiki/Fundamental_frequency)
[^ca]: [wikipedia.org/wiki/Conversation_analysis](https://en.wikipedia.org/wiki/Conversation_analysis)
[^tsne]: [medium.com/analytics-vidhya/what-is-t-sne](https://medium.com/analytics-vidhya/what-is-t-sne-37bfb920e431)

## Plots and Visualizations

The project will soon be available on GitHub. Meanwhile, you'll have to settle for some pictures:

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/col.png)

*Visualization of F0-data through R-intonation, showing the intonation in personalised stylization.*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/friend.png)

*Collection of utterances performed by a good friend, visualized through R-intonation.*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/richvis.png)

*Richvisualization through R-intonation showing waveform, F0-contour and spectrogram in default configuration.*


<!--- [GitHub-repostitory](https://github.com/FunctionalJerk/audio-DataMining) --->

# Related projects 
- [VocalSampler]({{ site.url }}/projects/VocalSampler)
- [°mm ↓m​:​°​,]({{ site.url }}/projects/mm-m)
