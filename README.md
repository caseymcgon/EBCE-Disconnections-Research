# EBCE-Disconnections-Research
This is the Executive Summary of a Semester-long Research Project for East Bay Community Energy (EBCE). 

# BEFORE YOU BEGIN
Note: This Repo only contains 2 files: the Executive Summary & The Final Project Presentation. 

It contains no code or the underlying data sets, as those are property of EBCE.

These 2 documents were shared with both EBCE and the University (UC Berkeley) and are not proprietary property.

# DESCRIPTION
The project's mission was to build a Machine-Learning Model that could effectively discern which buildings are likely to disconnect from the electrical grid. 

Ultimately, if we could predict which customers would disconnect, we'd be able to save time & money for both them and EBCE through mitigation programs. 

At the end of the semester, our best model was a Random Forest Model that had 89.9% Accuracy and 94.8% Recall but only 58.5% Precision. 

If we had more time (we were constrained by the length of the semester), we would have gone back and explored new features/data sets that we withheld for simplicity. We would also like to add a time component to our predictions (predict when, as well as who, will be disconnected).


# Our Data
Our Data was anonymized data from 2016-2019 consisting of approximately 97,000 connected and 33,000 disconnected EBCE customers. 
We used 3 public datasets (Customer Parcel Data, Public Census Data, and Cal Enviro Screen Data) and 1 private dataset (EBCE's data on Customer Energy Usage).
