### Dashtoon_Submission

Visit master branch for the ipynb


## Neural style transfer model using CNN

Description:
This neural style transfer model uses a special method to blend the content of one image with the artistic style of another. It adjusts features like average and spread to match both images, creating a new combined image. By using a straightforward approach and functions, it teaches a network to mimic styles and content from different pictures.

## Installation

First, we bring in the important tools by importing packages. Setting a seed helps us to reproduce the same results later if needed. The global variables are like settings we can adjust later to change how our model works

! pip install numpy matplotlib tensorflow-datasets tensorflow


## Usage

For running it in google colab:
-upload the ipynb file to colab and change the runtime to T4 GPU

Data sets used in this project
style data(Best Artworks of All Time): https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time

content data(Pascal VOC 2007): https://www.tensorflow.org/datasets/catalog/voc

As the data set size is high, follow the steps to access it.
1. Zip the data set download and upload in google drive
2. mount the google drive
from google.colab import drive
drive.mount('/content/drive')
3.unzip the file
!unzip -uq "/content/drive/path_dataset_in_gdrive" -d "/content/drive/MyDrive/path_to_dataset_in_gdrive"
  


