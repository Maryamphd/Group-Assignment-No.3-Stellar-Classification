![stars-1280x720-space-galaxy-4k-17390](https://user-images.githubusercontent.com/68198656/204143917-aec0a790-5c4f-4d10-840f-a494b24545ce.jpg)

# Stellar Classification - Sloan Digital Sky Survey DR17 (SDSS17)
### Our goal to apply Machine Learning algorithm(s) for Stellar Classification either stars, galaxies or quasars.
---
## Dataset
### The data consists of 100,000 observations of space taken by the SDSS (Sloan Digital Sky Survey). Every observation is described by 17 feature columns and 1 class column which identifies it to be either a star, galaxy or quasar.
https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17
### Dictionary
| Column  |   Description  |   
---       | ---       |        
|obj_ID | Object Identifier, the unique value that identifies the object in the image catalog used by the CAS|
|alpha | Right Ascension angle (at J2000 epoch)|
|delta | Declination angle (at J2000 epoch)|
|u | Ultraviolet filter in the photometric system|
|g | Green filter in the photometric system|
|r | Red filter in the photometric system|
|i | Near Infrared filter in the photometric system|
|z | Infrared filter in the photometric system|
|run_ID | Run Number used to identify the specific scan|
|rereun_ID | Rerun Number to specify how the image was processed|
|cam_col | Camera column to identify the scanline within the run|
|field_ID | Field number to identify each field|
|spec_obj_ID| Unique ID used for optical spectroscopic objects (this means that 2 different observations with the same spec_obj_ID must share the output class)|
|class | object class (galaxy, star or quasar object) |
|redshift| redshift value based on the increase in wavelength|
|plate|plate ID, identifies each plate in SDSS|
|MJD|Modified Julian Date, used to indicate when a given piece of SDSS data was taken|
|fiber_ID|fiber ID that identifies the fiber that pointed the light at the focal plane in each observation|
---
## Analysis Content
* EDA
* Univariate Analysis
* Multivariate Analysis
* Declare the feature vector and the target variable
* Feature Engineering
* Split data into training and test set
* Model training
* k-Fold Cross Validation
* Hyperparameter Optimization using GridSearch
* Model Evaluation and Selection
* Results and Conclusion
---
## References
* https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17
* Chawla, Nitesh V, Kevin W Bowyer, Lawrence O Hall, and W Philip Kegelmeyer. 2002. “SMOTE: Synthetic Minority over-Sampling Technique.” Journal of Artificial Intelligence Research 16: 321–57.
* Xiao-Qing, W., &Jin-Meng, Y. (2021). Classification of star/galaxy/QSO and star spectral types from LAMOST data release 5 with machine learning approaches. Chinese Journal of Physics, 69, 303-311. [11]Clarke, A. O., Scaife, A. M. M., Greenhalgh, R., &Griguta, V. (2020). 
* Identifying galaxies, quasars, and stars with machine learning: A new catalogue of classifications for 111 million SDSS sources with-out spectra. Astronomy & Astrophysics, vol.639, p.A84. 
## Acknowledgements
The data released by the SDSS is under public domain. Its taken from the current data release RD17.
More information about the license: http://www.sdss.org/science/image-gallery
