---
layout: page
title: "COSMOS-Web LRDs"
description: "Data and figures from Akins et al. (2024) paper on LRDs in COSMOS-Web."
img: assets/img/LRD_SEDs.png
importance: 1
category: Data
---

{% include figure.html path="assets/img/LRD_SEDs.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">
    Three example SED plots from Figure 4 of my paper.
</div>



All files hosted on my <a href="https://github.com/hollisakins/akins24_cw" target="_blank">GitHub</a>. 

<a href="https://github.com/hollisakins/akins24_cw/tree/main/seds" target="_blank">`seds/*_sed.pdf`</a>: This directory includes SED plots (as in Figures 4, and 5 in the paper) for all 434 objects in the sample. Note that for objects with F1800W coverage, we omit the ACS/F814W cutouts, and PRIMER-NIRCam cutouts are not shown, but the photometry is used. 

<a href="https://github.com/hollisakins/akins24_cw/blob/main/COSMOS-Web_LRDs.dat" target="_blank">`COSMOS-Web_LRDs.dat`</a>: This is an extended and machine-readable form of Table 1 in the paper, including coordinates, photometry (in all available bands), and derived physical properties (from QSO and galaxy fits) for all 434 objects in the sample. 

<a href="https://github.com/hollisakins/akins24_cw/blob/main/COSMOS-Web_LRDs_bol_LF.dat" target="_blank">`COSMOS-Web_LRDs_bol_LF.dat`</a>: This file provides the tabulated values for the LRD bolometric luminosity function from Figure 8. In the paper we provide the bolometric LF in 0.5 dex bins, here we additionally include the LF marginalized over the bin size, as described in the text. 

<a href="https://github.com/hollisakins/akins24_cw/blob/main/COSMOS-Web_LRDs_SMF.dat" target="_blank">`COSMOS-Web_LRDs_SMF.dat`</a>: This file provides the tabulated values for the LRD contribution to the stellar mass function from Figure 11. Format is identical to `COSMOS-Web_LRDs_bol_LF.dat`.  

<a href="https://github.com/hollisakins/akins24_cw/blob/main/COSMOS-Web_LRDs_stacked_SED.dat" target="_blank">`COSMOS-Web_LRDs_stacked_SED.dat`</a>: This file provides the median-stacked "maximal" SED model presented in Figure 13, from the X-ray to the radio. Wavelengths are in microns, and we provide flux density in µJy and monochromatic luminosity in solar luminosities. 

Happy to provide additional data, please reach out [over email](mailto:hollis.akins@gmail.com). 
If you use these data or intend to study these objects further, please cite [the COSMOS-Web LRD paper](https://ui.adsabs.harvard.edu/abs/2024arXiv240610341A/abstract):
```
Akins, H. B., Casey, C. M., Lambrides, E. et al. 2024, arXiv: 2406.10341
```

