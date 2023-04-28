---
layout: post
title: 'DataMining'
---

# Audio Data Mining

This project was was part of my bachelor studies in *Music and Media* at *Robert-Schumann-Hochschule Düsseldorf* and was dedicated to the methods for analyzing the speech melodies (F0) that occur in everyday human interaction. 
I first tried the python-library [librosa.pyin](https://librosa.org/doc/main/generated/librosa.pyin.html), but ended up using the package [intonation](https://github.com/usagi5886/intonation) for the [R-programming-language ](https://www.r-project.org/) to extract and visualize these melodies.  

Building on the resulting data-set, I used some of the methods described in the instructions for using the [AudioTSNEViewer](https://ml4a.github.io/guides/AudioTSNEViewer/) by *Machine Learning for Artists*:

<video width="100%" height="336" controls>
  <source src="{{ site.url }}/assets/vid/projects/{{page.title}}/tsne.mp4" type="video/mp4">
</video>  

As you may notice, some of the samples represented by the dots in this scatterplot do not get triggered. 
Because of that and because I wanted to explore even more of the possibilities offered by [t-SNE](https://medium.com/analytics-vidhya/what-is-t-sne-37bfb920e431),
I headed on to start my next project. 

[Visit the tSNE-VocalSampler]({{ site.url }}/projects/VocalSampler) and [listen to °mm ↓m​:​°​,]({{ site.url }}/projects/mm-m) to get an idea of how to use this data to generate algorithmic scores and synthesize sound. 

The project will soon be available on GitHub. Meanwhile, you'll have to settle for some pictures:

<!--- [SuperCollider](https://supercollider.github.io/). --->

## Plots and Visualizations

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/col.png)

*Visualization of F0-data through R-intonation*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/friend.png)

*Collection of utterances performed by a good friend, visualized through R-intonation*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/pyin.png)

*Mel-spectrogram with librosa.pyin, showing spectral content of an utterance*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/F0.png)

*Visualization of F0 with librosa.pyin, showing the intonation of an utterance*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/richvis.png)

*Richvisualization through R-intonation*


<!--- [GitHub-repostitory](https://github.com/FunctionalJerk/audio-DataMining) --->

## Related projects 
- [VocalSampler]({{ site.url }}/projects/VocalSampler)
- [°mm ↓m​:​°​,]({{ site.url }}/projects/mm-m)
