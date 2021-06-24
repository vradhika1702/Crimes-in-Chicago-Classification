# Crimes in Chicago Analysis
Data Mining Project

The Dataset:
URL to dataset: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2

The dataset we plan to use is a crime dataset for the city of Chicago in csv format.
This information was obtained from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. The dataset contains the crime records collected from 2001 to present in the city of Chicago. There is a total number of approximately 7 million crime records in this dataset and 22 features/attributes.


References: 

https://portal.chicagopolice.org/portal/page/portal/ClearPath/
The data is from the above reference.

-----------------------------------------------------------------------
For the purpose of comparison of classification models we all have used same preprocessed data file.The link to datafile is given below. Both the formats csv and pkl files have been generated.

Links to Preprocessed Data:

Link to csv file: https://drive.google.com/file/d/1lWPelpPwscDbsiTgIGXuvNtArosvu5kt/view?usp=sharing


Link to pkl file: https://drive.google.com/file/d/1f1XyLCFyLiMmy-DLD0kqmoShnII4ls85/view?usp=sharing

------------------------------------------------------------------------
There are 5 folders in this repo.

1. Data Processing : This folder contains a notebook which is used to create a processed data file which is used by all the classification models.
2. Classification_Models :This folder contains the notebooks for 4 different machine learning algorithms for classification.
3. Dataset : It contains the sample data just to get an idea how the dataset looks like.
4. Additional_Analysis : This folder contains the extra analysis done on data like clustering , prediction of crime and so forth.
5. Models to Load and Test on Sample Data: This folder contains a script which can be used run the random forest classification model. It also contains the pickle file for the already trained RF model and sample data pickel file that can be used to evaluate model.

---------------------------------------------------------------------------------------
Instructions to Run the code:
1. Clone the repository into your local directory.
2. Open Google Colab
3. Upload the notebooks that needed to be evaluated.
4. Data Processing notebook will need to use original dataset file. 

Link to original dataset:https://drive.google.com/file/d/1fN0eYECcdzEHvSix-jfdNMm20ilVcSay/view?usp=sharing

5. Classification Models notebook will need to use the preprocessed data file which are mentioned above under Links to Preprocessed Data.
6. For the short evaluation of RF1 model, use the files in "Models to load and test on sample data" and for evaluating RF2 model, the trained model link is mentioned in notebook itself.

