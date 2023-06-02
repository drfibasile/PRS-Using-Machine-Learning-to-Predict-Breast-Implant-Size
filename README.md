Breast Implant Size Prediction Model
This repository houses the code for a machine learning model that accurately predicts breast implant sizes for augmentation surgeries. The model is trained on a dataset comprising medical records of 1000 patients, including demographic and anthropometric measurements.

Key Features
Data Preprocessing: The code includes comprehensive data preprocessing, including handling missing data, outliers, and categorical variables.

Model Training: Utilizes a supervised machine learning algorithm, trained on a dataset from 800 initial cases, to predict the optimal breast implant size based on patient-specific parameters.

Model Testing and Validation: Includes retrospective analysis of an additional 200 cases to validate the model's accuracy in predicting the implant size chosen by the surgeon and patient. This step allows us to assess the model's robustness and reliability in a real-world clinical scenario.

Performance Metrics: The model's performance is evaluated using various metrics  to provide a holistic view of its predictive power and accuracy.

Model Interpretability: The code also includes features importance analysis, providing insights into which variables are most influential in determining the predicted breast implant size.

This machine learning model aims to enhance the accuracy of preoperative assessments, improve patient satisfaction, surgical outcomes, and reduce the likelihood of re-operations due to size adjustments. It represents a significant step towards integrating AI and machine learning in the field of plastic and reconstructive surgery.


HOW TO USE MODEL
Summary:
Click the right arrow
Use the buttons to upload or enter data
Hit the rectangular Run button to get outputs
First step for all the cells below would be to click on the right pointed arrow (one that looks like this); once done you can upload files, use the run button, or the textboxes by using the rectangular buttons.

Use the cell below to train the model. Please make sure you upload a csv. One that looks like this. This file will be used to train the model

Please make sure you always run the first step, i.e. train the model before attempting to make predictions in step 2 or generating visuals in step 3

Please make sure the values in the input file are consistent i.e. either A, B or a,b for socioeconomic throughout the data file. The training process is case sensitive and it will consider A as a separate socioeconomic category than a. Similarly, medim will be a different category than medium for relative size col. These discrepancies can significantly impact model's accuracy on top of having the potential to throw errors while running the script

Please Run the cell below (click the right pointed arrow) to make predictions by either uploading a file or by using the text boxes to manually add info about a patient. Once you press the arrow, you have to either upload a file or enter data manually that you want to get predicitons on.

Please note that you do not have to do the numerical mapping as the code takes care of it. For instance, use "HS" for education instead of 1.

Additionally, please note different categories in the data such as A, and B in socioeconomic col etc. are case-sensitive. You cannot use a for A as the model will treat them as different labels and it will impact the accuracy score and may even casue the script to break.

Use the upload or manual entries one at a time i.e. do not use both upload and manual entry feature simultaneously. Upload the file you want to use to make predictions and press run. Then remove the uploaded file by pressing the right pointed arrow. Now do not upload the file and use manual entries to make prediction for one patient.

Alternatively, you can first use manual boxes. Enter values and press Run to get the prediction for one patient. Clear the entries by pressing the right pointed arrow and then can upload the file to make predictions.
