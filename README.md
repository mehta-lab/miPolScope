# miPolScope
This repository provides Jupyter notebooks showing steps in the reconstruction of data presented in Fig. 1 and Fig. 3 of the manuscript

`Ivan E. Ivanov, Li-Hao Yeh, Juan A. Perez-Bermejo, Janie R. Byrum, James Y.S. Kim, Manuel D. Leonetti, and Shalin B. Mehta, "Correlative imaging of spatio-angular dynamics of biological systems with multimodal instant polarization microscope" (2022).`

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
pip install waveorder  
pip install napari napari-ome-zarr
```

# Data
Raw images and microscope calibration metadata are distributed via [Zenodo](https://zenodo.org/): [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5952953.svg)](https://doi.org/10.5281/zenodo.5952953)
