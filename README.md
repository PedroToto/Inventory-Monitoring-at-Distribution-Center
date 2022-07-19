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

# Dataset

### Overview
For this project we will be using the Amazon Bin Image Dataset. The dataset contains 500,000 images of bins containing one or more objects. For each image there is a metadata file containing information about the image like the number of objects, it's dimension and the type of object. The bin images in this dataset are captured as robot units carry pods as part of normal Amazon Fulfillment Center operations. However we only use a subset of this dataset which is about 10,436 images distributed into 5 clases.
![This is an image](https://github.com/PedroToto/Inventory-Monitoring-at-Distribution-Center/blob/main/image/data_distribution.png)

### Access
Since the data is located in a S3 Bucket we used the json file provided to get the directory of images and the download_file methode to download the data. After downloaded the data we uploaded the data into our S3 Bucket.

# Model Training


This project will serve as a demonstration of end-to-end machine learning engineering skills that you have learned as a part of this nanodegree.
