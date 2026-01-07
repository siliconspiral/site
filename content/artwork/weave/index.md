---
title: "Weave"
date: 2024-11-21
draft: false
description: "Weave"
tags: ["Weave", Generative Art"]
summary: "Series 1 / Part 5"
---
![Weave](art/weave.png "Weave<br>Series 1 / Part 5")

{{< lead >}}
"The fifth part of this series is an example of unexpected properties emerging with each attempt to develop the piece further. I wanted to toy with the idea of autonomous elements moving around the canvas. In this case, I set off a single element which followed a two step process again and again. I called this element a “mouse”, and in fact, the piece was originally called *Whiskers* rather than *Weave*."
{{< /lead >}}

---

For me, the mechanism by which a blank canvas is transformed into passable art is through iterative development and embracing unexpected deviation with each iteration. In art, and in other disciplines, the phenomenon whereby unexpected outcomes become apparent is called [Emergence](https://en.wikipedia.org/wiki/Emergence). Increasingly complex behaviours in a system lead to complex interactions which in turn produce unpredictable results, so called *Emergent Properties*. As you might imagine, this is particularly prevalent in generative art where the ability to layer more and more behaviour in code with great ease enables the coder cum artist to introduce complexity, in turn leading to hopefully desirable emergent properties.

So what does this mean in practice? I don't think about the process consciously, but having given some it thought, with each iteration it involves the following:

1. Stop and look at the current state of the art and think about what has changed from the previous iteration. What do you like? What don't you like? The change from a previous iteration is often unexpected i.e. emergent and will sometimes produce a visceral reaction, positive or negative.

2. Add a small amount of code to do one or more of the following:

  - Build upon what you like by adjusting and improve it, particularly if you just added it.
  - Fix or remove what you don't like, particularly if you just added it.
  - Conceive of, and implement, new additions which will complement what you see.

3. Rerun the code. Often the change won't quite be what you intended.

4. Return to step 1.

N.B. I think it's important not to overthink the changes you want to make before trying to faithfully recreate them. Experimentation and "failure" is key. Thinking "that should roughly give me what I want" or "let's see what happens if I tweak this number a bit" can lead to good results.

The piece that's missing from this process is how to come up with that initial idea, or seed, from which to start iterating. I hope to cover that in the final part of this series for the piece [ammonite]({{< relref "artwork/ammonite/index.md" >}}).

Back to Weave, this was a great example of unexpected properties emerging with each iteration. Similar to what I did with [Nett]({{< relref "artwork/nett/index.md" >}}), I wanted again to toy with the idea of autonomous elements moving around the canvas. In this case, I set off a single element which followed a two step process again and again. I called this element a "mouse", and in fact, the piece was originally called *Whiskers* rather than *Weave*. This is the process:

1. Move in a straight line for a random distance favouring stopping on a set grid of points on the canvas.

2. Change direction to one of the eight points of the compass.

Apart from making sure the mouse didn't leave the canvas, that was it. The result was as follows:

![](/img/weave-1.png "Whiskers")

Now I really like this, and hope to revisit it one day, but by accident, I left the programme running longer than usual to make a cup of tea, and the following emerged:

![](/img/weave-2.png "Weave Original")

It looked like a basket weave and I thought I'd run with that. I then added a textured purple background to [complement](https://en.wikipedia.org/wiki/Complementary_colors) the yellow / orange / gold in the image. Purple also added a sense of royalty to the golden pattern. At this point, I felt the edges looked very regular and though about how I could make them look more natural, so I frayed them a little by having the "mouse" simply turn back on itself when it reached the edge of the weave to give the final product.
