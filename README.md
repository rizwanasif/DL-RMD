# DL-RMD: A geophysically constrained electromagnetic resistivity model database for deep learning applications

This repository provides the trained network weights for the forward modelling of tTEM data and make a network forward pass to obtain the tTEM forward response from the network.

## Demo Code:

[DL_RMD_demo.ipynb](https://colab.research.google.com/github/rizwanasif/DL-RMD/blob/main/DL_RMD_demo.ipynb)


## Download the dataset:

The original files of the dataset can be [downloaded from here](https://doi.org/10.5281/zenodo.6695868) (comma separated delimiters and each row is one entry). The metadata is as below:


### S-RMD:



**_S_RMD_rho.txt_** contains the resistivity values for the shallow TEM systems.

**_S_RMD_thk.txt_** contains the thickness of each resistivity layer for the shallow TEM systems.

**_S_RMD_EMresponse.txt_** contains the forward responses for the corresponding resistiity models in **_S_RMD_rho.txt_**.

**_S_VK_rho.txt_** contains the resistivity values von Kármán models (90 layers) used for the shallow TEM systems.

**_S_VK_thk.txt_** contains the thickness of each resistivity layer of von Kármán models (90 layers) used for the shallow TEM systems.

 

### I-RMD:



**_I_RMD_rho.txt_** contains the resistivity values for the intermediate depth TEM systems.

**_I_RMD_thk.txt_** contains the thickness of each resistivity layer for the intermediate depth TEM systems.

**_I_VK_rho.txt_** contains the resistivity values von Kármán models (90 layers) used for the intermediate depth TEM systems.

**_I_VK_thk.txt_** contains the thickness of each resistivity layer of von Kármán models (90 layers) used for the intermediate depth TEM systems.

 

### D-RMD:



**_D_RMD_rho.txt_** contains the resistivity values for the deep TEM systems.

**_D_RMD_thk.txt_** contains the thickness of each resistivity layer for the deep TEM systems.

**_D_VK_rho.txt_** contains the resistivity values von Kármán models (90 layers) used for the deep TEM systems.

**_D_VK_thk.txt_** contains the thickness of each resistivity layer of von Kármán models (90 layers) used for the deep TEM systems.



## Citation:

Asif, M. R., Foged, N., Bording, T., Larsen, J. J., and Christiansen, A. V. (2022). DL-RMD: A geophysically constrained electromagnetic resistivity model database for deep learning applications (Dataset) (Version v1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6695868


