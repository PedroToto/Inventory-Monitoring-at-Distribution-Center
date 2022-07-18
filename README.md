# Inventory Monitoring at Distribution Centers
More Distribution centers are adopting types of robotics technology as a part of their operations than ever before. Objects are carried in bins which can contain multiple objects. In this project, we build a model that can count the number of objects in a bin. A system like this can be used to track inventory and make sure that delivery consignments have the correct number of items. To build this project we used AWS SageMaker which is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. And machine learning engineering practices to fetch data from a database, upload the training data to an S3 bucket, and then train a machine learning model. 

# Project Set Up and Installation
In this section we will present the differents steps for our set up.
### 1. Set up Amazon SageMaker Studio domain

|   |  |
| ------------- | ------------- |
| On Amazon Sagemaker, i clicked on Getting Started, then clicked on Set up Sagemaker Domain  | ![This is an image](https://github.com/PedroToto/Inventory-Monitoring-at-Distribution-Center/blob/main/image/Set%20up%20Amazon%20SageMaker%20Studio%20domain1.png)  |
| In the Set up Sagemaker Domain page, i typed a name for the Control Panel and select Create a new role  | ![This is an image](https://github.com/PedroToto/Inventory-Monitoring-at-Distribution-Center/blob/main/image/Set%20up%20Amazon%20SageMaker%20Studio%20domain2.png)  |
| In the Create an IAM role pupop i selected Any S3 Bucket and clicked on Create role | ![This is an image](https://github.com/PedroToto/Inventory-Monitoring-at-Distribution-Center/blob/main/image/Set%20up%20Amazon%20SageMaker%20Studio%20domain3.png) |
| Once the status is ready, we launch our Studio domain by clicking on Launch app and select Studio | ![This is an image](https://github.com/PedroToto/Inventory-Monitoring-at-Distribution-Center/blob/main/image/Set%20up%20Amazon%20SageMaker%20Studio%20domain4.png) |



This project will serve as a demonstration of end-to-end machine learning engineering skills that you have learned as a part of this nanodegree.
