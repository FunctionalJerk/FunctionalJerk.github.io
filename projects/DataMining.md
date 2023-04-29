---
layout: post
title: 'DataMining'
---

# Audio Data Mining

This project was was part of my bachelor studies in *Music and Media* at *Robert-Schumann-Hochschule Düsseldorf* and was dedicated to the methods for analyzing the speech melodies (F0) that occur in everyday human interaction.  
The data was collected in a prior project, which aimed to collect variations of human vocal melodies in interjections. This idea was strongly inspired by Gail Jefferson's writings on Conversation Analysis.  

I first tried the python-library [librosa.pyin](https://librosa.org/doc/main/generated/librosa.pyin.html), but ended up using the package [intonation](https://github.com/usagi5886/intonation) for the [R-programming-language ](https://www.r-project.org/) to extract and visualize these melodies.  

Building on the resulting audio library, I realised my own version of the [AudioTSNEViewer](https://ml4a.github.io/guides/AudioTSNEViewer/) by *Machine Learning for Artists*:

<video width="100%" height="336" controls>
  <source src="{{ site.url }}/assets/vid/projects/{{page.title}}/tsne.mp4" type="video/mp4">
</video>  

[Visit the tSNE-VocalSampler]({{ site.url }}/projects/VocalSampler) and [listen to °mm ↓m​:​°​,]({{ site.url }}/projects/mm-m) to get an idea of I use this data to generate algorithmic scores and synthesize sound. 

The project will soon be available on GitHub. Meanwhile, you'll have to settle for some pictures:

<!--- [SuperCollider](https://supercollider.github.io/). --->

## Plots and Visualizations

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/col.png)

*Visualization of F0-data through R-intonation, showing the intonation (intentionally without scale).*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/friend.png)

*Collection of utterances performed by a good friend, visualized through R-intonation.*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/pyin.png)

*Mel-spectrogram with librosa.pyin, showing spectral content of an utterance.*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/F0.png)

*Visualization of F0 with librosa.pyin, showing the F0-contour of an utterance.*

---

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/richvis.png)

*Richvisualization through R-intonation showing waveform, F0-contour and spectrogram.*


<!--- [GitHub-repostitory](https://github.com/FunctionalJerk/audio-DataMining) --->

## Related projects 
- [VocalSampler]({{ site.url }}/projects/VocalSampler)
- [°mm ↓m​:​°​,]({{ site.url }}/projects/mm-m)
