---
title: "Germ"
date: 2025-11-02
draft: false
description: "Germ"
tags: ["Germ", Generative Art"]
summary: "Series 2 / Part 2"
---
![Germ](art/germ.png "Germ<br>Series 2 / Part 2")

{{< lead >}}
This piece started life courtesy of the book [50 Visions of Mathematics](https://global.oup.com/academic/product/50-visions-of-mathematics-9780198701811) forwarded by the Irish comedian and closet mathematician, Dara Ó Briain. Chapter 7 is titled *Pigs didn't fly but swine flu* in which Ellen Brooks-Pollock and Ken Eames describe a theoretical mathematical model for the transmission of swine flu in the UK. This piece is a visual representation of that model.
{{< /lead >}}

![](/img/50-visions-of-mathematics.jpg "Visions of Mathematics")

---

Key to how the model works is to consider every individual's infection status as being in one of three categories:

* Susceptible: yet to be infected.
* Infectious: infected and capable of transmitting infection to surrounding individuals.
* Recovered: no longer infected, no longer infectious, and immune from reinfection for a time before becoming susceptible again.

The following factors are also taken into account:

* Transmission rate: the number of people infected by an infected individual in a given stretch of time.
* Recovery rate: the amount of time taken for an infected individual to recover and no longer be infected.

This piece is the end result of a simulation whereby a canvas is initially filled with susceptible individuals represented as hexagons filled with the background colour. A single infected individual, represented as a green hexagon, is placed in the middle of the canvas, and subsequent transmission, infection and recovery of individuals is modelled based on the transmission rate and recovery rate. Each category of individual is represented with a different colour, and the level of infection or recovery by the depth of that colour:

* Susceptible: background colour
* Infected: greens to yellows
* Recovered: blues to magenta

Here is a short video demonstrating the simulation:

<center>
<video width="100%" controls>
    <source src="/vid/germ.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
</center>

Finally, why the name *Germ*? At first, the piece was called *Transmission*, but at some point, the output started to look like the Swine Flu virus itself whose transmission was being modelled.

![](https://upload.wikimedia.org/wikipedia/commons/8/8b/CDC-11214-swine-flu.jpg "Electron microscope image of swine flu virus<br>Wikipedia Public Domain, C. S. Goldsmith and A. Balish, CDC")
