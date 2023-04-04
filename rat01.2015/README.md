### Rat01.2015



**<u>Species</u>**: Rat (Sprague Dawley, male, 9-10-week-old, ~300 g)<br/>Imaging: postmortem MR imaging (Unity Plus spectrometer (Varian, Palo Alto, CA) and a commercial imaging probe (Doty Scientific, Columbia, SC) mounted inside a 7-T, 89-mm diameter, vertical-bore magnet (Oxford Instruments, Oxford, UK)) of the upper airways (nose trough larynx, 125 µm resolution) and µCT imaging (Skyscan 1176 μCT, Microphotonics, Inc., Allentown, PA) of silicone cast of the trachea down to bronchiolar airways at 18-μm isotropic resolution. <br/>**<u>Segmentation</u>**: upper airways segmentation based on intensity thresholding followed by visual validation and repair. Prefiltering of airway cast images using background normalization and edge-preserving hybrid median filters to remove both low- and high-frequency noise, respectively, followed by semiautomatic segmentation, and manual evaluation and repair when necessary. <br/>**<u>Model</u>**: upper airways (nasal passages) down to several generations of conducting airways (17 ± 7 generations) resulting in 1277 outlets. <br/>**<u>Mesh</u>**: polyhedral mesh created in OpenFOAM, with each boundary facet assigned to a non-overlapping region for CFD/PBPK simulations. (1.80 million elements with 10.4 million nodes and 0.86 million surface facets). <br/>**<u>Simulation types</u>**: airflow, vapor exposure<br/><u>**Simulation parameters:**</u> minute volume = 0.217 L/min, 100 breaths/min, subchronic inhalation of 0.2 ppm (acrolein), 50 ppm (acetaldehyde), 1 ppm (formaldehyde).<br>**<u>Funding</u>**: NHLBI R01 HL073598 and NIEHS P01 ES011617<br/>**<u>Related publications:</u>** [Corley et al., 2015](https://doi.org/10.1093/toxsci/kfv071)



![rat1.2015](../README/rat01_2015.png)
