---
layout: archive
permalink: /gallery/
title: "Gallery"
author_profile: true
redirect_from: 
  - /gallery
  - /gallery.html
---

Here are some pictures of the random processes that I'm interested in. Feel free to use any of them but please give credit. 

## Hyperbolic BBM

This is from an ongoing project on branching Brownian motion in hyperbolic space, modelled via the Poincaré disk model. Here, a single Brownian particle converges to a uniform point on the boundary. For BBM, the empirical measure converges to a random measure on the boundary. If we increase the branching rate, then this random measure becomes more spread out in an appropriate sense. In the picture, the branching rates left to right are $0.12, 0.4$ and $1$. 

<img src="/files/hyperbolic_BBM.png"  /> 

## BBM with space inhomogeneous branching rate

This is from the paper where we consider branching Brownian motion in two dimensions where the branching rate depends on the direction. The branching rate is maximised in the direction of the $x$-axis. In the picture, the different colours correspond to different choices of a parameter that controls how much smaller the branching is in directions other than the $x$-axis. Observe that the shape of the blob becomes less spherical for the smaller blobs where the inhomogeneity is more pronounced. 

<img src="/files/space_BBM_1.png"  /> 

Here are some realisations in different colours [sibBBM_2](/files/space_BBM_2.png) and [sibBBM_3](/files/space_BBM_3.png).

## Branching random walk on random trees 

Here we consider a branching random walk that takes place on a random tree. The random tree can be seen as a model for a random environment in very high dimension. As the process grows, it explores the tree. Here we plot the trace of the branching random walk.
This is a figure from our paper here <a href="https://arxiv.org/abs/2502.07363">arXiv [2502.07363]</a>. 

<img src="/files/brw_0.png"  /> 

The colours illustrate the distance from the root of the tree where the branching random walk is initiated. Here are some more realisations [brw_2](/files/brw_1.png), [brw_3](/files/brw_2.png), [brw_4](/files/brw_3.png).

## Marchal's tree growth and stable trees

Marchal's tree growth is a tree-valued Markov chain. Once rescaled properly, the trees converge as metric spaces. The limiting objects are called stable trees. Here are some simulations of Marchal's tree growth after 25000 steps for different values of alpha, they approximate stable trees. Here, alpha takes values in 2, 1.9, 1.6 and 1.4. When the parameter alpha is lowered the degree of some vertices in the tree becomes bigger and bigger leading to visual accumulation points. In the case alpha = 2, the stable tree is also called the Brownian continuum random tree (BCRT). 

<table>
<tr> 
<td> <img src="/files/stable_2_jpeg.jpg"  />  </td>
<td> <img src="/files/stable_19_jpeg.jpg" />  </td>
</tr>
<tr> 
<td> <img src="/files/stable_16_jpeg.jpg" />  </td>
<td> <img src="/files/stable_14_jpeg.jpg" />  </td>
</tr> 
</table>

You can download vectorised versions here: [1.4 stable tree](/files/stable_14.pdf), [1.6 stable tree](/files/stable_16.pdf), [1.9 stable tree](/files/stable_19.pdf), [BCRT](/files/stable_2.pdf). Also, [here is a GIF](/files/marchal.gif) of a breadth first search of one of those trees.

## Dynamic Widom-Rowlinson model

The Widom-Rowlinson model is a stochastic model for liquid-vapour transitions. Mathematically, it is a point process defined on the plane of points of two different colours. Each point comes with a disk of diameter one, points of different colour must not overlap whereas points of the same colour ignore each other. Projecting on one colour yields the model for the liquid-vapour transition. This (random) model comes with a stochastic dynamic where points die at rate 1 and are born at rate z as long the birth is compatible with the existent configuration. 

I don't research on this model myself but I learned about it in a course of Frank den Hollander at the [PIMS summer school 2022](https://secure.math.ubc.ca/Links/ssprob22/courses.php). 

<img src="/files/WR_04_jpeg.jpg"  /> 

Here are some GIFs of the dynamics, (large files, ~20MB each): [intensity 0.025](/files/dynamic_WR_025.gif), [intensity 0.05](/files/dynamic_WR_05.gif), [intensity 0.075](/files/dynamic_WR_075.gif), [intensity 0.1](/files/dynamic_WR_1.gif).