---
layout: archive
title: ""
permalink: /kaepora/
author_profile: true
---

{% include base_path %}
kaepora <img src="http://msiebert1.github.io/images/Kaepora_Gaebora_Icon.png" alt="Kaepora Gaebora" width="200"/>
=======

``kaepora`` is an open-source relational database for Type Ia Supernova spectra. For installation and example code please visit the [github repository](https://github.com/msiebert1/kaepora). Below are links to download the most recent versions of the database:

[kaepora_v1.db]()

After downloading, unzip and place the '.db' file in the /data folder of the repository. 

Please let me know if you have suggestions for how I can improve this tool. If you have metadata that you think would be interesting to include, I am happy to help. 

## Composite Spectra

Below are the composite spectra presented in [Siebert et al. 2019](https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS). All of these have been constructed using our "Gini-Weighting" method that is described in the paper. 

Each spectrum contains 7 columns of data. They are wavelength (A), flux (arbitrary), $1\sigma$ lower bootstrap sampling error (arbitrary), $1\sigma$ upper bootstrap sampling error (arbitrary), phase, Dm15, redshift, and the number of SNe per wavelength bin. At the top of each file we also include the SQL query that was used to generate the composite spectrum. Follow the link below to view the example composite spectrum from Figure 14 in [Siebert et al. 2019](https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS). 

### Maximum-Light Example (see [Fig. 14](https://msiebert1.github.io/files/maximum_light_all_dm15.pdf))

[siebert_example_max_light_N=102_Nspec=170_phase=p0.01_dm15=1.13_z=0.014.txt](http://msiebert1.github.io/files/siebert_example_max_light_N=102_Nspec=170_phase=p0.01_dm15=1.13_z=0.014.txt)

### Everything from [Siebert et al. 2019](https://msiebert1.github.io/publication/2019-XX-XX-Siebert_2019_MNRAS)

### Phase-Binned (see [Figs. 17 and 18]())

### Maximum-Light $\Delta m_{15}$ $(B)$-Binned (see [Fig. 21]())

[siebert_max_light_dm15.tar](http://msiebert1.github.io/files/siebert_max_light_dm15.tar)

### Phase-$\Delta m_{15}$ $(B)$ Grid (see [Fig. 25]())

### Template Comparisons (see [Figs. 26, 28, 29, 30, 31, 32, and 33]())

### Host-Galaxy Morphology (see [Figs. 34, 35, and 36]())