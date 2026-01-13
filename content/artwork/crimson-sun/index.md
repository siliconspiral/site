---
title: "Crimson Sun"
date: 2024-09-27
draft: false
description: "Crimson Sun"
tags: ["Crimson Sun", Generative Art"]
summary: "Series 1 / Part 1"
---
![Crimson Sun](art/crimson-sun.png "Crimson Sun<br>Series 1 / Part 1")

{{< lead >}}
This is the first piece of artwork in my first art series. The initial seed of the idea was a sunflower rather than a sun. I had planned to create a circle and fill it with triangles which would represent the sunflower's seeds and see where that took me, but very quickly, especially as I started to colour the output in reddish tones, I realised that it looked less like a sunflower and more like a sun.
{{< /lead >}}

---

An interesting aspect of this work is the not-so-random placement and dimensions of the numerous triangles. A common strategy for this would be to use random number generation, however I wanted the placement to be much more homogeneous. Enter the [Halton Sequence](https://en.wikipedia.org/wiki/Halton_sequence), a deterministic sequence which appears random for most purposes, however the generated numbers are well distributed as they progress.

The Halton Sequence requires seeding with an integer "base" from which to start. Each base will result in a different sequence, much like seeding a random number generator. For example, base 2 results in the following sequence:

```
1⁄2,
1⁄4, 3⁄4,
1⁄8, 5⁄8, 3⁄8, 7⁄8,
1⁄16, 9⁄16, 5/16, 13/16, 3/16, 11/16, ...
```

And base 3 results in the following:

```
1/3, 2/3,
1/9, 4/9, 7/9, 2/9, 5/9, 8/9,
1/27, 10/27, 19/27, 4/27, 13/27, 22/27, 7/27, ...
```

Hopefully this gives a little insight into the algorithm which underlies this piece.
