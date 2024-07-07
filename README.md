# Capstone-2024
Sari Sarieddine 





## Predictive Model for Forest Fire Preparedness
=========================

### Executive Summary

... Why this project:
        - Forest fires are becoming more commonplace and dangerous
        - Weather is getting warmer by the year
        
... What is the data science opportunity:
    Anticipating forest fires may help communities be better equipped to handle the risks. 


... Key takeaways: Histogram Gradient Boosting has proved to be the best model in predicting occurance of forest fires. Modelling for climate related events has a risk of model drifting in a shorter span than what may be ideal as we are seeing a rapid change in temperatures and weather events. We will have to contineously monitor, measure, and retrain our models to keep up with those changes. 




### More Information on Methodology


... Data was collected from the government of Canada's open data websites for both the Ministry of Environment and natural resources and Ministry of Forests and Forestry
... Daily weather data was downloaded from 430 stations then aggregated into Monthly data to reduce the number of missing values. 
... The data used was from all across Canada, between 1990 and 2022
... This dataset is heavily relient on the assumption that the user understand Geographic data and Coordinate systems
... Weather data and fire data were then merged based on distance. 
... cKD trees were used to merge the two datasets together by distance. 
... We collected the 5 closest stations to a fire to get a good average of the different temepratures that suround a fire.
... More information can be found in the notebooks!



#### Repository 

* `data` 
    - contains link to copy of the dataset (stored in a public Google Drive)

* `model`
    - Includes all 3 models that were created: Logistic Regression, Decision Tree, and Histogram Gradient Boosting. 

* `notebooks`
    - contains all final notebooks involved in the project

* `docs`
    - contains the presentations invloved with this project


* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `fire_prediction_model.yml`
    - Conda environment for this project

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

#### Dataset

...Can be found under `Data` 
