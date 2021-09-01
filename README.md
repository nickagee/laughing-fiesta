# laughing-fiesta
Dog breed classificaion

[//]: # (Image References)

[image1]: ./images/blog_images/pup01.png "Sample Output"
[image2]: ./images/blog_images/class_app.png "App Workflow"

## Table of Contents

1. [Project Overview](#overview)
2. [Setup/Testing Instructions](#setup)
3. [File/Folder Descriptions](#files)
4. [Results/Findigns](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Overview <a name="overview"></a>

The aim of this project is to develop an application that predicts an image of a dog, your algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

I have also written a Medium Blog that details the steps and process that I took to complete this project.  

["Dog Breed Classification Model: DSND Capstone Project"](https://njackson-gis.medium.com/dog-breed-classification-model-dsnd-capstone-project-fd6098d692f5)

![Sample Output][image1]

## Setup/Testing Instructions <a name="setup"></a>

Git clone this repo to an environment that has the ability to train Machine Learning utilizing a GPU.  I utilized Google Colab to perform all tasks in this notebook.

**Libraries/Dependencie**

- Pandas
- Numpy
- PyTorch
- CV2
- Pillow
- Matplotlib
- Seaborn

## File/Folder Descriptions <a name="files"></a>

Within the `main/` folder is where the mechanics of the application are found.

**DogBreedApp.ipynb** is the jupyter notebook that contains all the code for setting up and running the ML models and analytics.

**DataExploring.ipynb** is the jupyter notebook that contains the code that I utilize to look at the images in the dataset.

## Findings/Results <a name="results"></a>

After training a custom model and a transfer learning model, it was no surprise that the transfer learning model performed better
than the custom model.  From the better performing transfer learning model I then created the baseline for a dog breed classification application that performs classification of an image provided and then provides an estimated breed if the image is dog or human.  

Even though my final model didn't classify all the images correctly, I believe that it is heading in the right direction. The model has a good accuracy level, and it shows that it generalizes well with images it hasn't seen before. It is my conclusion that with some more time and effort this classification model could become a real application to help people decern a dog's breed.

![App Workflow][image2]

## Licensing, Authors, Acknowledgements <a name="licensing"></a>

The data that was utilized in this project was obtained from Udacity Data Science Nano Degree.
