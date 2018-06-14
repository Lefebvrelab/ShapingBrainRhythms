# ShapingBrainRhythms

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Lefebvrelab/ShapingBrainRhythms/master)


This repository contains code, data, and additional documentation relating to

>Griffiths J D & Lefebvre J (2018). Shaping brain rhythms: Dynamic and control-theoretic perspectives on periodic brain stimulation for treatment of neurological disorders. (Chapter to appear in Vassilis et al. Eds. : ”Handbook of Multi-Scale Models of Brain Disorders: From Microscopic to Macroscopic Assessment of Brain Dynamics. Springer. London.)

Simulation, analysis, and visualization code is located in two jupyter notebooks in the `code` folder. `run_sims.ipynb` runs all the simulations, and saves the results to `.h5` files in the `data` folder. `make_figures.ipynb` loads in the saved outputs and plots them as is done in the figures 2 and 3 of the chapter. You can also skip running the `run_sims.ipynb` notebook and go straight to the second one if you prefer, as the necessary output files are included in the `data` folder of this repo. 






## Run simulations in the cloud


This repository has been configured so that the simulations can be easily run, reproduced, and modified for free in the cloud through just your browser, using the wonderful [Binder](https://github.com/binder-project).

Click on the 'launch binder' button above to launch a new interactive cloud-hosted jupyter notebook server in your browser. When that has fired up, in the jupyter file browser navigate to `code`, and start up and execute the code in `run_sims.ipynb`, and then `make_figures.ipynb`, to reproduce the figures shown in the chapter.   
