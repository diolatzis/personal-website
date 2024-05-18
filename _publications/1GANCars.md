---
where: Eurographics 2024
title: 'Physically-based Lighting of 3D Generative Models of Cars'
authors: <a href="https://nviolante25.github.io/">Nicolás Violante</a>, <a href="https://albangauthier.github.io/">Alban Gauthier</a>, <b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://people.mpi-inf.mpg.de/~tleimkue/">Thomas Leimkühler</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
file: https://repo-sam.inria.fr/fungraph/lighting-3d-generative-cars/lighting_3D_generative_cars.pdf
webpage: https://repo-sam.inria.fr/fungraph/lighting-3d-generative-cars
teaser_vid: https://repo-sam.inria.fr/fungraph/lighting-3d-generative-cars/content/videos/session.mp4
---

# Authors

<a href="https://nviolante25.github.io/">Nicolás Violante</a>, <a href="https://albangauthier.github.io/">Alban Gauthier</a>, <b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://people.mpi-inf.mpg.de/~tleimkue/">Thomas Leimkühler</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
<p float="left"> 
	<a href="https://repo-sam.inria.fr/fungraph/lighting-3d-generative-cars/lighting_3D_generative_cars.pdf"><img src="../assets/file.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Paper</span></a>
	<a href="https://repo-sam.inria.fr/fungraph/lighting-3d-generative-cars"><img src="../assets/supp.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Project Website</span></a>
</p>

![Teaser](https://repo-sam.inria.fr/fungraph/lighting-3d-generative-cars/content/images/teaser.png)

# Abstract

<div style="text-align: justify">Recent work has demonstrated that Generative Adversarial Networks (GANs) can be trained to generate 3D content from 2D image collections, by synthesizing features for neural radiance field rendering. However, most such solutions generate radiance, with lighting entangled with materials. This results in unrealistic appearance, since lighting cannot be changed and view-dependent effects such as reflections do not move correctly with the viewpoint. In addition, many methods have difficulty for full, 360◦ rotations, since they are often designed for mainly front-facing scenes such as faces

We introduce a new 3D GAN framework that addresses these shortcomings, allowing multi-view coherent 360◦ viewing and at the same time relighting for objects with shiny reflections, which we exemplify using a car dataset. The success of our solution stems from three main contributions. First, we estimate initial camera poses for a dataset of car images, and then learn to refine the distribution of camera parameters while training the GAN. Second, we propose an efficient Image-Based Lighting model, that we use in a 3D GAN to generate disentangled reflectance, as opposed to the radiance synthesized in most previous work. The material is used for physically-based rendering with a dataset of environment maps. Third, we improve the 3D GAN architecture compared to previous work and design a careful training strategy that allows effective disentanglement. Our model is the first that generatea variety of 3D cars that are multi-view consistent and that can be relit interactively with any environment map</div><br />

# Citation

```
@Article{violante2024lighting_3D_cars,
      author       = {Violante, Nicolás and Gauthier, Alban, and Diolatzis, Stavros and Leimkühler, Thomas and Drettakis, George},
      title        = {Physically-Based Lighting for 3D Generative Models of Cars},
      journal      = {Computer Graphics Forum (Proceedings of the Eurographics Conference)},
      number       = {2},
      volume       = {43},
      month        = {April},
      year         = {2024},
      url          = {https://repo-sam.inria.fr/fungraph/lighting-3d-generative-cars/}
}
```
