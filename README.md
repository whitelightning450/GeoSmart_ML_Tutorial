![mountain](https://user-images.githubusercontent.com/33735397/155626251-72859ce7-e05a-4282-89be-6871b19ab234.PNG)

# Geosmart Use Case Jupyter Book

[![Deploy](https://github.com/geo-smart/use_case_template/actions/workflows/deploy.yaml/badge.svg)](https://github.com/geo-smart/use_case_template/actions/workflows/deploy.yaml)
[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://geo-smart.github.io/use_case_template)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/geo-smart/use_case_template/HEAD?urlpath=lab)
[![GeoSMART Use Case](./book/img/use_case_badge.svg)](https://geo-smart.github.io/usecases)
![GitHub](https://img.shields.io/github/license/whitelightning450/National-ML-Snow-Prediction-Mod?logo=GitHub&style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/whitelightning450/National-ML-Snow-Prediction-Mod?logo=Jupyter&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/whitelightning450/National-ML-Snow-Prediction-Mod?logo=Github&style=flat-square)

### Deep Learning national scale 1 km resolution SWE prediction model
Snow-derived water is a critical hydrological component for characterizing the quantity of water available for domestic, recreation, agriculture, and power generation in the western United States.
Advancing the efficiency and optimization of these aspects of water resources management requires an enhanced characterization of the snow state variable, particularly the essential global inputs of snow-water-equivalent (SWE), peak SWE, and snowmelt onset for hydrological models.
While physically-based models that characterize the feedbacks and interactions between influencing factors predict SWE values well in homogeneous settings, these models exhibit limitations for CONUS-scale deployment due to challenges attributed to spatial resolution, landscape heterogeneity, and computational intensity. 
Leveraging a collaborative partnership between the Alabama Water Institute (AWI) at the University of Alabama (UA) and the University of Utah (UU), we address these limitations through the National Snow Model (NSM) as a full stack data-driven machine learning (ML) platform with a modular structure to account for the heterogeneity of climate and topographical influences on SWE across the western United States.
This model consists of twenty-three regionally specific sub-models tailored to the unique topography and hydroclimate phenomena in the Western U.S., exhibiting an RMSE less than 8 cm and a coefficient of determination approaching 0.99 on predictions spanning the 2013-2017 training period.
The NSM pipeline assimilates nearly 700 snow telemetry (SNOTEL) and California Data Exchange Center (CDEC) sites and combines with processed lidar-derived terrain features for the prediction of a 1 km x 1 km SWE inference in critical snowsheds under 20 minutes on personal computer.
We complete the full stack product by leveraging the Tethys interface (TBA), supporting the interactive use of the results (i.e., individual to HUC-scale SWE estimates).
With preliminary regional testing performance ranging between 2.5 cm to 8 cm (i.e., RMSE), this model has the potential to advance the snow state variable in hydrological models such as the National Water Model to improve the estimates of peak flow for flood management and low-flows for supply operations. 
 This readme describes the necessary Python dependencies, training sources, and instructions to get the ML model running for near-real-time SWE inference.


![ML_SWE-2.jpg](./book/chapters/Images/ML_SWE.jpg)
# About the GeoSMART Snow ML Use Case Library
[![GeoSMART Use Case](./book/img/use_case_badge.svg)](https://geo-smart.github.io/usecases)

### General Overview


This use case library contains a summary of the motivation behind the project, applicable ML methods and tools, the methods for data preparation, model development including the model training framework and evaluation, workflow management demonstrated using GeoWeaver, links to the complete model on GitHub as the model is data-intensive the tutorial is for a subset of the entire model, a discussion/conclusion, and a solitication to qestions.
Below are the respective chapters addressing these items:



Explain this family of books, link to others, explain how to contribute and purpose. Books in the library can be identified by the badge:

1. [Motivation](./book/chapters/motivation.ipynb)
2. [Machine Learning Methods and tools](./book/chapters/methods.ipynb)
3. [Data Preparation](./book/chapters/data.ipynb)
4. [Model Development and Parameter Tuning](./book/chapters/development.ipynb)
5. [Model Training](./book/chapters/training.ipynb)
6. [Evaluation of Model Performance](./book/chapters/evaluation.ipynb)
7. [Workflow Management and Cloud Computing](./book/chapters/workflow.ipynb)
8. [Reproducibility](./book/chapters/reproducibility.ipynb)
9. [Discussion/Conclusion](./book/chapters/conclusion.ipynb)
10. [Solicitation to Questions](./book/chapters/questions.ipynb)


### Contributing Content

Tutorial content supports the data processing, model training, and evaluation of the National Snow model for a subregion of Colorado.
The goal is to provide get new users running executable code on our AWS platform.

## Project support through the University of Alabama and the University of Utah
![UU](https://user-images.githubusercontent.com/33735397/155627859-a34f7856-22a5-4376-89ca-a59b70f3692e.PNG)
![UA](https://user-images.githubusercontent.com/33735397/155628209-c4742053-eb29-4d1e-b8e2-c4e354188ca9.PNG)
