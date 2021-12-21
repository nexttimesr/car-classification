# car-classification
Use machine learning CNN to classify cars from different brands and models

## Data
Data comes from Stanford Car Classification dataset

https://ai.stanford.edu/~jkrause/cars/car_dataset.html

Reshape the images to (256, 256) and (224, 224) using ImageDataGenerator with batch size 32

### Directories
project.ipynb main code file for the project

project.pdf PDF file of project.ipynb

project.pptx Presentation for the project

projectdata/names.csv Name of the classes for the classification

projectdata/car_data/car_data/train Training data 

projectdata/car_data/car_data/test Testing data

googled 5 googled picture of 5 different car, used for testing. 
-Corresponds to ['Bentley Continental GT Coupe 2012', 'Bugatti Veyron 16.4 Convertible 2009', 'Ferrari 458 Italia Coupe 2012', 'Lamborghini Aventador Coupe 2012', 'Rolls-Royce Ghost Sedan 2012']

## Model 1
1 Conv2D Layer with MaxPooling, BatchNormalization and Dropout

2 FC Layers for input and output

## Model 2
3 Conv2D Layer with MaxPooling, BatchNormalization and Dropout

2 FC Layers for input and output

## Model 3
5 Conv2D Layer with MaxPooling, BatchNormalization and Dropout

2 FC Layers for input and output

## Model found online
https://www.kaggle.com/elmahy/tiny-models-with-the-cars-dataset-70-accuracy

MobileNetV2 network

## Testing
Validate using testing data

Additional test with 1 batch of testing data and 5 googled image for visualization


