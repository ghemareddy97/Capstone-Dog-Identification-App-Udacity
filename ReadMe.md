# Dog Identification App 

## Contents

* Procedure
* Dependencies
* Execution
* Motivation
* Results
* Licencing and Acknowledgments


### Procedure

* Import Datasets
* Detect Humans
* Detect Dogs
* Create a CNN to Classify Dog Breeds (from Scratch)
* Use a CNN to Classify Dog Breeds (using Transfer Learning)
* Create a CNN to Classify Dog Breeds (using Transfer Learning)
* Write your Algorithm
* Test Your Algorithm

### Dependencies

Basic [Anaconda](https://www.anaconda.com/) installation would be enough to run this code. The following packages have been used to create this notebook.

| Library | Usage |
| ----------------- | ----------- |
|Pandas|to handle and manipulate data|
| Numpy | to perform numpy array operations |
| Matplotlib | for data visualization |
| re | regular expressions for performing string operations on the data in the dataframe |
| flask | Webserver for serving backend  |
| sklearn | for datasets  |
| glob | file handling  |
| keras | for deeplearnign and CNN |
| cv2 | image manipulation and handling |

### Execution

Execution of this code is fairly simple. Run the code cells one by one or run them all from the Cell option in the toolbar. 

* Keep in mind if you want to train the model yourself you will need a GPU.

* If you want to test the model efficiency you may run the function dog_human_predict_breed below in the notebook. Example of how to run the function is already added in the notebook.

### Motivation

This project is a Capstone for Udacity data science nanodegree program. Purpose is recognition of a dog's breed from an image. If there is no dog in the image provided it has to check for a human using the haar cascade weights and display the breed that the human resembles. 

* Three architectures were used in this project. Basic CNN from scratch with conv2d and maxpooling layers with respective dropouts.
* VGG16 architecture with a globalaveragepooling layer and a dense layer.
* Resnet50 architecture with a globalaveragepooling layer and a dense layer. 

The final algorithm uses the Resnet50 architecture and runs fairly fast.  

### Results

Run the last two code cells with the image path provided to the function dog_human_predict_breed to check for results. 

## Licensing and Acknowledgements
This code is part of the Udacity project for data science nanodegree. I don't hold rights for the data. Feel free to use the code. 