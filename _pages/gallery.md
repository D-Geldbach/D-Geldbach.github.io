---
layout: archive
permalink: /gallery/
title: "Gallery"
author_profile: true
redirect_from: 
  - /gallery
  - /gallery.html
---

Here are some pictures of the random processes that I'm interested in. Feel free to use any of them but please give credit. This page is currently being updated.

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

You can download vectorised versions here: [1.4 stable tree](/files/stable_14.pdf), [1.6 stable tree](/files/stable_16.pdf), [1.9 stable tree](/files/stable_19.pdf), [BCRT](/files/stable_2.pdf).

## Growth on trees

Here is a picture of a random particle process growing on a random Bienaymé-Galton-Watson tree. A characteristic property of this process is that it has a frontier of particles, i.e. particles which are next to unoccupied sites. In the picture, these particles are coloured in light blue. This frontier moves outward with time.

<img src="/files/growth_on_trees_1.png"  /> 

And here are some gifs of the dynamics, emphasising the frontier - movies 3 and 4 are different from movies 1 and 2: [movie 1](/files/growth_on_trees_movie_1.gif), [movie 2](/files/growth_on_trees_movie_2.gif), [movie 3](/files/growth_on_trees_movie_3.gif), [movie 4](/files/growth_on_trees_movie_4.gif). (large files, ~20MB each)

## Angle dependent Branching Brownian Motion

In this model we consider a branching Brownian motion (BBM) in the 2-dimensional plane where the branching rate depends on the angle towards the origin. Here are two simulations of this process: [movie 1](/files/aBBM_movie_1.gif), [movie 2](/files/aBBM_movie_2.gif).

## Dynamic Widom-Rowlinson model

The Widom-Rowlinson model is a stochastic model for liquid-vapour transitions. Mathematically, it is a point process defined on the plane of points of two different colours. Each point comes with a disk of diameter one, points of different colour must not overlap whereas points of the same colour ignore each other. Projecting on one colour yields the model for the liquid-vapour transition. This (random) model comes with a stochastic dynamic where points die at rate 1 and are born at rate z as long the birth is compatible with the existent configuration. 

I don't research on this model myself but I learned about it in a course of Frank den Hollander at the [PIMS summer school 2022](https://secure.math.ubc.ca/Links/ssprob22/courses.php). 

<img src="/files/WR_04_jpeg.jpg"  /> 

Here are some GIFs of the dynamics, (large files, ~20MB each): [intensity 0.025](/files/dynamic_WR_025.gif), [intensity 0.05](/files/dynamic_WR_05.gif), [intensity 0.075](/files/dynamic_WR_075.gif), [intensity 0.1](/files/dynamic_WR_1.gif).