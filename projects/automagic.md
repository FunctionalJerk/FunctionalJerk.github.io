---
layout: default
title: 'automagic'
---

# Automagic

<iframe title="automagic live" width="100%" height="500" src="https://makertube.net/videos/embed/n2mMk9wKi1gUMKhRZEyD9V" frameborder="0" allowfullscreen="" sandbox="allow-same-origin allow-scripts allow-popups allow-forms"></iframe>  
*© Elisabeth Codoux*

This project took place in early 2025 on the occasion of **Elisabeth Codoux'** masters exam in *Klang und Realität* at *Robert Schumann Hochschule Düsseldorf*.  
Her idea was to build a series of 'musical robots' that are remote-controllable so that an audience could interact with them within a live-performance setting.  
Elisabeth asked me to help her implement this idea. She designed and built the hardware part of the *robots* and their remote controls according to my advise, while I designed and built the circuits and software for the microcontrollers.  

We ended up building six robots that were equipped with LEDs, aswell as stepper- and vibrationmotors. For each robot we build one remote control that controlled the LED color, LED "candlelight flicker" (pseudo-random brightness modulation),   aswell as each of the motors speed. 

Dennis Scheiba kindly helped us create a custom network protocol for transmitting the remote controls' data and reviewed my code.  
 
#### Pics 

<iframe title="Automagic" width="100%" height="500px" src="https://makertube.net/videos/embed/sWewgtryYhpFsvCuEhcPnJ" frameborder="0" allowfullscreen="" sandbox="allow-same-origin allow-scripts allow-popups allow-forms"></iframe>  
*© Elisabeth Codoux*  
Closeup of the first prototype.

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/Elli_2_scale.jpg){: width="100%" }  
Perfboard with the ESP32C3 that was inside the remote controls. 

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/IMG_3820_crop.jpg){: width="100%" }  
*© Elisabeth Codoux*  
One of the six remote controls

<!---
#### Automagic

![]({{ site.github.url }}/assets/img/projects/{{ page.title }}/Elli_1.jpg)  
*© Raphael Zöschinger* 

## Technical stuff
--->

## Related projects

 - [invers/invertiert]({{ site.url }}/projects/inversinvertiert)
