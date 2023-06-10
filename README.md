## Breast Cancer Detection(PART1)

### Data Source Information

Creator:

Dr. WIlliam H. Wolberg (physician)

University of Wisconsin Hospitals

Madison, Wisconsin, USA

Location: [Data Source](https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original)


### Attribute Information:

- Sample code number: id number
- Clump Thickness: 1 - 10
- Uniformity of Cell Size: 1 - 10
- Uniformity of Cell Shape: 1 - 10
- Marginal Adhesion: 1 - 10
- Single Epithelial Cell Size: 1 - 10
- Bare Nuclei: 1 - 10
- Bland Chromatin: 1 - 10
- Normal Nucleoli: 1 - 10
- Mitoses: 1 - 10
- Class: (2 for benign, 4 for malignant)

### Background

All of our bodies are composed of cells. The human body has about 100 trillion cells within it. And usually those cells behave in a certain way. However, occasionally, one of these 100 trillion cells behave in a different way and keeps dividing and pushes the other cells around it out of the way. That cell stops observing the rules of the tissue within which it is located and begins to move out of its normal position and starts invading into the tissues around it and sometimes entering the bloodstream and becoming is called a metastasis.

In summary, as we grow older,throughout a lifetime, we go through this kind of situation where a particular kind of gene is mutated where the protein that it makes is abnormal and drives the cell to behave in a different way that we call cancer.

This is what Dr. WIlliam H. Wolberg was observing and put together this dataset. He was trying to classify the cells into;

Malignant==> Cancerous  

Benign==> Not Cancerous cells (Healthy)



### Objectives 

The "Class" is the Target or Dependent Variable whose values were modeled and predicted by the other variables (independent or predictor variables).  The goal is to predict if a cell is Malignant (prone to cancer) or Benign (not prone to cancer), So we used classification algorithms for the prediction which are KNeighborsClassifier and Support Vector Machine and also to compare the perfrormance of the models. 


### Solution [Here](Breast_Cancer_Detection_PART1.ipynb)





