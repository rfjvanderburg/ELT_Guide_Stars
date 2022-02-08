# ELT Guide Star Catalogues

This is the repository of work done in preparation of Guide Star
catalogues that will be used by the future ELT during operations.

<<<<<<< HEAD
[Workbook 1](https://github.com/rfjvanderburg/ELT_Guide_Stars/blob/master/Guide_stars_1.ipynb) explores options to estimate H-band magnitudes for stars 
=======
[Workbook 1](https://github.com/rfjvanderburg/ELT_Guide_Stars/Guide_stars_1.ipynb) explores options to estimate H-band magnitudes for stars 
>>>>>>> b39134f680a13bdc8e367d34ac5e492b83017de0
based on their optical colours and Gaia G-band magnitude. It is making use of the Pan-STARRS1 survey, 
which has filter bands similar to those LSST/Vera Rubin will have. The model is trained on stars that have a range of
different Galactic dust extinction. The final product/model performs well for different stellar types, as well as
different levels of Galactic extinction.

<<<<<<< HEAD
[Workbook 2](https://github.com/rfjvanderburg/ELT_Guide_Stars/blob/master/Guide_stars_2.ipynb) uses the Gaia simulated Universe to explore the fraction
=======
[Workbook 2](https://github.com/rfjvanderburg/ELT_Guide_Stars/Guide_stars_2.ipynb) uses the Gaia simulated Universe to explore the fraction
>>>>>>> b39134f680a13bdc8e367d34ac5e492b83017de0
of problematic binary stars for ELT operations (as defined by their
angular separation and flux ratio). We find that ~20% of stars that could be selected
for wavefront sensing are expected to have a companion that could potentially hamper ELT
operations. This is a strong case for the remaining work; namely to clean up this catalogue of contaminants.

<<<<<<< HEAD
[Workbook 3](https://github.com/rfjvanderburg/ELT_Guide_Stars/blob/master/CNN_binary_classification.ipynb) trains a CNN model to classify sources into single
=======
[Workbook 3](https://github.com/rfjvanderburg/ELT_Guide_Stars/CNN_binary_classification.ipynb) trains a CNN model to classify sources into single
>>>>>>> b39134f680a13bdc8e367d34ac5e492b83017de0
stars and binary stars based on HST imaging data. It is trained on a large number of 
binary stars that are constructed using real HST data. This trained
model will be central to the next stage, where we aim to obtain a
similar classification based on entirely different data (Gaia only). 

<<<<<<< HEAD
[Workbook 4](https://github.com/rfjvanderburg/ELT_Guide_Stars/blob/master/Gaia_classification.ipynb) combines the trained CNN model (from Workbook 3) with a curve-of-growth classifier that will be more sensitive to extended object such as Galaxies.
=======
[Workbook 4](https://github.com/rfjvanderburg/ELT_Guide_Stars/Gaia_classification.ipynb) combines the trained CNN model (from Workbook 3) with a curve-of-growth classifier that will be more sensitive to extended object such as Galaxies.
>>>>>>> b39134f680a13bdc8e367d34ac5e492b83017de0
The result is a set of HST-observed stars that would likely be problematic for ELT operations.
Then different Gaia parameters are explored to investigate how these stars can be flagged
without the need of HST imaging.

[Workbook 5](https://github.com/rfjvanderburg/ELT_Guide_Stars/blob/master/make_catalogue.ipynb) creates a guide-star catalogue around a user-specified ICRS coordinate. The catalogue is based on Gaia EDR3 and contains NIR fluxes based on different VISTA and UKIRT surveys, and on J- and H-band predictions based on optical data.


