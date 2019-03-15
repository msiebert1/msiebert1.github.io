---
layout: archive
title: ""
permalink: /kaepora/
author_profile: true
---

{% include base_path %}
<img src="http://msiebert1.github.io/images/Kaepora_Gaebora_Icon.png" alt="Kaepora Gaebora" align="bottom" width="200"/>

<span style="color:#5D3301">kaepora</span>
=======

``kaepora`` is an open-source relational database for Type Ia Supernova spectra. For installation and example code please visit our [Read the Docs](https://kaepora.readthedocs.io/en/latest/index.html) page. You can download the source code from our [Github repository](https://github.com/msiebert1/kaepora) Below are links to download the most recent versions of the database:

|[kaepora_v1.db]() | The version used in [Siebert et al. 2019](https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS) |

After downloading, unzip and place the '.db' file in the /data folder of the repository. 

I am currently the only active developer regarding database architecture and user interaction. If you would like to contribute, please contact me and I will add you as a github collaborator. Let me know if you have suggestions for how I can improve this tool. If you have metadata that you think would be interesting to include, I am happy to help. 

<span style="color:#7B5A18">Composite Spectra</span>
-----------------------

<style>
img {
  border: 1px solid #ddd; /* Gray border */
  border-radius: 4px;  /* Rounded border */
  padding: 5px; /* Some padding */
  width: 250; /* Set a small width */
}

/* Add a hover effect (blue shadow) */
img:hover {
  box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}
</style>
<body>
<a target="_blank" href="https://msiebert1.github.io/files/maximum_light_all_dm15.pdf">
  <img src="https://msiebert1.github.io/images/maximum_light_all_dm15.png" alt="Maximum Light" height="250">
</a>
</body>
<body>
<a target="_blank" href="https://msiebert1.github.io/files/dm15_split_max.pdf">
  <img src="https://msiebert1.github.io/images/dm15_split_max.png" alt="Dm15 Sequence" height="250">
</a>
</body>
<body>
<a target="_blank" href="https://msiebert1.github.io/files/si_region.pdf">
  <img src="https://msiebert1.github.io/images/si_region.png" alt="Dm15 Sequence" height="250">
</a>
</body>
<body>
<a target="_blank" href="https://msiebert1.github.io/files/color_curve.pdf">
  <img src="https://msiebert1.github.io/images/color_curve.png" alt="Dm15 Sequence" height="250">
</a>
</body>

Below are the composite spectra presented in [Siebert et al. 2019](https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS). All of these have been constructed using our "Gini-Weighting" method that is described in the paper. 

Each spectrum contains 7 columns of data. They are wavelength (A), flux (arbitrary), $1\sigma$ lower bootstrap sampling error (arbitrary), $1\sigma$ upper bootstrap sampling error (arbitrary), phase (rest-frame days), $\Delta m_{15}$ $(B)$ (mag), redshift, and the number of SNe per wavelength bin. At the top of each file we also include the SQL query that was used to generate the composite spectrum. Follow the link below to view the example composite spectrum from Figure 14 in our paper. 

<h3 style="color:#AE9A55">Maximum-Light Example (<a href="https://msiebert1.github.io/files/maximum_light_all_dm15.pdf"> Fig. </a>) </h3>

[siebert_example_max_light](http://msiebert1.github.io/files/siebert_example_max_light_N=102_Nspec=170_phase=p0.01_dm15=1.13_z=0.014.txt)

<h3 style="color:#AE9A55">Sets of Composite Spectra from <a href="https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS">Siebert et al. 2019</a> </h3> 

| **All Composite Spectra**                                               | [siebert_all.tar](http://msiebert1.github.io/files/siebert_all.tar)                                   |
| **Phase-Binned (see [Fig.]())**                                         | [siebert_phase.tar](http://msiebert1.github.io/files/siebert_phase.tar) <br> [siebert_phase_2day.tar](http://msiebert1.github.io/files/siebert_phase_2day.tar) |
| **Color Curve (see [Fig.]())**                                          | [siebert_color_curve.tar](http://msiebert1.github.io/files/siebert_color_curve.tar)                   |
| **Maximum-Light $\Delta m_{15}$ $(B)$-Binned (see [Fig.]())**           | [siebert_max_light_dm15.tar](http://msiebert1.github.io/files/siebert_max_light_dm15.tar)             |
| **Phase-$\Delta m_{15}$ $(B)$ Grid (see [Fig.]())**                     | [siebert_grid.tar]()                                                                                  |
| **Template Comparisons (see [Fig.]())**                                 | [siebert_template_comparisons.tar](http://msiebert1.github.io/files/siebert_template_comparisons.tar) |
| **Host-Galaxy Morphology (see [Fig.]())**                               | [siebert_host.tar](http://msiebert1.github.io/files/siebert_host.tar)                                 |