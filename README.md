# Chest disease classification using Convolutional Neural Networks

This project will investigate a set of convolutional neural networks, to identify diseases on
previously unseen chest radiographs. MobileNet (V1), ResNet50, VGG16 and modified
versions of the first two models are evaluated, to find and propose the most suitable architecture for the problem. The ChestX-ray14 (Wang et al., 2017) dataset provides a large collection of images in fourteen categories.


Feature maps and class activation maps are generated, to gain further insight into which
features are predominant during the classification process. Transfer learning is used as a
means to try and improve model performance.


The test results demonstrate, that a shortened version of MobileNet is the most suitable
model for the task, and significant diagnostic predictions can be made with the proposed
network architecture. Transfer learning proved to be beneficial and offered increased classification performance, regardless of the apparent domain discrepancy.


A full report of the findings is available in the following dissertation: https://drive.google.com/open?id=115NfM_HbA3DD2OePtvNM2nGgdZ93Cfg5


To run the jupyter notebook, which contains the project:
  - Download a 64-bit version of Python
  
  - Open console at .ipynb location
  
  - Acquire necessary libraries: "pip install tensorflow keras scikit-learn scipy Pillow pandas matplotlib jupyter"
  
  - Run "jupyter notebook" and open the project
  
To import the best performing model:
  - Run "Load session model" cell with "_Mobile_transfer" session parameter
  
  - Run "Import session model" cell
  
  
  
.

Dataset from: https://nihcc.app.box.com/v/ChestXray-NIHCC
