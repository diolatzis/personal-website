---
where: SIGGRAPH 2024
title: 'N-Dimensional Gaussians for Fitting of High Dimensional Functions'
authors: <b><a href="https://sdiolatz.info">Stavros Diolatzis</a></b>, <a href="https://alphanew.net/">Tobias Zirr</a>, <a href="https://www.alexku.me/">Alexandr Kuznetsov</a>, <a href="https://grgkopanas.github.io/">Georgios Kopanas</a>, <a href="http://kaplanyan.com/">Anton Kaplanyan</a>
file: https://www.sdiolatz.info/ndg-fitting/static/files/ngd-paper-compressed.pdf
webpage: https://www.sdiolatz.info/ndg-fitting/
teaser_vid: https://www.sdiolatz.info/ndg-fitting/static/videos/cd.mp4
---

# Authors

<a href="https://sdiolatz.info">Stavros Diolatzis</a>, <a href="https://alphanew.net/">Tobias Zirr</a>, <b><a href="https://www.alexku.me/">Alexandr Kuznetsov</a></b>, <a href="https://grgkopanas.github.io/">Georgios Kopanas</a>, <a href="http://kaplanyan.com/">Anton Kaplanyan</a>
<p float="left"> 
	<a href="https://www.sdiolatz.info/ndg-fitting/static/files/ngd-paper-compressed.pdf"><img src="../assets/file.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Paper</span></a>
	<a href="https://www.sdiolatz.info/ndg-fitting/"><img src="../assets/supp.png" width="30" style="vertical-align:middle;margin:0px 5pt 0px"/><span>Project Website</span></a>
</p>

![Teaser](https://www.sdiolatz.info/ndg-fitting/static/images/teaser.png)

# Abstract

<div style="text-align: justify">In the wake of many new ML-inspired approaches for reconstructing and representing high-quality 3D content, recent hybrid and explicitly learned representations exhibit promising performance and quality characteristics. However, their scaling to higher dimensions is challenging, e.g. when accounting for dynamic content with respect to additional parameters such as material properties, illumination, or time. In this paper, we tackle these challenges for an explicit representations based on Gaussian mixture models. With our solutions, we arrive at efficient fitting of compact N-dimensional Gaussian mixtures and enable efficient evaluation at render time: For fast fitting and evaluation, we introduce a high-dimensional culling scheme that efficiently bounds N-D Gaussians, inspired by Locality Sensitive Hashing. For adaptive refinement yet compact representation, we introduce a loss-adaptive density control scheme that incrementally guides the use of additional capacity towards missing details. With these tools we can for the first time represent complex appearance that depends on many input dimensions beyond position or viewing angle within a compact, explicit representation optimized in minutes and rendered in milliseconds.</div><br />
