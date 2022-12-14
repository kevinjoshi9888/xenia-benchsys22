# XENIA_BenchSys22

#### This repository contains code to reproduce the results for the paper 'XENIA: eXplainable ENergy Informatics and Attributes for building energy benchmarking' by Kevin Joshi, Arnab Jana, Pandarasamy Arjunan, and Krithi Ramamritham


![XENIA](/figures/xenia_teaser_2.png)

##### Abstract:
Benchmarking energy usage help identify operational and strategic best practices suitable for an establishment while creating awareness of energy consumption. Therefore in this work, we present XENIA, a data-driven energy benchmarking methodology for buildings in Singapore using a public dataset of building attributes. We develop an ensemble tree model to predict energy consumption using the building attributes as predictors. Symmetric mean absolute percentage error of these models for hotel and retail buildings is 5.15% and 5.02%, respectively. A benchmark grade is then assigned to each building using the actual and predicted energy consumption. To interpret the model, we provide a global explanation using the partial dependence function to show the effect of building attributes on energy consumption. For local explanation, i.e., for a specific building, we use the SHAP value to show the influence of each building attribute in the prediction model. The results for hotels and retail buildings show that change in AC and non-AC floor has the highest positive impact on energy consumption.

A data visualization dashboard is available at: <https://public.tableau.com/app/profile/kevinjoshi9888/viz/XENIA_BenchSys22/XENIA>

##### url: https://doi.org/10.1145/3563357.3566140

##### citation:

##### ACM Format
Kevin Joshi, Arnab Jana, Pandarasamy Arjunan, and Krithi Ramamritham. 2022. XENIA: eXplainable ENergy informatics and attributes for building energy benchmarking. In Proceedings of the 9th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation (BuildSys '22). Association for Computing Machinery, New York, NY, USA, 406–412. https://doi.org/10.1145/3563357.3566140

##### BibTeX
@inproceedings{10.1145/3563357.3566140,
author = {Joshi, Kevin and Jana, Arnab and Arjunan, Pandarasamy and Ramamritham, Krithi},
title = {XENIA: EXplainable ENergy Informatics and Attributes for Building Energy Benchmarking},
year = {2022},
isbn = {9781450398909},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3563357.3566140},
doi = {10.1145/3563357.3566140},
booktitle = {Proceedings of the 9th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation},
pages = {406–412},
numpages = {7},
keywords = {explainable AI, shapley value, ensemble model, partial dependence, energy benchmarking, machine learning},
location = {Boston, Massachusetts},
series = {BuildSys '22}
}
