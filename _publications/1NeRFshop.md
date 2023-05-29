---
where: ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games 2023
title: 'NeRFshop: Interactive Editing of Neural Radiance Fields'
authors: <a href="https://clementjambon.github.io/">Clément Jambon</a>, <a href="https://www.cg.tuwien.ac.at/staff/BernhardKerbl">Bernhard Kerbl</a>, <a href="https://grgkopanas.github.io/">Georgios Kopanas</a>, <b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://people.mpi-inf.mpg.de/~tleimkue/">Thomas Leimkühler</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>
file: http://www-sop.inria.fr/reves/Basilic/2023/JKKDLD23/nerfshop.pdf
webpage: https://repo-sam.inria.fr/fungraph/nerfshop/
teaser_vid: https://repo-sam.inria.fr/fungraph/nerfshop/content/videos/lego-cabin.mp4
code: https://github.com/graphdeco-inria/nerfshop
---

# Authors

<a href="https://clementjambon.github.io/">Clément Jambon</a>, <a href="https://www.cg.tuwien.ac.at/staff/BernhardKerbl">Bernhard Kerbl</a>, <a href="https://grgkopanas.github.io/">Georgios Kopanas</a>, <b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://people.mpi-inf.mpg.de/~tleimkue/">Thomas Leimkühler</a>, <a href="http://www-sop.inria.fr/members/George.Drettakis/">George Drettakis</a>

<p float="left">
  <a href="http://www-sop.inria.fr/reves/Basilic/2023/JKKDLD23/nerfshop.pdf"><img src="../assets/file.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Paper</span></a>
  <a href="https://github.com/graphdeco-inria/nerfshop"><img src="../assets/code.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Code</span></a>
  <a href="https://repo-sam.inria.fr/fungraph/nerfshop/"><img src="../assets/supp.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Project Website</span></a>
</p>

![Teaser](http://www-sop.inria.fr/reves/Basilic/2023/JKKDLD23/teaser.jpg)

# Abstract

<div style="text-align: justify">Neural Radiance Fields (NeRFs) have revolutionized novel view synthesis for captured scenes, with recent methods allowing interactive free-viewpoint navigation and fast training for scene reconstruction. However, the implicit representations used by these methods — often including neural networks and complex encodings — make them difficult to edit. Some initial methods have been proposed, but they suffer from limited editing capabilities and/or from a lack of interactivity, and are thus unsuitable for interactive editing of captured scenes.

We tackle both limitations and introduce NeRFshop, a novel end-to-end method that allows users to interactively select and deform objects through cage-based transformations. NeRFshop provides fine scribble-based user control for the selection of regions or objects to edit, semi-automatic cage creation, and interactive volumetric manipulation of scene content thanks to our GPU-friendly two-level interpolation scheme. Further, we introduce a preliminary approach that reduces potential resulting artifacts of these transformations with a volumetric membrane interpolation technique inspired by Poisson image editing and provide a process that "distills" the edits into a standalone NeRF representation..</div><br />

# Citation

```
@Article{JKKDLD23,
  author       = "Jambon, Cl\'ement and Kerbl, Bernhard and Kopanas, Georgios and Diolatzis, Stavros and Leimk{\"u}hler, Thomas and Drettakis, George",
  title        = "NeRFshop: Interactive Editing of Neural Radiance Fields",
  journal      = "Proceedings of the ACM on Computer Graphics and Interactive Techniques",
  number       = "1",
  volume       = "6",
  month        = "May",
  year         = "2023",
  url          = "http://www-sop.inria.fr/reves/Basilic/2023/JKKDLD23"
}
```
