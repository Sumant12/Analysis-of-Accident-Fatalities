			NASS CDS Dataset Analysis

Team Members 
##############################
	1. Sai Priya Sudhi reddy (RED ID:819923631)
	2. Sreerag Sreenivasan (RED ID: 820911878)

Project Description
##############################
The goal of the project was to predict the chances of survival in road accidents using various machine learning models of spark data frames and RDDs . We also wanted to analyze the influence of airbag, seatbelts etc in safety of drivers and passengers in a vehicle.
The dataset was found to be a highly imbalanced one and hence we extended our project to different case studies to see how Data frame and RDD ML models handle this scenarios.

CASE STUDY 1: Data frame ML Models with default hyper parameter - To show that data is imbalanced
CASE STUDY 2: Data frame ML Models with tweeted Hyper parameter - to handle imbalanced data
CASE STUDY 3: RDD based ML models with tweeted Hyper parameter - to handle imbalanced data
ANALYSIS on THE DATA SET. 

Dataset
################################

Source Link : https://vincentarelbundock.github.io/Rdatasets/datasets.html

Item Name : nassCDS

CSV Dataset Link : https://raw.githubusercontent.com/vincentarelbundock/Rdatasets/master/csv/DAAG/nassCDS.csv


Third party Python code - for LibSVM Format: 
-----------------------
we used third party code to convert our csv file to libSVM Format. Below is the link
	Git Hub link :
	-------------------- 
		https://github.com/zygmuntz/phraug/blob/master/csv2libsvm.py
	Command to execute the code:
	--------------------------------
		csv2libsvm.py <input file> <output file> [<label index = 0>] [<skip headers = 0>]
	
		<input file> : This parameter takes the path to csv file
		<output file> : Path to store the libsvm file
		<label index> : index of the label in our case it is 3
	
	Usage : csv2libsvm.py nassCDS.csv libSVM.data 3 0

Note: We also attached libsvm file which we obtained after using this resource

Jupyter Notebook - Kernel used
============================= 
	Apache-toree



