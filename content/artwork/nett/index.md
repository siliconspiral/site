---
title: "Nett"
date: 2024-11-02
draft: false
description: "Nett"
tags: ["Nett", Generative Art"]
summary: "Series 1 / Part 4"
---
![Nett](art/nett.png "Nett<br>Series 1 / Part 4")

{{< lead >}}
This is the fourth piece in this series. As usual, I started with a small seed of an idea and grew things from there. In this case, I started with a simulation of the flocking of birds! Over past years, I've enjoyed writing a few graphical programs that simulate the behaviour and motion of a flock of birds which follow a lead bird whilst at the same time keeping their distance from each other. The end result is a natural and attractive swarming of dots, which led to this piece.
{{< /lead >}}

For a better idea of flocking algorithms, have a look at this classic Artificial Life program called [Boids](https://en.wikipedia.org/wiki/Boids). In starting with a simulation, I wanted to depart a little from my artworks to date which more explicitly draw from equations, and I liked the idea of simply giving a bunch of dots a few simple rules, letting them loose, and seeing if art comes out at the other end!

My birds are very simple. I lined them up in a regular grid then placed a bunch of fixed invisible "magnets" randomly on the screen. The birds are attracted to every magnet in equal measure which causes them to accelerate and move. The birds make no attempt to keep away from each other. I also modelled a bit of drag slowing the birds down as though there were air friction.

The program steps through time, frame by frame, and in each frame the acceleration is calculated, drag is applied, a new velocity calculated, and the bird is moved.

My first output yielded a bunch of dots which, although had some character, still needed a lot of work to get to something a bit more interesting and fleshed out:

![](/img/nett-1.png "Just Dots")

I then thought about "joining the dots" to see what that would look like:

![](/img/nett-2.png "Just a Net")

In joining the dots, I felt as though I was folding a tangible structure like a fishing net, or a napkin. With this in mind, and playing with variations of colour, I ended up with the final result. It occurred to me that, rather than looking like a flock of birds, it has more of an organic fleshy feel like a colourful sea creature such as the [Red Cushion Starfish](https://en.wikipedia.org/wiki/Porania_pulvillus):

![](https://upload.wikimedia.org/wikipedia/commons/5/50/Porania_pulvillus.jpg "Red Cushion Starfish")

I mentioned that the image is built up by stepping through time, frame by frame, as the birds move toward the magnets. Here is a video demonstrating that:

<center>
<video width="100%" controls>
    <source src="/vid/nett.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
</center>

Finally, why the name *Nett*? At some point the piece started to look like a fishing net. So why the odd spelling? As I was finishing this work, I was on family holiday in a beautiful part of Bavaria in Germany. The German language has the word *nett* which means *nice*, which I felt was a fitting name for this piece.
