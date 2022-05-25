---
where: Eurographics Symposium on Rendering 2020
title: Practical Product Path Guiding Using Linearly Transformed Cosines
authors: <b><a href="{{ "/" | relative_url }}">Stavros Diolatzis</a></b>, <a href="https://beltegeuse.github.io/research/">Adrien Gruson</a>, <a href="https://rgl.epfl.ch/people/wjakob/">Wenzel Jakob</a>, <a href="http://www.cim.mcgill.ca/~derek/">Derek Nowrouzezahrai</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
code: https://gitlab.inria.fr/sdiolatz/practical-product-path-guiding
presentation: https://youtu.be/CAa2APz1hUc?t=45
file: http://www-sop.inria.fr/reves/Basilic/2020/DGJND20/practical_product_path_guiding_authors.pdf
supplemental: https://repo-sam.inria.fr/fungraph/practical_product_path_guiding/
teaser_img: https://gitlab.inria.fr/sdiolatz/practical-product-path-guiding/uploads/54c1899936910a5acd754f005197e87e/rect5434.png
---

# Authors

<b><a href="{{ "/" | relative_url }}" >Stavros Diolatzis</a></b>, <a href="https://beltegeuse.github.io/research/">Adrien Gruson</a>, <a href="https://rgl.epfl.ch/people/wjakob/">Wenzel Jakob</a>, <a href="http://www.cim.mcgill.ca/~derek/">Derek Nowrouzezahrai</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>

<p float="left">
  <a href="http://www-sop.inria.fr/reves/Basilic/2020/DGJND20/practical_product_path_guiding_authors.pdf"><img src="../assets/file.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Paper</span></a>
  <a href="https://gitlab.inria.fr/sdiolatz/practical-product-path-guiding/"><img src="../assets/code.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Code</span></a>
  <a href="https://repo-sam.inria.fr/fungraph/practical_product_path_guiding/"><img src="../assets/supp.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Interactive Supplemental Page</span></a>
  <a href="https://youtu.be/CAa2APz1hUc?t=45"><img src="../assets/presentation.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Presentation</span></a>
</p>


![Teaser](https://gitlab.inria.fr/sdiolatz/practical-product-path-guiding/uploads/f58aa8b579ee7f414d07de6e0ac8c3e5/Capture.PNG)

# Abstract

<div style="text-align: justify">Path tracing is now the standard method used to generate realistic imagery in many domains, e.g., film, special effects, architecture etc. Path guiding has recently emerged as a powerful strategy to counter the notoriously long computation times required to render such images. We present a practical path guiding algorithm that performs product sampling, i.e., samples proportional to the product of the bidirectional scattering distribution function (BSDF) and incoming radiance. We use a spatial‐directional subdivision to represent incoming radiance, and introduce the use of Linearly Transformed Cosines (LTCs) to represent the BSDF during path guiding, thus enabling efficient product sampling. Despite the computational efficiency of LTCs, several optimizations are needed to make our method cost effective. In particular, we show how we can use vectorization, precomputation, as well as strategies to optimize multiple importance sampling and Russian roulette to improve performance. We evaluate our method on several scenes, demonstrating consistent improvement in efficiency compared to previous work, especially in scenes with significant glossy inter‐reflection.</div><br />

# Citation

```
@inproceedings{diolatzis2020practical,
  title={Practical Product Path Guiding Using Linearly Transformed Cosines},
  author={Diolatzis, Stavros and Gruson, Adrien and Jakob, Wenzel and Nowrouzezahrai, Derek and Drettakis, George},
  booktitle={Computer Graphics Forum},
  volume={39},
  number={4},
  pages={23--33},
  year={2020},
  organization={Wiley Online Library}
}
```
