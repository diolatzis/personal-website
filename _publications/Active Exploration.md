---
where: ACM Transactions on Graphics 2022 (Presented @ SIGGRAPH 2022)
title: Active Exploration for Neural Global Illumination of Variable Scenes
authors: <b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://julienphilip.com/">Julien Philip</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
file: http://www-sop.inria.fr/reves/Basilic/2022/DPD22/active-exploration.pdf
webpage: https://repo-sam.inria.fr/fungraph/active-exploration/
teaser_vid: https://gitlab.inria.fr/fungraph/active-exploration/uploads/ad8cc0a87044ea417a82b1e132ce1abc/vid.mp4
code: https://github.com/diolatzis/active-exploration
---

# Authors

<b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://julienphilip.com/">Julien Philip</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>

<p float="left">
  <a href="http://www-sop.inria.fr/reves/Basilic/2022/DPD22/active-exploration.pdf"><img src="../assets/file.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Paper</span></a>
  <a href="https://github.com/diolatzis/active-exploration"><img src="../assets/code.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Code</span></a>
  <a href="https://repo-sam.inria.fr/fungraph/active-exploration/"><img src="../assets/supp.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Project Website</span></a>
</p>

![Teaser](http://www-sop.inria.fr/reves/Basilic/2022/DPD22/teaser.jpg)

# Abstract

<div style="text-align: justify">Neural rendering algorithms introduce a fundamentally new approach for photorealistic rendering, typically by learning a neural representation of illumination on large numbers of ground truth images. When training for a given variable scene, i.e., changing objects, materials, lights and viewpoint, the space D of possible training data instances quickly becomes unmanageable as the dimensions of variable parameters increase.

We introduce a novel Active Exploration method using Markov Chain Monte Carlo, which explores D , generating samples (i.e., ground truth renderings) that best help training and interleaves training and on-the-fly sample data generation. We introduce a self-tuning sample reuse strategy to minimize the expensive step of rendering training samples. We apply our approach on a neural generator that learns to render novel scene instances given an explicit parameterization of the scene configuration.

Our results show that Active Exploration trains our network much more efficiently than uniformly sampling, and together with our resolution enhancement approach, achieves better quality than uniform sampling at convergence. Our method allows interactive rendering of hard light transport paths (e.g., complex caustics) – that require very high samples counts to be captured – and provides dynamic scene navigation and manipulation, after training for 5-18 hours depending on required quality and variations.</div><br />

# Citation

```
@Article{DPD22,
  author       = "Diolatzis, Stavros and Philip, Julien and Drettakis, George",
  title        = "Active Exploration for Neural Global Illumination of Variable Scenes",
  journal      = "ACM Transactions on Graphics",
  year         = "2022",
  url          = "http://www-sop.inria.fr/reves/Basilic/2022/DPD22"
}
```
