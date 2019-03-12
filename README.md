# IoT Detection with AWS

**Rachel Qu**

This project aims to build machine learning models to classify types of devices that connected to organizations. Based on log data, various features were engineered and selected, XGBoost model was built and tunned. Samples of working with log data and of building machine learning models can be found in the two folders.

**Content:**

* Data_Preparation 
	- IP_Mac_Mapping.ipynb: an example file used to map IP address and MAC address
	- Clean_Data_Pipeline.ipynb: an example file used to clean log data from S3

* AWS_ModelBuilding
	- AWS_S3_ReadData.ipynb: an example file used to read data from S3 to SageMaker
	- AWS_SageMaker_IoTDetection.ipynb: an example file used to build and tune IoT detecion model with SageMaker 
	- Explanatory_Data_Analysis.ipynb: an example file used to do basic explanatory analysis on log files and test out model performance on selected features
	- Kmeans_Device_Identification.ipynb: an example file that use Kmeans to find natrual groupings in IoT devices


