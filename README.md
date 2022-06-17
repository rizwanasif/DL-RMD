# DL-RMD: A geophysically constrained electromagnetic resistivity model database for deep learning applications (code demo)

This repository provides the trained network weights for the forward modelling of tTEM data and make a network forward pass to obtain the tTEM forward response from the network.

## Demo Code:

Use DL_RMD_demo.ipynb and run in Colab for demo.

## Download the dataset:

The original files of the dataset can be downloaded from here as an archive file. The metadata is provided in the archive file.

## Parameter description:

Layer 1 weights: L1_W.txt

Layer 1 bias:    L1_B.txt 

Layer 2 weights: L2_W.txt

Layer 2 bias:    L2_B.txt

Layer 3 weights: L3_W.txt

Layer 3 bias:    L3_B.txt


dBdt normalization mean values: mu.txt

dBdt normalization std values:  std.txt

dBdt time instants:             t.txt


Test set (Input) having 697 samples : resistivity_Soften.txt

Test set (Target output ) :           resistivity_Soften.txtforwards_Soften.txt
