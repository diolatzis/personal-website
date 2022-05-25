---
where: ACM Transactions on Graphics 2022 (To be presented at SIGGRAPH 2022)
title: Active Exploration for Neural Global Illumination of Variable Scenes
authors: <b><a href="{{ "/" | relative_url }}">Stavros Diolatzis</a></b>, <a href="https://julienphilip.com/">Julien Philip</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
file: http://www-sop.inria.fr/reves/Basilic/2022/DPD22/active-exploration.pdf
webpage: https://repo-sam.inria.fr/fungraph/active-exploration/
teaser: https://gitlab.inria.fr/sdiolatz/active-exploration-neural-rendering-paper/uploads/21177273df3bb26cad635fdf5a804b55/image271.png
---

# Authors

<b><a href="{{ "/" | relative_url }}">Stavros Diolatzis</a></b>, <a href="https://julienphilip.com/">Julien Philip</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>

<p float="left">
  <a href="http://www-sop.inria.fr/reves/Basilic/2022/DPD22/active-exploration.pdf"><img src="../assets/file.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Paper</span></a>
  <a href="https://repo-sam.inria.fr/fungraph/active-exploration/"><img src="../assets/supp.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Project Website</span></a>
</p>

![Teaser](http://www-sop.inria.fr/reves/Basilic/2022/DPD22/teaser.jpg)

# Abstract

<div style="text-align: justify">Path tracing is now the standard method used to generate realistic imagery in many domains, e.g., film, special effects, architecture etc. Path guiding has recently emerged as a powerful strategy to counter the notoriously long computation times required to render such images. We present a practical path guiding algorithm that performs product sampling, i.e., samples proportional to the product of the bidirectional scattering distribution function (BSDF) and incoming radiance. We use a spatial‐directional subdivision to represent incoming radiance, and introduce the use of Linearly Transformed Cosines (LTCs) to represent the BSDF during path guiding, thus enabling efficient product sampling. Despite the computational efficiency of LTCs, several optimizations are needed to make our method cost effective. In particular, we show how we can use vectorization, precomputation, as well as strategies to optimize multiple importance sampling and Russian roulette to improve performance. We evaluate our method on several scenes, demonstrating consistent improvement in efficiency compared to previous work, especially in scenes with significant glossy inter‐reflection.</div><br />

![Variations](https://gitlab.inria.fr/sdiolatz/active-exploration-neural-rendering-paper/uploads/c0f15873aa0e2977ba7ff08ec179b9b8/variations.png)

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
