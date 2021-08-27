
 
# Data Mining and Warehousing Mini Project

Understand the data in order to predict who survived and who did not in the Titanic disaster.


## Installation

To Run mini project use Google Colab Notebook or Jupyter Notebook


To import csv files in project using local drive
```bash
  from google.colab import files
  uploaded = files.upload()
```
It will prompt you to select a file. Click on “Choose Files” then select and upload the file

In Jupyter Notebook give path of the CSV file

Save the csv file in your directory. i.e where you store the file
```bash
  data=pd.read_csv('directory/ csv stored file name.csv')
  test=pd.read_csv('directory/ csv stored file name.csv')
```
