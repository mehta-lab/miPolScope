# miPolScope
This repository provides Jupyter notebooks showing steps in the reconstruction of data presented in Fig. 1 and Fig. 3 of the manuscript

`Ivan E. Ivanov, Li-Hao Yeh, Juan A. Perez-Bermejo, Janie R. Byrum, James Y.S. Kim, Manuel D. Leonetti, and Shalin B. Mehta, "Correlative imaging of spatio-angular architecture of live cells and molecular assemblies with multimodal instant polarization microscope" (2022).`

# Requirements
The notebooks use the [waveorder](https://github.com/mehta-lab/waveorder) package for data reconstruction and [napari](https://napari.org/) for data visualization.

To execute the notebooks create a new conda environment

```
conda create -n <environment-name> python
conda activate <environment-name>
```

and install the following packages:

```
conda install jupyter scikit-image
pip install git://github.com/mehta-lab/waveOrder.git#egg=waveorder  
pip install napari napari-ome-zarr
```

# Data
Raw images and microscope calibration metadata are distributed via [Zenodo](https://zenodo.org/): [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5952953.svg)](https://doi.org/10.5281/zenodo.5952953)

# License
Chan Zuckerberg Biohub Software License

This software license is the 2-clause BSD license plus a third clause
that prohibits redistribution and use for commercial purposes without further
permission.

Copyright © 2019. Chan Zuckerberg Biohub.
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1.	Redistributions of source code must retain the above copyright notice,
this list of conditions and the following disclaimer.

2.	Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.

3.	Redistributions and use for commercial purposes are not permitted without
the Chan Zuckerberg Biohub's written permission. For purposes of this license,
commercial purposes are the incorporation of the Chan Zuckerberg Biohub's
software into anything for which you will charge fees or other compensation or
use of the software to perform a commercial service for a third party.
Contact ip@czbiohub.org for commercial licensing opportunities.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
