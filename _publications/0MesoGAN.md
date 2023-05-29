---
where: Computer Graphics Forum 2023
title: 'MesoGAN: Generative Neural Reflectance Shells'
authors: <b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://jannovak.info/">Jan Novák</a>, <a href="https://research.nvidia.com/person/fabrice-rousselle">Fabrice Rouselle</a>, <a href="http://granskog.xyz/">Jonathan Granskog</a>, <a href="https://research.nvidia.com/person/miika-aittala">Miika Aittala</a>, <a href="https://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
file: http://www-sop.inria.fr/reves/Basilic/2023/DNRGARD23/mesogan_authors.pdf
webpage: https://repo-sam.inria.fr/fungraph/mesogan/
teaser_vid: https://repo-sam.inria.fr/fungraph/mesogan/static/resources/living.mp4
---

# Authors

<b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://jannovak.info/">Jan Novák</a>, <a href="https://research.nvidia.com/person/fabrice-rousselle">Fabrice Rouselle</a>, <a href="http://granskog.xyz/">Jonathan Granskog</a>, <a href="https://research.nvidia.com/person/miika-aittala">Miika Aittala</a>, <a href="https://cseweb.ucsd.edu/~ravir/">Ravi Ramamoorthi</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
<p float="left">
  <a href="http://www-sop.inria.fr/reves/Basilic/2023/DNRGARD23/mesogan_authors.pdf"><img src="../assets/file.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Paper</span></a>
  <a href="https://repo-sam.inria.fr/fungraph/mesogan/"><img src="../assets/supp.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Project Website</span></a>
</p>

![Teaser](https://repo-sam.inria.fr/fungraph/mesogan/static/resources/teaser.png)

# Abstract

<div style="text-align: justify">We introduce MesoGAN, a model for generative 3D neural textures. This new graphics primitive represents mesoscale appearance by combining the strengths of generative adversarial networks (StyleGAN) and volumetric neural field rendering.

The primitive can be applied to surfaces as a neural reflectance shell; a thin volumetric layer above the surface with appearance parameters defined by a neural network. To construct the neural shell, we first generate a 2D feature texture using StyleGAN with carefully randomized Fourier features to support arbitrarily sized textures without repeating artifacts.

We augment the 2D feature texture with a learned height feature, which aids the neural field renderer in producing volumetric parameters from the 2D texture. To facilitate filtering, and to enable end-to-end training within memory constraints of current hardware, we utilize a hierarchical texturing approach and train our model on multi-scale synthetic datasets of 3D mesoscale structures.

We propose one possible approach for conditioning MesoGAN on artistic parameters (e.g., fiber length, density of strands, lighting direction) and demonstrate and discuss integration into physically based renderers.</div><br />

# Citation

```
@Article{DNRGARD23,
  author       = "Diolatzis, Stavros and Novak, Jan and Rousselle, Fabrice and Granskog, Jonathan and Aittala, Miika and Ramamoorthi, Ravi and Drettakis, George",
  title        = "MesoGAN: Generative Neural Reflectance Shells",
  journal      = "Computer Graphics Forum",
  year         = "2023",
  url          = "http://www-sop.inria.fr/reves/Basilic/2023/DNRGARD23"
}
```
