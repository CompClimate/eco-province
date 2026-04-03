# ec-province
Code and relevant data for McDevitt, Sonnewald and Dutkiewicz, in review, Communications Earth and Environment

All data can be found here: https://simonscmap.com/catalog/datasets/Darwin_Phytoplankton

The code files are in the following order: 

1) summer_and_winter_nemi_clustering.ipynb for the clustering workflow for identifying eco-provinces based on phytoplankton functional type data using NEMI.
2) Plotting_EPs_and_Entropy.ipynb is for plotting the eco-provinces produced by NEMI.
3) network_training.ipynb is for training the dense network ensemble based on remotely observable data found here: https://simonscmap.com/catalog/datasets/Darwin_Ocean_Color. Training and total datasets are included here as .npy files, and test and validation sets are created in the included code. 
4) run_shap.py is for running the SHAP explainability.
5) shap_plots.ipynb.zip is for plotting the SHAP values spatially. 
