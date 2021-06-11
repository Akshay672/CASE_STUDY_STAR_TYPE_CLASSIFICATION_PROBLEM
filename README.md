# CASE_STUDY_STAR_TYPE_CLASSIFICATION_PROBlEM

# Problem Statement

The aim of our model is to classify observations of space objects into a star, a galaxy or a quasar.

# Dataset Information
The Sloan Digital Sky Survey offers public data of space observations. Observations have been made since 1998 and have been made accessible to everyone.

For this purpose a special 2.5 m diameter telescope was built at the Apache Point Observatory in New Mexico, USA. The telescope uses a camera of 30 CCD-Chips with 2048 x 2048 image points each. The chips are ordered in 5 rows with 6 chips in each row. Each row observes the space through different optical filters (u, g, r, i, z) at wavelengths of approximately 354, 476, 628, 769, 925 nm.

![CCDs_filters1](https://user-images.githubusercontent.com/85668824/121673639-ba251c00-cace-11eb-9604-bd6a3b50e7b1.gif)

# Attribute Information

**objid** : Object Identifier

**right_asc** : Right Ascension. It is the angular distance of a particular point measure from East to west. It is analogous to longitude on Earth.

**declination** : Declination. It is the angular distance of a point north or south of the celestial equator. It is measured in degrees. Analogous to latitude on Earth.

**u_band, g_band, r_band, i_band, z_band **: represents the different wavelengths used to capture the observations. The bands are Ultraviolet, Green, Red, Near-infrared and Infrared respectively. The SDSS imaging camera takes images in five filters: u,g,r,i,z. Each letter designates a section of light of the electromagnetic spectrum.

**run** : Run Number, which indentifies the specific scan

**rerun** : Rerun Number, tells us how the image has been processed

**camcol** : Camera column. The SDSS camera had six parallel camera columns, meaning that each run is divided into six parallel scanlines, one for each camera column. These images are known as camcols, and are numbered 1 through 6.

**field** : Field number. A field is a part of a camcol that is processed by the Photo pipeline at one time. Fields are 2048x1489 pixels. A field consists of the frames in the 5 filters for the same part of the sky.

Run, rerun, camcol and field are features which describe a field within an image taken by the SDSS. A field is basically a part of the entire image corresponding to 2048 by 1489 pixels.

**specobjid** : Object Identifier

**redshift** : It is a ratio of the obseved wavelength and a reference wavelength. The wavelength at which the radiation is originally emitted from the space object is lengthened as it travels through space. Using this one can understand how far the space objects are.

**mod_julian_date** : Modified Julian Date is the number of days passed since November 17th 1858. This date tells us when the record was taken.

**fiberid** : fiber ID. It gives the specific optical fiber chosen to record the observation.

**plate** : plate number. It gives the specfic plate number of the SDSS camera used to record observations.

# Target Variable
The target variable is '**class**' which has 3 categories:

**Star**: It is a type of astronomical object consisting of a luminous spheroid of plasma held together by its own gravity. The nearest star to Earth is the Sun.

**Galaxy**: It is a huge collection of gas, dust, and billions of stars and their solar systems, all held together by gravity. We are a part of the milky way galaxy.

**QS0(Quasar)**: It is an astronomical object of very high luminosity found in the centres of some galaxies and it is powered by gas spiraling at high velocity into an extremely large black hole.

# Task Completed:
Import Libraries

1.Data Preprocessing

2.Data Visualization

3.Data Encoding

4.Data Cleaning

5.Feature Scaling

6.Model Building

6.1 - K Nearest Neighbour Classifier

6.2 - Random Forest Classifier

6.3 - AdaBoost classifier

6.4 - XGBoost Classifier

6.5 - Final Result



# Conclusion :

Through this notebook, we have analyzed the SDSS data (we learned some very interesting facts about our space along the way), how to build a machine learning model to predict for unseen data from this data set and how to improve its performance (even though there was only a slight improvent). We used XGBoost for predicting and evaluated its result.


<h4>DATASET FILE LINK : <a href='https://github.com/Akshay672/CASE_STUDY_STAR_TYPE_CLASSIFIACTION_PROBlEM/blob/main/sky_survey_project_final_datasetnew.csv'>sky_survey_project_final_datasetnew.csv</a></h4>


<h4>CASE STUDY FILE LINK : <a href='https://github.com/Akshay672/CASE_STUDY_STAR_TYPE_CLASSIFIACTION_PROBlEM/blob/main/CASE_STUDY_STAR_TYPE_CLASSIFICATION_PROBlEM.ipynb'>CASE_STUDY_STAR_TYPE_CLASSIFICATION_PROBlEM</a></h4>
