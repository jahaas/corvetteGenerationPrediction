# corvetteGenerationPrediction
Based on an Image, Predict the Corvette Generation, C1-C8

Corvette Generation Recognition Project

Introduction: 
This project is an object detection, classification and recognition project. Object detection is processing an image and detecting discreet objects within that image. Object classification is taking the objects detected and identifying what those objects are. And finally, object recognition is taking those classified objects and recognizing the differences between them. Object recognition is the most difficult of the three mentioned.

My project is an object detection, classification and recognition project. Given an image as input, I want to detect whether a car is in the image or not, classify the car as a corvette or not, and if it is a corvette, recognize the specific generation of corvette – C1 through C8.  

Requirements
- Code is written in python 3 and requires keras, sklearn, matplotlib, google_images_download, numpy, pandas, csv, tqdm, 

Datasets
- Datasets are provided for training and testing.  
- The testing dataset is named "testSet". 
- There are 3 training datasets used in the project, but only 1 training set is provided due to size ("dataSet_training"): 
 1) a subset for quick iterations, "dataSet_training"
 2) full training dataset, "dataSet"
 3) dataset with approximately 1,000 images per class, "dataSet_10000"
- User can collect their own images as well through scraping and the Stanford Car Dataset on Kaggle.

Processing
- AWS EC2 with GPU instance is necessary to process the entire dataset

iPython Notebooks
- Notebooks are provided for web scraping, data labeling, and the main notebook that includes data ingestion, data wrangling, data pre-processing, model building and tuning, transfer learning, and prediction

