COVID-19 Detection and Lung & Infection Mask Segmentation Using UNET


Coronavirus disease 2019 (COVID-19) is a contagious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). 
The first known case was identified in Wuhan, China, in December 2019. The disease has since spread worldwide, leading to an ongoing pandemic


Description

A CNN model was trained to detect COVID-19 in CT scans of lung. UNET models have been developed to detect the infected region in the CT scans and to perform lung segmenation as well.


Dataset

COVID-19 CT scans which consists of 20 CT scans and expert segmentations of patients with COVID-19 which is nifti format has been used for training.
Link to the dataset : https://www.kaggle.com/andrewmvd/covid19-ct-scans


Output and Results

The COVID-19 detection CNN model has achieved an accuracy of 98.26%. A DICE score of 0.9802 has been achieved using the lung segmentation UNET model and a DICE score of 0.8710 has been attained using the infection region segmentation UNET model

