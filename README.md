# DL TERM PROJECT

## Project Structure
Consisters of two models:
1 - CNN-based encoder and RNN-based decoder Image Captioning model\
2 - Transformer based encoder-decoder Image Captioning model\
Link for the dataset : https://drive.google.com/file/d/1FMVcFM78XZE1KE1rIkGBpCdcdI58S1LB/view?usp=sharing

## Running instructions:

### Part-A (Part - a.ipynb):

**Created and tested on kaggle only**

Upload the given dataset zip file to the kaggle datasets and name the dataset while uploading as image-captioning

Then load the uploaded dataset to the inputs
The path of the training images directory should look like this:
    **"/kaggle/input/image-captioning/custom_captions_dataset/train"**

**Run the code after making sure the GPU is turned on**



### Part-B (Part - b.ipynb):

**Created and tested on Colab only**

Create a directory called VIT in the root googe drive directory
Upload the given dataset zip file to the VIT directory in the google drive

The path of the dataset should look like this:
    **"/content/drive/MyDrive/VIT/custom_captions_dataset.zip"**


**Run the code after making sure the GPU is turned on**



## Inference of both the models

Both the parts have the outputs of the models on the test images along with correct captions in the testing and evaluation part.
