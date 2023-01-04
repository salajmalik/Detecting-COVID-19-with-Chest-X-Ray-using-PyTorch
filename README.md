


# __Detecting COVID 19 with Chest X-Ray using PyTorch__

<p align='center'>
  <a href="#">
    <img src='https://github.com/swapnil18800/Detecting-COVID-19-with-Chest-X-Ray-using-PyTorch/blob/master/proj_png/covid%2019%20pytorch.png' alt="head_image">
  </a>
</p>

This repository is a case study for detecting COVID-19 with Chest X-Ray using PyTorch from COVID-19 Radiography Dataset on Kaggle

## __Dataset__

__Chest X-ray images for COVID-19 dataset:-__ 

In our current release, there are `1143` COVID-19 `positive images`, `1341` `normal` images and `1345` `viral pneumonia` images.

```python
# Create api key -> account ->Create New Token 
# .json file is genrated 

!pip install -q kaggle
from google.colab import files 
files.upload() #upload kaggle.json
```
```bash
!mkdir -p ~/.kaggle 
!cp kaggle.json ~/.kaggle/ 
!ls ~/.kaggle 
!chmod 600 /root/.kaggle/kaggle.json 

# API Command 
!kaggle datasets download -d tawsifurrahman/covid19-radiography-database

```
## __Objective__

- Create custom Dataset and DataLoader in PyTorch
- Train a ResNet-18 model in PyTorch to perform Image Classification



Open latest version of notebook in __Jupyter Notebook__.

## Project Structure

- Task :zero::one: _Importing the Dataset from Kaggle_
- Task :zero::two: _Importing Libraries_
- Task :zero::three: _Preparing Training and Test Sets_
- Task :zero::four: _Creating Custom Dataset_
- Task :zero::five: _Image Transformations_
- Task :zero::six: _Prepare DataLoader_
- Task :zero::seven: _Data Visualization_
- Task :zero::eight: _Creating the Model_
- Task :zero::nine: _Training the Model_
- Task :one::zero: _Show the Predictions_
- Task :one::one: _Saving the Model_
- Task :one::two: _Inference on a Single Image_

## Model Training Privew 
<p align='center'>
  <a href="#">
    <img src='https://github.com/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch/blob/master/proj_png/01_train.png?raw=true' alt="head_image">
  </a>
</p>

## Prediction Preview

<p align='center'>
  <a href="#">
    <img src='https://github.com/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch/blob/master/proj_png/02_pred.png?raw=true' alt="head_image">
  </a>
</p>
 
