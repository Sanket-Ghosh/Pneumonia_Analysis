# Pneumonia_Analysis

# Abstract: 
Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus (purulent material), causing cough with phlegm or pus, fever, chills, and difficulty breathing. A variety of organisms, including bacteria, viruses and fungi, can cause pneumonia
Cell image pre-processing and compilation of dataset for deep learning:  The images used in this work were whole slide images provided in the PEIR-VM repository built by the University of Alabama in Birmingham. The original whole slide image data contain significant amount of redundant information. In order to achieve good classification accuracy, image segmentation and de-noising are needed to extract only blood cells and remove those redundant image pixels simultaneously. Several effective image processing techniques were used to accurately segment tiles into individual cells.

**Task:** Now we have to Recognize the future images and give the prediction result

# Context
http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

<img src="images/github-download.png">

Figure S6. Illustrative Examples of Chest X-Rays in Patients with Pneumonia, Related to Figure 6 The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs. http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
chest

# Content
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, th

e evaluation set was also checked by a third expert.

# Acknowledgements :
**Data:** https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia?

**Citation:** http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

special thanks to Shuvradip Ghosh.

# CONCLUSION:

This model undergoes different convolutional layers and maxpooling layers as a result I got a decent amount of accuracy while testing the data.
 
**Architecture:** VGG-16

**Training Accuracy: 96%
Testing Accuracy:92%**


