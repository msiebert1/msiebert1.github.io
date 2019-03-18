---
layout: archive
title: ""
permalink: /kaepora/
author_profile: true
---

{% include base_path %}
<style>
.header {
  border-radius: 10px;  /* Rounded border */
  padding: 5px; /* Some padding */
  width: auto; /* Set a small width */
  height: 250px
}
</style>

<style>
.thumb {
  border: 1px solid #ddd; /* Gray border */
  border-radius: 4px;  /* Rounded border */
  padding: 5px; /* Some padding */
  width: auto; /* Set a small width */
  height: 400px;
}

/* Add a hover effect (blue shadow) */
.thumb:hover {
  box-shadow: 0 0 2px 1px;
  color: #5D3301;
}
</style>

<img src="http://msiebert1.github.io/images/Kaepora_Gaebora_Icon.png" alt="Kaepora Gaebora" align="bottom" class="header"/>
<img src="http://msiebert1.github.io/images/template_neon.png" alt="SN Ia" align="bottom" class="header"/>

<span style="color:#5D3301">kaepora</span>
=======

``kaepora`` is an open-source relational database for Type Ia Supernova spectra. For installation and example code please visit our [Read the Docs](https://kaepora.readthedocs.io/en/latest/index.html) page. You can download the source code from our [Github repository](https://github.com/msiebert1/kaepora) Below are links to download the most recent versions of the database:

|[kaepora_v1.db]() | The version used in [Siebert et al. 2019](https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS) |

After downloading, unzip and place the '.db' file in the /data folder of the repository. 

I am currently the only active developer regarding database architecture and user interaction. If you would like to contribute, please contact me and I will add you as a github collaborator. Let me know if you have suggestions for how I can improve this tool. If you have metadata that you think would be interesting to include, I am happy to help. 

<a target="_blank" href="https://msiebert1.github.io/files/maximum_light_all_dm15.pdf">
  <img src="https://msiebert1.github.io/images/maximum_light_all_dm15.png" alt="Maximum Light" class="thumb" align="right">
</a>

<span style="color:#7B5A18">Composite Spectra</span>
-----------------------

<!-- <body>
<a target="_blank" href="https://msiebert1.github.io/files/maximum_light_all_dm15.pdf">
  <img src="https://msiebert1.github.io/images/maximum_light_all_dm15.png" alt="Maximum Light" class="thumb">
</a>
<a target="_blank" href="https://msiebert1.github.io/files/dm15_split_max.pdf">
  <img src="https://msiebert1.github.io/images/dm15_split_max.png" alt="Dm15 Sequence" class="thumb">
</a>
<a target="_blank" href="https://msiebert1.github.io/files/si_region.pdf">
  <img src="https://msiebert1.github.io/images/si_region.png" alt="Si II Region" class="thumb">
</a>
<a target="_blank" href="https://msiebert1.github.io/files/color_curve.pdf">
  <img src="https://msiebert1.github.io/images/color_curve.png" alt="Color Curve" class="thumb">
</a>
</body> -->

Below are the composite spectra presented in [Siebert et al. 2019](https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS). All of these have been constructed using our "Gini-Weighting" method that is described in the paper. 

Each spectrum contains 7 columns of data. They are wavelength (A), flux (arbitrary), $1\sigma$ lower bootstrap sampling error (arbitrary), $1\sigma$ upper bootstrap sampling error (arbitrary), phase (rest-frame days), $\Delta m_{15}$ $(B)$ (mag), redshift, and the number of SNe per wavelength bin. At the top of each file we also include the SQL query that was used to generate the composite spectrum. Follow the link below to view the example composite spectrum from Figure 14 (right) in our paper.

[siebert_example_max_light](http://msiebert1.github.io/files/siebert_example_max_light_N=96_Nspec=142_phase=p0.11_dm15=1.11_z=0.013.txt)



<h3 style="color:#AE9A55">Sets of Composite Spectra from <a href="https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS">Siebert et al. 2019</a> </h3> 


<style>
.thumb_small {
  border: 1px solid #ddd; /* Gray border */
  border-radius: 4px;  /* Rounded border */
  padding: 5px; /* Some padding */
  width: auto; /* Set a small width */
  height: 50px;
}

/* Add a hover effect (blue shadow) */
.thumb_small:hover {
  box-shadow: 0 0 2px 1px;
  color: #5D3301;
}
</style>


| **All Composite Spectra**  | [siebert_all.tar](http://msiebert1.github.io/files/tarballs/siebert_all.tar)                                   |
| **Phase-Binned** <a target="_blank" href="https://msiebert1.github.io/files/phase_binned.pdf"><img src="https://msiebert1.github.io/images/phase_binned.png" alt="Maximum Light" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/phase_binned_zoom.pdf"><img src="https://msiebert1.github.io/images/phase_binned_zoom.png" alt="Phase Binned" class="thumb_small"></a>| [siebert_phase.tar](http://msiebert1.github.io/files/siebert_phase.tar) <br> [siebert_phase_2day.tar](http://msiebert1.github.io/files/tarballs/siebert_phase_2day.tar) |
| **Color Curve** <a target="_blank" href="https://msiebert1.github.io/files/color_curve.pdf"><img src="https://msiebert1.github.io/images/color_curve.png" alt="Color Curve" class="thumb_small"></a> | [siebert_color_curve.tar](http://msiebert1.github.io/files/tarballs/siebert_color_curve.tar)                   |
| **Maximum-Light $\Delta m_{15}$ $(B)$-Binned** <a target="_blank" href="https://msiebert1.github.io/files/maximum_light_all_dm15.pdf"><img src="https://msiebert1.github.io/images/maximum_light_all_dm15.png" alt="Dm15 Sequence" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/si_region.pdf"><img src="https://msiebert1.github.io/images/si_region.png" alt="Si II Region" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/color_dm15.pdf"><img src="https://msiebert1.github.io/images/color_dm15.png" alt="Color Dm15" class="thumb_small"></a> | [siebert_max_light_dm15.tar](http://msiebert1.github.io/files/tarballs/siebert_max_light_dm15.tar)             |
| **Phase-$\Delta m_{15}$ $(B)$ Grid** <a target="_blank" href="https://msiebert1.github.io/files/dm15_grid.pdf"><img src="https://msiebert1.github.io/images/dm15_grid.png" alt="Phase-Dm15 Grid" class="thumb_small"></a> | [siebert_grid.tar](http://msiebert1.github.io/files/tarballs/siebert_grid.tar) |
| **Template Comparisons** <a target="_blank" href="https://msiebert1.github.io/files/temp_m7_all.pdf"><img src="https://msiebert1.github.io/images/temp_m7_all.png" alt="-7 Days" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/temp_max_light_all.pdf"><img src="https://msiebert1.github.io/images/temp_max_light_all.png" alt="0 Days" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/temp_p7_all.pdf"><img src="https://msiebert1.github.io/images/temp_p7_all.png" alt="+7 Days" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/temp_p30_all.pdf"><img src="https://msiebert1.github.io/images/temp_p30_all.png" alt="+30 Days" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/temp_max_light_lowdm15.pdf"><img src="https://msiebert1.github.io/images/temp_max_light_lowdm15.png" alt="Slow-Declining" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/temp_max_light_middm15.pdf"><img src="https://msiebert1.github.io/images/temp_max_light_middm15.png" alt="Mid-Declining" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/temp_max_light_91bg.pdf"><img src="https://msiebert1.github.io/images/temp_max_light_91bg.png" alt="Fast-Declining" class="thumb_small"></a> | [siebert_template_comparisons.tar](http://msiebert1.github.io/files/tarballs/siebert_template_comparisons.tar) |
| **Host-Galaxy Morphology** <a target="_blank" href="https://msiebert1.github.io/files/host_m3_dm13.pdf"><img src="https://msiebert1.github.io/images/host_m3_dm13.png" alt="Host -3 Days" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/host_p3_dm13.pdf"><img src="https://msiebert1.github.io/images/host_p3_dm13.png" alt="Host +3 Days" class="thumb_small"></a> <a target="_blank" href="https://msiebert1.github.io/files/host_p9_dm13.pdf"><img src="https://msiebert1.github.io/images/host_p9_dm13.png" alt="Host +9 Days" class="thumb_small"></a> | [siebert_host.tar](http://msiebert1.github.io/files/tarballs/siebert_host.tar)                                 |