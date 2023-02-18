Rat1.2015

Species: Rat (Sprague Dawley, male, 9-10-week-old, ~300 g)
Imaging: postmortem MR imaging (Unity Plus spectrometer (Varian, Palo Alto, CA) and a commercial imaging probe (Doty Scientific, Columbia, SC)  mounted inside a 7-T, 89-mm diameter, vertical-bore magnet (Oxford Instruments, Oxford, UK)) of the upper airways (nose trough larynx, 125 µm resolution) and µCT imaging (Skyscan 1176 μCT, Microphotonics, Inc., Allentown, PA) of silicone cast of the trachea down to bronchiolar airways at 18-μm isotropic resolution. 
Segmentation: upper airways segmentation based on intensity thresholding followed by visual validation and repair. Prefiltering of airway cast images using background normalization and edge-preserving hybrid median filters to remove both low- and high-frequency noise, respectively, followed by semiautomatic segmentation, and manual evaluation and repair when necessary.
Model: upper airways (nasal passages) down to several generations of conducting airways (17 ± 7 generations) resulting in 1277 outlets. 
Mesh: polyhedral mesh created in OpenFOAM, with each boundary facet assigned to a non-overlapping region for CFD/PBPK simulations. (1.80 million elements with 10.4 million nodes and 0.86 million surface facets). 
Simulation types: airflow, vapor exposure
Funding: NHLBI R01 HL073598 and NIEHS P01 ES011617
Related publications: Corley et al., 2015 (https://doi.org/10.1093/toxsci/kfv071)
