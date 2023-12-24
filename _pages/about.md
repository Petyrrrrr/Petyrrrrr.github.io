---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently a fourth-year undergraduate student at [MIT](https://www.mit.edu/), studying Math, CS, and Statistics under the brilliant supervision of Prof. [Guy Bresler](https://www.mit.edu/~gbresler/) and Prof. [Nike Sun](https://math.mit.edu/~nsun/). I grew up in [Shanghai](https://www.urbandictionary.com/author.php?author=newyorkstinks), China, and went to [PRISMS](https://prismsus.org/) for high school in Princeton, NJ. A [list](../assets/Tianze_CV (5).pdf) of things I've done (awards, papers, talks, etc.) can be found [here](https://petyrrrrr.github.io/cv/). More detailed descriptions of my past projects is [here](../assets/Tianze_J_CV.pdf).

Research interests
======
I'm generally interested in statistics, computer science, combinatorics, and applied probability. A good amount of my past work happened at the intersection of theoretical CS and statistics where I explore insights from TCS to analyze non-asymptotic and high-dimensional inference problems. Last semester I spent some time reading about statistical physics inspired topics such as [spin glasses](https://arxiv.org/abs/2204.02909) (not nearly close to finishing this) and [Approximate Message Passing](https://arxiv.org/abs/2302.03682).

I'm also broadly interested in understanding '[intelligence](https://www.britannica.com/technology/artificial-intelligence)', despite my constant lag behind the [up-to-date](https://openreview.net/group?id=ICLR.cc/2024/Conference#tab-active-submissions) AI developments. I hope one day someone comes up with a unifying theory to explain why everything works (most notably SGD) in empirical ML without making unbearing assumptions or questionable approximations.



Some ongoing thoughts
======
* Compression and Prediction
  * We can write a formula that turns any nice compression coding into a decent prediction algorithm, but is there a generic lower bound saying that if compression is hard, so is prediction?
  * Can any efficient compression algorithm beat high-order Markov transition estimation on simple models such as HMMs?

* Learnability of Random Nets
  * It is known that fully random nets are easier to learn than adversarial nets. But what happens at the intermediate ‘smoothed’ settings?
  * We have a set of nice tools on proving lower bounds with feed-forward nets. How about transformers?

* Diffusion Models and Sampling
  * Can you run diffusion for a shorter amount of time and generate something that is 'pseudo'-valid (a.k.a. 'shortcut sampling')?
  * Can you shortcut starting at a noise ratio so low that efficient denoising algorithms start to function?

* Average-case Reductions and Hardness
  * We have some wonderful results matching moments with dense graphs from the Planted Clique model. How about in the sparse regime?
  * Is there some clever way to show that signal recovery in the planted community problem is strictly harder than detection?

