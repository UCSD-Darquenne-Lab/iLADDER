# iLADDER

#### **In-silico LADDER: Lung Aerosol Dosimetry for Drug and Environmental Research**

This GitHub repository contains lung models geometries developed and used by the in-silico LADDER team of investigators

**This project is also available on [SimTK](https://simtk.org/projects/insilico_ladder).** 

The development of predictive aerosol dosimetry models has been a major focus of environmental toxicology and pharmaceutical health research for decades. Simplified compartmental and one-dimensional models have been successful in predicting overall deposition but fail to accurately predict local deposition. Computational fluid-particle dynamics (CFPD) has been extensively used to study flow patterns and aerosol transport in idealistic, physiologically realistic and more recently patient-specific models of lung airways. To date, the challenge of predicting the deposition of inhaled aerosols under disease conditions is largely unmet. While 3D CFPD models provide the capability of including subject-specific lung abnormalities resulting from respiratory diseases, they typically only include a sub-region of the lung because of the prohibitive computational costs compared to simplified models.

The in-silico LADDER project aims at developing aerosol dosimetry multiscale models through a step-wise, modular integration of 3D computational fluid dynamic airflow and aerosol tracking CT-based lung models that extend from the nose and mouth to several generations of the conducting airways with each most distal 3D pulmonary airway bi-directionally coupled with lower dimensional airflow, aerosol transport, and tissue mechanics models to describe aerosol transport and deposition over the full respiratory system. The expected deliverables will be a suite of modular, multiscale models and standardized approaches for new model development that can be used by researchers, risk assessors, or clinicians to predict aerosol deposition in the lungs under healthy and disease conditions in addition to the underlying algorithms and framework for effective linking of user-defined, personalized aerosol dosimetry models in the future. As modules are fully validated and published, they will be made available to the research community on the SimTK platform.

**This project is funded by grant U01-ES028669 from the National Institutes of Health (NIH). The curation of lung models and meshes is funded by the Environmental Protection Agency (EPA) through service agreement 68HE0B22P0365.**



<hr>



### Available Lung Models

Detailed metadata  and information for each model is available below this table:



| Sample ID and STL                                            | Basic Info                                  | Species | Mesh                                                         | Reference                                                    | Model                                                        |
| ------------------------------------------------------------ | ------------------------------------------- | ------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [human01](human01/)                                          | female, 84 yrs                              | Human   | Yes<br>[Nasal](https://drive.google.com/file/d/1imDkstz6MvFbS1XG7UXyt2q_zp3NRwv8/view?usp=sharing)<br>[Oral](https://drive.google.com/file/d/14kVG9JjSKrwelTGwtYfIpHi3pSbHiKvM/view?usp=sharing) | [Corley et al., 2012](https://doi.org/10.1093/toxsci/kfs168);<br>[Corley et al., 2015](https://doi.org/10.1093/toxsci/kfv071) | <img src="README/human01.png" alt="human01" style="zoom:50%;" /> |
| [human02.2016](https://drive.google.com/file/d/1CxhNb389b_hMd4hZ-GEovwC3JzM-6Da8/view?usp=sharing) | male, 35 yrs, 68kg, 170cm tall              | Human   | [Yes](https://drive.google.com/file/d/1pSTQOJ6WIYSJZLzZwNXRd3gVWfoHzLsd/view?usp=sharing) | [Kabilan et al., 2016](https://doi.org/10.1016/j.jaerosci.2016.01.011) | <img src="README/human02.png" alt="human01" style="zoom:50%;" /> |
| [human02.2021](human02.2021/)                                | male, 35 yrs, 68kg, 170cm tall              | Human   | [Yes](https://drive.google.com/file/d/1qokg3Ck713OAhM-b5bSqltqKwNM5AIou/view?usp=sharing) | [Corley et al., 2021](https://doi.org/10.1093/toxsci/kfab062) |                                                              |
| [human03](human03/)                                          | male, 18 yrs, 74kg                          | Human   | [Yes](https://drive.google.com/file/d/1AU6V0V2sPjrHRY7ZEx9yAmSDR2nz_Pla/view?usp=sharing) | [Corley et al., 2015](https://doi.org/10.1093/toxsci/kfv071) | <img src="README/human03.png" alt="human01" style="zoom:120%;" /> |
| [monkey01](monkey01/)                                        | male, 6 months                              | Monkey  | [Yes](https://drive.google.com/file/d/17Wy2Yqs-3d-9JfDlDnKDyqF4Q1-bwhVm/view?usp=sharing) | [Corley et al.  2012](https://academic.oup.com/toxsci/article/128/2/500/1649982) | ![monkey01](README/monkey01.png)                             |
| [rat01.2012](rat01.2012/)                                    | Sprague Dawley, male, 9-10-week-old, ~300 g | Rat     | [Yes](https://drive.google.com/file/d/1ZOuzDvd2aSElZ5Xp92iBd6pCLzU0BiZh/view?usp=sharing) | [Corley et al., 2012](https://doi.org/10.1093/toxsci/kfs168) | ![rat01.2012](README/rat01_2012.jpg)                         |
| [rat01.2015](rat01.2015/)                                    | Sprague Dawley, male, 9-10-week-old, ~300 g | Rat     | [Yes](https://drive.google.com/file/d/1qoqnwQ-kuKldkr-5Al-PaYV5VddXFzZm/view?usp=sharing) | [Corley et al., 2015](https://doi.org/10.1093/toxsci/kfv071) | ![rat01.2015](README/rat01_2015.png)                         |
| [rat02](rat02/)                                              | male, 9-10 weeks, 300  g                    | Rat     | [Yes](https://drive.google.com/file/d/1izSij8qFnJywqlsnLn3bYRGOmT75oYWm/view?usp=sharing) | [Corley et al., 2021](https://doi.org/10.1093/toxsci/kfab062) | ![rat02](README/rat02.png)                                   |
| [rabbit01](rabbit01/)                                        | male, 3-3.7 kg,                             | Rabbit  |                                                              | [Corley et al., 2009](https://doi.org/10.1080/08958370802598005) | ![rabbit01](README/rabbit01.png)                             |
| [rabbit02](rabbit02)                                         | female,  5-6 months, 4-5 kg                 | Rabbit  | [Yes](https://drive.google.com/file/d/1_38F5TTeXc1NF-xB0qKUnCKb7ghn0fC7/view?usp=share_link) | [Kabilan et al., 2016 ](http://dx.doi.org/10.1016/j.jaerosci.2016.01.011) | ![rabbit02](README/rabbit02.png)                             |



### Meta Data



| Sample ID    | Additional Info                                              |
| ------------ | ------------------------------------------------------------ |
| human01      | **<u>Human</u>** (female, 84 Yr-old) <br/>**<u>Imaging</u>**: multi-slice CT imaging of the head and torso (623-μm isotropic resolution, FOV 31.9 × 31.9 × 46.1 cm, i.e., image volume size of 512 × 512 × 739).  <br/>**<u>Segmentation</u>**: based on intensity thresholding followed by visual validation and repair. <br/>**<u>Model</u>**: upper airways (nasal passages or oral cavity, both available) down to several generations of conducting airways (135 outlets). A cylinder capturing the contours of the face and extending several centimeters away from the face is included with the distal end of the cylinder used to initiate airflows and chemical exposures.  <br/>**<u>Mesh</u>**: polyhedral mesh created in OpenFOAM<br/>**<u>Simulation types</u>**: airflow, vapor exposure<br/>**<u>Funding source</u>:** NHLBI R01 HL073598 and NIEHS P01 ES011617<br/>**<u>Related Publications</u>:** [Corley et al., 2012](https://doi.org/10.1093/toxsci/kfs168); [Corley et al., 2015](https://doi.org/10.1093/toxsci/kfv071) |
| human02.2016 | **<u>Human</u>** (male, 35 Yr-old, 68 kg, 1.70 m tall)<br>**<u>Imaging</u>**: multi-slice CT imaging of the head and torso (0.5 x 0.7 x 0.7 mm resolution, FOV 36 × 36 × 48 cm, i.e., image volume size of 512 × 512 × 960). <br/>**<u>Segmentation</u>**: based on intensity thresholding followed by visual validation and repair. Larynx was widened from the as-imaged supine breath-hold position to a fully open geometry to mimic inhalation in an upright posture. <br/>**<u>Model</u>**: Nose down to several generations of conducting airways (272 outlets). Model is provided in 5 stl files as listed in the figure.<br>**<u>Mesh</u>**: Hybrid prism/polyhedral volume meshes generated in STAR-CCM+ (Version 8.02, 5,751,626 nodes and 2,550,285 polyhedral elements)<br/>**<u>Simulation types</u>**: airflow and aerosol transportFunding: NHLBI R01HL073598<br/>**<u>Related publications</u>**: [Kabilan et al., 2016](https://doi.org/10.1016/j.jaerosci.2016.01.011) |
| human02.2021 | **<u>Human</u>** (male, 35 Yr-old, 68 kg, 1.70 m tall)<br>**<u>Imaging</u>**: multi-slice CT imaging of the head and torso (0.5 x 0.7 x 0.7 mm resolution, FOV 36 × 36 × 48 cm, i.e., image volume size of 512 × 512 × 960). <br/>**<u>Segmentation</u>**: based on intensity thresholding followed by visual validation and repair. In Kabilan et al’s study (2016), the larynx was widened from the as-imaged supine breath-hold position to a fully open geometry to mimic inhalation in an upright posture. Additional modifications of the oral cavity, i.e., repositioning surface of the tongue for upright oral breathing and closing off the connection to the esophagus, were made in the model used in Corley et al.’s study (2021). <br/>**<u>Models</u>**: 1) Oral cavity down to several generations of conducting airways (272 outlets). STL available soon. 2) Nose down to trachea.<br>**Mesh**: Hybrid prism/polyhedral volume meshes generated in STAR-CCM+ (Version 8.02 for the nasal breathing model (2.85 million elements) and version 14.04.011 for the oral breathing model (4.88 million elements)). Detailed computational mesh characteristics can be found in Table 1 of Corley et al (2021)<br/>**<u>Simulation types</u>**: airflow and aerosol transport<br/>Funding: NHLBI R01HL073598 and NIEHS U01 ES028669<br/>**<u>Related publications</u>**: [Corley et al., 2021](https://doi.org/10.1093/toxsci/kfab062) |
| human03      | **<u>Human</u>** (male, 18 Yr-old, 72 kg)<br>**<u>Imaging</u>**: multi-slice CT imaging of the head and torso.<br/>**<u>Segmentation</u>**: based on intensity thresholding followed by visual validation and repair.<br/>**<u>Model</u>**: Oral cavity down to several generations of conducting airways (8 ± 4 airway generations, 117 outlets). A cylinder capturing the contours of the face and extending several centimeters away from the face is included with the distal end of the cylinder used to initiate airflows and chemical exposures. <br/>**<u>Mesh</u>**: polyhedral mesh created in OpenFOAM (782,000 elements, 442,000 nodes, and 181,000 surface facets, each with their anatomically defined PBPK model boundary condition)<br/>**<u>Simulation types</u>**: airflow, vapor exposure<br/>**<u>Funding</u>**: NHLBI R01 HL073598<br/>**<u>Related publications</u>**: [Corley et al., 2015](https://doi.org/10.1093/toxsci/kfv071) |
| monkey01     | **<u>Species</u>**: Monkey (Rhesus, male, 6-month-old, 1.3 kg)<br>**<u>Imaging</u>**: postmortem CT imaging (GE HighSpeed FX/i system) of the upper airways (nose trough larynx, 1 mm-thick continuous slices) and MR imaging (2T Varian Unity Plus MRI spectrometer) of silicone cast of the trachea and lung obtained at a lung pressure 30 cm H2O from same animal and submersed in 0.25% agar containing the contrast agent Magnevist (1:500 v/v; 391-μm isotropic resolution, FOV 10.1 cm x 10.1 cm x 10.1 cm). <br>**<u>Segmentation</u>**: upper airways segmentation based on intensity thresholding followed by visual validation and repair. Prefiltering of airway cast images using background normalization and edge-preserving hybrid median filters to remove both low- and high-frequency noise, respectively, followed by semiautomatic segmentation, and manual evaluation and repair when necessary.<br>**<u>Model</u>**: upper airways (nasal passages) down to several generations of conducting airways (airway diameter cut-off of 650 µm resulting in 2172 outlets). A cylinder capturing the contours of the face and extending several centimeters away from the face is included with the distal end of the cylinder used to initiate airflows and chemical exposures. <br>**<u>Mesh</u>**: polyhedral mesh created in OpenFOAM, with each boundary facet assigned to a non-overlapping region for CFD/PBPK simulations.<br>**<u>Simulation types</u>**: airflow, vapor exposure<br>**<u>Funding</u>**: NHLBI R01 HL073598 and NIEHS P01 ES011617<br>**<u>Related publications</u>**: [Corley et al., 2012](https://doi.org/10.1093/toxsci/kfs168) |
| rat01.2012   | **<u>Species:</u>** Rat (Sprague Dawley, male, 9-10-week-old, ~300 g)<br>**<u>Imaging:</u>** postmortem MR imaging (Unity Plus spectrometer (Varian, Palo Alto, CA) and a commercial imaging probe (Doty Scientific, Columbia, SC) mounted inside a 7-T, 89-mm diameter, vertical-bore magnet (Oxford Instruments, Oxford, UK)) of the upper airways (nose trough larynx, 125 µm resolution) and µCT imaging (Skyscan 1176 μCT, Microphotonics, Inc., Allentown, PA) of silicone cast of the trachea down to bronchiolar airways at 18-μm isotropic resolution. <br/>**<u>Segmentation:</u>** upper airways segmentation based on intensity thresholding followed by visual validation and repair. Prefiltering of airway cast images using background normalization and edge-preserving hybrid median filters to remove both low- and high-frequency noise, respectively, followed by semiautomatic segmentation, and manual evaluation and repair when necessary.<br/>**<u>Model:</u>** upper airways (nasal passages) down to several generations of conducting airways (airway diameter cut-off of 180 µm resulting in 1272 outlets). A cylinder capturing the contours of the face and extending several centimeters away from the face is included with the distal end of the cylinder used to initiate airflows and chemical exposures.<br/>**<u>Mesh:</u>** polyhedral mesh created in OpenFOAM, with each boundary facet assigned to a non-overlapping region for CFD/PBPK simulations (1.86 million elements with 10.5 million nodes and 0.63 million surface facets).<br/>**<u>Simulation types:</u>** airflow, vapor exposure<br/>**<u>Funding</u>**: NHLBI R01 HL073598 and NIEHS P01 ES011617<br/>**<u>Related publications</u>**: Corley et al., 2012 (https://doi.org/10.1093/toxsci/kfs168) |
| rat01.2015   | **<u>Species</u>**: Rat (Sprague Dawley, male, 9-10-week-old, ~300 g)<br/>Imaging: postmortem MR imaging (Unity Plus spectrometer (Varian, Palo Alto, CA) and a commercial imaging probe (Doty Scientific, Columbia, SC) mounted inside a 7-T, 89-mm diameter, vertical-bore magnet (Oxford Instruments, Oxford, UK)) of the upper airways (nose trough larynx, 125 µm resolution) and µCT imaging (Skyscan 1176 μCT, Microphotonics, Inc., Allentown, PA) of silicone cast of the trachea down to bronchiolar airways at 18-μm isotropic resolution. <br/>**<u>Segmentation</u>**: upper airways segmentation based on intensity thresholding followed by visual validation and repair. Prefiltering of airway cast images using background normalization and edge-preserving hybrid median filters to remove both low- and high-frequency noise, respectively, followed by semiautomatic segmentation, and manual evaluation and repair when necessary. <br/>**<u>Model</u>**: upper airways (nasal passages) down to several generations of conducting airways (17 ± 7 generations) resulting in 1277 outlets. <br/>**<u>Mesh</u>**: polyhedral mesh created in OpenFOAM, with each boundary facet assigned to a non-overlapping region for CFD/PBPK simulations. (1.80 million elements with 10.4 million nodes and 0.86 million surface facets). <br/>**<u>Simulation types</u>**: airflow, vapor exposure<br/>**<u>Funding</u>**: NHLBI R01 HL073598 and NIEHS P01 ES011617<br/>**<u>Related publications:</u>** Corley et al., 2015 (https://doi.org/10.1093/toxsci/kfv071)https://doi.org/10.1093/toxsci/kfab062) |
| rat02.2015   | **<u>Species</u>**: Rat (Sprague Dawley, male, 9-10-week-old, 309 g)<br/>**<u>Imaging</u>**: µCT imaging (GE eXplore CT120 scanner) of the upper airways at 50-μm isotropic resolution. <br/>**<u>Segmentation</u>**: upper airways segmentation based on intensity thresholding followed by visual validation and repair. <br/>**<u>Model</u>**: upper airways (nasal passages) down to upper trachea. <br/>**<u>Mesh</u>**: Hybrid prism/polyhedral volume mesh was generated in STARCCM+. The boundary layer was kept constant at 80 µm and consisted of prismatic elements. Polyhedral mesh elements constituted the core of the volume mesh. (18.7 million elements with 45.1 million nodes and 0.86 million surface facets). <br/>**<u>Simulation types</u>**: airflow, aerosol transport<br/>**<u>Funding</u>**: NHLBI R01 HL073598 and NIEHS U01 ES028669<br/>**<u>Related publications</u>**: Corley et al., 2021 (https://doi.org/10.1093/toxsci/kfab062) |
| rabbit01     | **<u>Species:</u>** Rabbit (New Zealand White, female, 4.335kg)<br>**<u>Imaging:</u>** postmortem MR imaging (using Magnevist contrast agent, 2T horizontal-bore magnet, Varian, Palo Alto, CA) of the upper airways (nose trough larynx, 512 x 512 x 256 matrix, FOV 8 x 8 x 16 cm). <br/>**<u>Segmentation:</u>** upper airways segmentation using Digital Data Viewer (DDV, http://www.cgccode.org) after correcting for poorly resolved data using the pixel editing tool in DDV. An isosurface for the entire volume was generated and saved in the AVS UCD format (http://www.avs.com), then smoothed using volume-conserving smoothing.<br>**<u>Model:</u>** upper airways from the nostrils to the nasopharynx (referred to as Rabbit 1 in Corley et al., 2009).<br/>**<u>Simulation types:</u>** airflow <br/>**<u>Funding:</u>** NHLBI R01 HL073598 and NIEHS P01 ES011617<br/>**<u>Related publications:</u>** Corley et al., 2009 (https://doi.org/10.1080/08958370802598005)</u> |
| rabbit02     | **<u>Species</u>**: Rabbit (New Zealand White, male, 3.5-3.8 kg)<br/>**<u>Imaging</u>**: µCT imaging (GE eXplorer CT-120) at 50 µm resolution: postmortem in-situ imaging of the upper airways (nose trough larynx) followed by imaging of silicone cast of the trachea down to bronchiolar airways. <br/>**<u>Segmentation</u>**: upper airways segmentation based on intensity thresholding followed by visual validation and repair. Prefiltering of airway cast images using background normalization and edge-preserving hybrid median filters to remove both low- and high-frequency noise, respectively, followed by semiautomatic segmentation, and manual evaluation and repair when necessary.<br/>**<u>Model</u>**: upper airways (nasal passages) down to several generations of conducting airways (airway diameter cut-off of 500 µm resulting in 3857 airways with 2878 terminal outlets). <br/>**<u>Mesh</u>**: Hybrid prism/polyhedral volume meshes generated in STAR-CCM+ (Version 8.02, 36,232,173 nodes and 16,060,891 polyhedral elements).<br/>**<u>Simulation types</u>**: airflow and aerosol transport<br/>**<u>Funding</u>**: NHLBI R01 HL073598<br/>**<u>Related publications</u>**: Kabilan et al., 2016 (http://dx.doi.org/10.1016/j.jaerosci.2016.01.011) |





### References

Corley, R. A., Kabilan, S., Kuprat, A. P., Carson, J. P., Jacob, R. E., Minard, K. R., Teeguarden, J. G., Timchalk, C., Pipavath, S., Glenny, R., & Einstein, D. R. (2015). Comparative Risks of Aldehyde Constituents in Cigarette Smoke Using Transient Computational Fluid Dynamics/Physiologically Based Pharmacokinetic Models of the Rat and Human Respiratory Tracts. *Toxicological Sciences: An Official Journal of the Society of Toxicology*, *146*(1), 65–88.

Corley, R. A., Kabilan, S., Kuprat, A. P., Carson, J. P., Minard, K. R., Jacob, R. E., Timchalk, C., Glenny, R., Pipavath, S., Cox, T., Wallis, C. D., Larson, R. F., Fanucchi, M. V., Postlethwait, E. M., & Einstein, D. R. (2012). Comparative computational modeling of airflows and vapor dosimetry in the respiratory tracts of rat, monkey, and human. *Toxicological Sciences: An Official Journal of the Society of Toxicology*, *128*(2), 500–516.

Corley, R. A., Kuprat, A. P., Suffield, S. R., Kabilan, S., Hinderliter, P. M., Yugulis, K., & Ramanarayanan, T. S. (2021). New Approach Methodology for Assessing Inhalation Risks of a Contact Respiratory Cytotoxicant: Computational Fluid Dynamics-Based Aerosol Dosimetry Modeling for Cross-Species and In Vitro Comparisons. *Toxicological Sciences: An Official Journal of the Society of Toxicology*, *182*(2), 243–259.

Kabilan, S., Suffield, S. R., Recknagle, K. P., Jacob, R. E., Einstein, D. R., Kuprat, A. P., Carson, J. P., Colby, S. M., Saunders, J. H., Hines, S. A., Teeguarden, J. G., Straub, T. M., Moe, M., Taft, S. C., & Corley, R. A. (2016). Computational fluid dynamics modeling of Bacillus anthracis spore deposition in rabbit and human respiratory airways. *Journal of Aerosol Science*, *99*, 64–77.
