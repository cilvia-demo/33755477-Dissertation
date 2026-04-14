# 33755477 - Dissertation

##### 

##### This Git Contains the R and Python code used for my dissertation "The Validity of LLM Trait Prediction in a Recruitment Context". 

##### 

##### This includes code for the analysis and plotting, and code for minej/bert-base-personality model use in Google Colabs.



##### The steps below are for replication purposes only, and can be skipped. To view the fully cleaned final data output please see '33755477 - Data.csv'. Raw textual outputs from open ended question responses have been removed from this repository to ensure participant anonymity.

##### 

##### Order of operations if full replication is desired: (Note: some code or file names may need to be changed when loading files locally)



#### How to use Google Colabs and the Minej/bert-base-personality to obtain AI personality trait predictions



* Upload raw textual responses to a Google drive. As the raw textual responses have been removed for this public upload, researchers wishing to access the full text may contact me at ltils001@gold.ac.uk, subject to ethical approval.
* Upload the Python code in Google Colabs, to load (from Google drive) and process the data. 
* Find the completed AI predicted trait outputs in the same Google Drive.

#### 

#### I then used Excel to manually combine the AI traits scores with my Qualtrics output and create '33755477 - Self Reported.csv' which can be found in the repository.



#### Obtaining self reported trait scores and analysis



* Load '33755477 - Self Reported.csv' in RStudio.
* Run the code.
* This will calculate z-scores and create the file 'scored\_standardised\_data.csv' which can be found in your working directory (or in this repository).



#### How to create plots in RStudio



* Load the output of the analysis code 'scored\_standardised\_data.csv'.
* Run the code.
* Find the plots in your working directory.

