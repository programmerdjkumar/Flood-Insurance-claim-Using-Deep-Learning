# Flood-Insurance-claim-Using-Deep-Learning
This repository contains the csv files, jupyter files to pre process a huge 7 gb data file of Insurance claims from FEMA (Federal Emergency  Management Agency), jupyter notebook of model building and its evaluation and finally Visualization using Power BI
## The link to the entire dataset is https://www.fema.gov/openfema-data-page/individuals-and-households-program-valid-registrations-v1
## The link to the processed Flood based insurance claim dataset: https://drive.google.com/file/d/1hWnCBzSN9F2rXjQsBc2113mL0FeIjCIx/view?usp=sharing
### AIM: 
- This dataset aims to provide information about the rate and severity of flooding disasters, the scope of damage done, and the financial impact that has on insurance companies.
- Develop ML and deep learning models to predict the flood damage amount based on the insurance policy and amount of insurance and etc
- Insurance firms may identify risk factors and develop better risk management plans by examining the data on flooding claims.
### Dataset description
- This dataset includes details on insurance claims made for damage caused on by floods in different areas over a period of time.
- Here the location is represented by county, city and zip code.

- INPUT FEATURES : Damaged Zip code, IHP Amount, homeowner Insurance, home damage and etc

- TARGET VARIABLE : Flood Damage Amount (Indicates the entire damage caused by the floods) 
![image](https://github.com/programmerdjkumar/Flood-Insurance-claim-Using-Deep-Learning/assets/48883104/be06709b-7d58-4626-9bc1-2bb03efed1af)
### Results:
- After comparing the results of all 4 models the training and test error is least for deep learning, those are : 0.1230, 0.1306 respectively
- The R2 score for deep learning model i.E, 0.8697 and it is least for SVR I.E, 0.7792
- Similarly mean square error is highest for the model SVR and it is least by using deep learning model. So deep learning is best model among all. 

![image](https://github.com/programmerdjkumar/Flood-Insurance-claim-Using-Deep-Learning/assets/48883104/e1c40812-6f49-4a49-9593-46619f031d5f)

![image](https://github.com/programmerdjkumar/Flood-Insurance-claim-Using-Deep-Learning/assets/48883104/8975ad93-7201-4ac5-b037-a76c713dc975)

