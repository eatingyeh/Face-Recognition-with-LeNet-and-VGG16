# Face-Recognition-with-LeNet-and-VGG16
## 1. Goal
To classify the person in the image out of five different people.

## 2. Dataset
Original training dataset
There are five people with 10 images each in this dataset, 50 images in total:
1. My friend – Ennie
2. My friend – Jimmy
3. President of the US - Joe Biden
4. Queen of the UK - Elizabeth II
5. Myself - Teresa
These images are either downloaded from Google or provided by myself.
Class labels: 'Ennie'-1, 'Jimmy'-2, 'Biden'-3, 'Elizabeth'-4, 'Teresa'-5

After processing images, the inputs for model LeNet would be 64*64 pixels.
And the inputs for model VGG16 would be 224*224 pixels.

Additional testing dataset
This dataset is a brand new dataset, which is used to test the actual performance of LeNet and VGG16 models.
There are the same five people with 3 images each in this dataset, 15 images in total.

## 3. Tools and Algorithms
Tools
- Jupyter Notebook: To run the code.
- PIL, glob, dlib, tqdm, ntpath: To do image preprocessing, such as accessing and saving images.
- Keras: To build neural network models.
- Scikit-Learn: To do train test split and evaluate the model.
- cv2: To detect faces in images, resize images and convert images to grayscale.
Approaches
- LeNet
- VGG16

## 4. Procedure
- Data Preprocessing
- Model Defining
- Model Training
- Model Evaluating
  1. Loss
  2. Accuracy
  3. Confusion Metric
  4. Additional dataset testing

## 5. Python files
- ImagePreprocessing_LeNet
  This is for loading, processing and saving images for later use in model LeNet.
- ImagePreprocessing_VGG
  This is for loading, processing and saving images for later use in model VGG16.
- LeNet
  This is for training model LeNet.
- VGG16
  This is for training model VGG16.
- Additional dataset testing_LeNet
  This is for testing the performance of the best model of LeNet model using a brand new dataset.
- Additional dataset testing_VGG16
  This is for testing the performance of the best model of VGG16 model using a brand new dataset.


## 6. Results
Please view the code provided above for the results and more details.
