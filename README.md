![image](https://github.com/LocNguyenTKP/Land_Surface_Temperature_Future_Prediction/assets/66542803/98d919fc-bd4f-4e0d-818b-789bb27dea87)

# Land_Surface_Temperature_Future_Prediction

## Project Summary
The primary goal of this project is to offer a reliable method for predicting LST from satellite data, which is vital for environmental studies and climate monitoring. The application automates the data retrieval, preprocessing, and machine learning prediction stages, ensuring an efficient workflow that can be utilized by researchers and practitioners in the field of geospatial data analysis.

## Key Features:

Google Earth Engine Integration: Utilizes GEE for accessing a vast repository of satellite imagery.
Machine Learning Prediction: Implements RandomForestClassifier to predict LST based on the input satellite images.
Data Management: Seamlessly connects to Google Drive to handle data input and output operations.
Geospatial Data Handling: Employs rasterio for efficient handling and manipulation of geospatial data formats.
##  Step-by-Step Guide
* ### Step 1: Authentication and Initialization

Authenticate and initialize Google Earth Engine using your Google account credentials. This step ensures you have access to Earth Engine's data repositories.
* ### Step 2: Mount Google Drive

Mount your Google Drive to the script environment to access and store TIFF files and other data used in the project. This integration simplifies data management and accessibility.
* ### Step 3: Install and Import Dependencies

Install necessary Python libraries such as rasterio, which are crucial for geospatial data processing. The script automatically manages these installations.
* ### Step 4: Data Retrieval

Use the script to retrieve TIFF files from the specified Google Drive path. These files contain satellite imagery data that will be used for temperature prediction.
* ### Step 5: Data Preprocessing

Preprocess the data using rasterio to handle TIFF files and prepare the data for machine learning processing. This involves reading, transforming, and structuring the data into a format suitable for analysis.
* ### Step 6: Machine Learning Model Training

Train the RandomForestClassifier with the preprocessed data. This model learns from the data to predict LST based on the features extracted from satellite images.
* ### Step 7: Prediction and Analysis

Use the trained model to predict LST and analyze the output. The results are used to understand temperature patterns and can be visualized using additional Python libraries if needed.

![image](https://github.com/LocNguyenTKP/Land_Surface_Temperature_Future_Prediction/assets/66542803/a51e5b3d-1a8d-451c-8433-f7a82abedddc)

* ### Step 8: Results Handling
Output the prediction results to TIFF files and store them back to Google Drive or display them directly from the script for analysis and reporting.

![image](https://github.com/LocNguyenTKP/Land_Surface_Temperature_Future_Prediction/assets/66542803/2769f55c-af61-4b07-ab0c-7f595e2f6964)

![image](https://github.com/LocNguyenTKP/Land_Surface_Temperature_Future_Prediction/assets/66542803/951a718c-283e-40af-bd8a-2b8ea6985c3c)

## Conclusion
This project provides a streamlined, efficient approach to predicting land surface temperature using satellite imagery and machine learning. It is designed to be modular and easy to integrate into larger environmental monitoring and analysis workflows.
