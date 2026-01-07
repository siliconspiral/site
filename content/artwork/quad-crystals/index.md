---
title: "Quad Crystals"
date: 2024-10-07
draft: false
description: "Quad Crystals"
tags: ["Quad Crystals", Generative Art"]
summary: "Series 1 / Part 2"
---
![Quad Crystals](art/quad-crystals.png "Quad Crystals<br>Series 1 / Part 2")

{{< lead >}}
"This is the second piece my first art series. I began by drawing a set of quadrilaterals radiating out from the centre, and in fact, the piece started off life being called *Quad Ray*, but as the piece developed, the quads look less like rays emanating from the centre, and more like crystals."
{{< /lead >}}

---

Of interest, I've used two different sources of (pseudo)random numbers for this piece...

Firstly, I've employed the [Halton Sequence](https://en.wikipedia.org/wiki/Halton_sequence) which I also used for [Crimson Sun]({{< relref "artwork/crimson-sun/index.md" >}}). Here it is used to generate the locations and dimensions of the quads, and from those, to derive the basic colour of each quad.

Secondly, I've sourced random numbers from a Gaussian distribution, also known as a [normal distribution](https://en.wikipedia.org/wiki/Normal_distribution). Random numbers drawn from the normal distribution, when plotted on a graph, follow a so-called and familiar Bell Curve whereby numbers drawn are most likely gathered around the centre of the graph, and the likelihood of a number being drawn tails off the further away it is from the centre:

![](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8c/Standard_deviation_diagram.svg/1920px-Standard_deviation_diagram.svg.png "Bell Curve")

The normal distribution is commonly found in nature. For example, if you were to plot people's heights, or their blood pressures, or their IQ, you will find that they follow a normal distribution.

This piece uses random numbers from a normal distribution to "jitter" the quads i.e. to redraw each quad with a slight variation in its coordinates. The jitter is used to soften the edges of the quads to make them look a little natural and perhaps almost hand drawn.
