# Patient Survivability Classification modelling

### Overview
 Various models were considered to classify a patient's surviability including logistic regression models, simple neutral networks, complex neural networks and bayes clasifiers.
It is found that a logistic regression model performs best with a test set accuracy of 89%, micro precision of 0.89 and micro recall of 0.89.
Note that Git imposes a 5 second timeout on rich rendering meaning you need to download the file to view it.

### Process
I chose the Support dataset provided by Vanderbilt University Department of Biostatistics and hosted on the UC Irving Machine Learning Repository 1
 . The Robert Wood Johnson Foundation funded the creation of this dataset 2
 .

The Support dataset is comprised of 9105 individual critically ill patients accross 5 medical centers in the United States over 1989-1991 and 1992-1994. The original goal of the dataset was to determine the patients 2 and 6 month survival rates based on available information including physiological, demographical and disease severity or symptom information. The Support dataset has 9105 instances and 42 features with various continous and categorical variables. This is a very rich dataset that hopefully will be of interest to a wide range of audiences.

I aim to explore the use of neural networks, bayesian inference and logistic regression models to predict whether or not a patient will die "hospdead" which is a binary categorical variable with values 0 and 1. Given this is a classification task I have disregarded the use of a linear regression and consider instead logistic regression, bayesian inference (with logistic regression) and neural network models.

I lay out in the subsequent section, 1.2, the overall structure of my approach to the assignment from initial data preprocessing, exploratory data analysis to model development and model evaluation, finishing with a discussion of the results with respect to the various performance metrics used.

It is recognised that some of the information in relation to particularly gender, race, income and educational level should be approached in a sensitive way. Data provided has been anonymised and individual patients are not identifiable in any way.

### References:
University California Irvine, 2023. URL:https://archive.ics.uci.edu/dataset/880/support2

Robert Wood Johnson Foundation, 1994. URL:https://www.rwjf.org/

Medium.URL:https://medium.com/@anushruthikae/from-raw-to-rescaled-a-guide-to-z-score-normalization-and-standardization-in-data-preprocessing-173874df077d

National Library of Medicin, 2000. URL: (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3333165/)

Danesh, Heydari. 2016.URL:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4893757/#:~:text=APACHE%20III%20is%20widely%20used,into%20the%20score%20(18)

Physiopedia, 2020. URL:(https://www.physio-pedia.com/Activities_of_Daily_Living)

Cleveland Clinic. URL:https://my.clevelandclinic.org/health/diseases/17069-heart-failure-understanding-heart-failure#:~:text=What%20is%20congestive%20heart%20failure,other%20parts%20of%20your%20body.

NHS. URL:https://www.nhs.uk/conditions/chronic-obstructive-pulmonary-disease-copd/

NHS. URL:https://www.nhs.uk/conditions/cirrhosis/

Moffitt Cancer Center. URL:https://www.moffitt.org/cancers/colon-cancer/survival-rate/#:~:text=According%20to%20the%20National%20Cancer,colorectal%20cancer%20

Cancer Research UK. URL:https://www.cancerresearchuk.org/about-cancer/lung-cancer/survival

Cancer Research UK.URL:(https://www.cancerresearchuk.org/about-cancer/oesophageal-cancer/survival#:~:text=almost%2020%20out%20of%20every,for%2010%20years%20or%20more)
