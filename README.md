# V-Screening-OPV
#### Machine learning codes for virtual screening of conjugated polymers for organic photovoltaic devices (solar cells)

In this repository, we create models for virtual screening of conjugated polymers for organic photovoltaic devices using
various machine learning algorithms. We particular focus on support vector machine (SVM) and ensemble learning approaches.
We found the power conversion efficiencies (PCEs) of the devices prepared with the polymer candidates can be predicted with
their structure fingerprints as the only inputs. In other words, no preliminary knowledge about material properties are 
required. Additionally, the predictive performance could be further improved by “blending” the results of the SVM and 
random forest (RF) models. The resulting ensemble learning algorithm might open up a new opportunity for more precise, 
high-throughput virtual screening of conjugated polymers for OPV devices.

You will find two jupyter notebook files in this repository. The modelling details can be found in the first file, 
"Model.ipynb". Note the raw data used in the models was published by a paper, entitled "Computer-Aided Screening of 
Conjugated Polymers for Organic Solar Cell: Classification by Random Forest", by Nagasawa et al. [J. Phys. Chem. Lett.
vol. 9, pp. 2639-2646, 2018].

After the model was ready. We test it by using the other dataset obtained from the paper, “The Harvard organic 
photovoltaic dataset”, by Lopez et al. [Sci. Data vol. 3, Art. no. 160086, 2016]. The code is in the second file,
"Prediction.ipynb". Note that all the data (not split data) is used for building the model for prediction.

#### The research article about the models has been published here: Fang-Chung Chen*, “Virtual Screening of Conjugated Polymers for Organic Photovoltaic Devices Using Support Vector Machines and Ensemble Learning” Int. J. Polym. Sci., 2019, 4538514 (2019). (https://onlinelibrary.wiley.com/doi/10.1155/2019/4538514)
