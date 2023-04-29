---
layout: post
title: 'DataMining'
---

# Audio Data Mining

This project was was part of my bachelor studies in *Music and Media* at *Robert-Schumann-Hochschule Düsseldorf* and was dedicated to the methods for analyzing the speech melodies (F0) that occur in everyday human interaction.  
The data was sourced in a prior project, which aimed to collect variations of human vocal melodies in interjections. This idea was strongly inspired by Gail Jefferson's writings on Conversation Analysis.  

I first tried the python-library *librosa.pyin[^pyin]*, but ended up using the package *intonation[^inton]* for the *R-programming-language[^cran]* to extract and visualize these melodies.  

Building on the same audio library, I realised my own version of the *AudioTSNEViewer[^atv]* by *Machine Learning for Artists*:

<video width="100%" height="336" controls>
  <source src="{{ site.url }}/assets/vid/projects/{{page.title}}/tsne.mp4" type="video/mp4">
</video>  

[Visit the tSNE Vocal Sampler]({{ site.url }}/projects/VocalSampler) and [listen to °mm ↓m​:​°​,]({{ site.url }}/projects/mm-m) to get an idea of how to use this data to generate algorithmic scores and synthesize sound. 

## Todo

There's a lot still to explore here. 
The python-script that was used to create the *t-SNE plot[^tsne]* looks for similarities in harmonic content. 
To apply it to my proposal for relative vocal harmony, each sample needs to be put in relation to it's speakers vocal range. 
I will try and rewrite th, so that it compares the samples actual intonation

---
* nessecary line
{:footnotes}

[^pyin]: [librosa.org/pyin](https://librosa.org/doc/main/generated/librosa.pyin.html)
[^inton]: [github.com/usagi5886/intonation](https://github.com/usagi5886/intonation)
[^cran]: [r-project.org](https://www.r-project.org/)
[^atv]: [ml4a.github.io/guides/AudioTSNEViewer](https://ml4a.github.io/guides/AudioTSNEViewer/)
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

## Related projects 
- [VocalSampler]({{ site.url }}/projects/VocalSampler)
- [°mm ↓m​:​°​,]({{ site.url }}/projects/mm-m)
