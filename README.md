# Study of Higgs to Diphoton Signal in the CMS Detector at LHC.
This repository contains Jupyter Notebooks developed during my research internship at the Saha Institute of Nuclear Physics (SINP), Kolkata. The work involved analyzing data from the CMS experiment at CERN, focusing on the Higgs to diphoton signal.

**Repository Structure**

The repository is divided into two main sections:

**1. Initial Analysis:** 

  - Notebooks in this section handle ROOT files from the CMS experiment.
  
  - Use of the tag-and-probe method to calculate the efficiency of selection criteria.
  
  - Conversion of ROOT files into dataframes for further analysis.
  
  - Preparing the data for machine learning model training.
  
**2. Model Training:** 
  
  - Contains notebooks for training a simple neural network.
  
  - The neural network is trained on different background simulations: QCD Background, Gamma-Jets Background, Diphoton Background, and combinations of these with Higgs to Diphoton signals.
  
  - These backgrounds simulate common noise encountered when isolating the Higgs signal from other events.
  
  - After training, the model is used to make predictions on real data from the CMS experiment.
  
  - Signal modeling is performed to visualize the signal within the background noise.
  
**A note regarding the data files:** 

  The dataset used in this project was provided by my supervisor and can only be shared at his discretion.

**Skills and Tools**

Throughout this project, I gained experience with:

  - **CERN ROOT:** Used for data handling and analysis, including modules like RooFit.
  
  - **Awkward Arrays:** Designed specifically for high-energy physics data analysis.
  
  - **Neural Networks:** Applied PyTorch to build and train models for classifying signal vs. background data.

