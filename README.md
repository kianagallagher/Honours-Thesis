# Honours-Thesis
This repository contains the code that was used in the completion of Kiana Gallagher's Honours Thesis

## Get_Counts.ipynb
Gets the counts from the files output by the detector during image acquisition.

## Mask_Sinogram.ipynb
Gets the sinograms and corrects for dead or unstable detector pixels using the counts produced by Get_Counts.ipynb.

## Image_Reconstruction.ipynb
Reconstructs the images using the sinograms produced by Mask_Sinogram.ipynb.

## Make_Datasets.pynb
Creates the train, validation, and test datasets used for model training and evaluation.

## PCCT_U-Net_Training.ipynb
Trains the U-Net model on individual PCCT images.

## Conventional_CT_U-Net_Training.ipynb
Trains the U-Net model on conventional CT images.

## Model_Output.ipynb
Calculates the image metrics for models trained on PCCT and Conventional CT data

## Average_Calculations.ipynb
Calculates the average image metrics for models trained on PCCT and Conventional CT data