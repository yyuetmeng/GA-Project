#  Capstone: Pneumonia Detection in Chest X-Ra imags using deep learning model

### Description

There is an outbreak of bacteria in the community that is affecting children and elderly. The infection can be detected via Chest X ray. 
The normal chest X-ray depicts clear lungs without any areas of abnormal opacification in the image. 
Bacterial pneumonia typically exhibits a focal lobar consolidation whereas viral pneumonia manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs. 
We are establishing a diagnostic tool based on a deep-learning framework for the screening of patients that are affected by this bacteria so that doctors can focus on the treatment

---
### Input

I have obtained the dataset from https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia. I am provided with a train dataset, validate dataset and test dataset

---

### Approach
- Due to massive amount of data to be trained, this model is trained in the Google Colab environment
- The approach taken in this POC is to 1) create base model from scratch 2) build 2 CNN models from scratch and assess 3) Use Pre-Trained VGG-19 models 4) Manipulate Classifier layers in Pre-Trained VGG-19
- Assess which are the preferred approach

### Result
- Result shows that pre-trained models with changes in Classifier layers can provide the best accuracy and recall metrics.
- Comparing Pytorch and Keras libraries, Pytorch training performance is faster than Keras and suitable for large datasets. Keras is generally easier to make changes to the models.
- Further enhancement will be 1) contrast enhancement 2) segmentation of lung image before classification 3) ensemble of pre-trained models


### Deliverables

- Due to limitation of storage in GitHub,input data will not be uploaded. You can download the dataset from the above link given.
- I am using 6 models to perform the POC. 3 different categories of the models namely CNN built from scratch, pre-trained models of VGG-19 from Pytorch and pre-trained models of VGG-19 from Keras
- A Jupyter Notebook with my analysis 
- An executive summary of my results.
- A short presentation outlining your process and findings for a semi-technical audience.
- Readme file 
- Slide deck as PDF
---
