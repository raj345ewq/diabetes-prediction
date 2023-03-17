# INSPIRATION 

Creating a machine learning model to predict diabetes is a promising and challenging project that has several sources of inspiration. One of the primary motivators is the public health concerns associated with the disease's increasing prevalence. A predictive model that can identify individuals at high risk of developing diabetes could enable early interventions to prevent or manage the disease. Personal motivation, research opportunities, and technological advancements are other potential sources of inspiration for developing a diabetes prediction model. The complexity of diabetes as a disease, the availability of large datasets, powerful computational resources, and advanced machine learning algorithms make it an exciting and rewarding project for those with a background in machine learning and an interest in health research. Overall, creating a machine learning model to predict diabetes has the potential to contribute significantly to our understanding of the disease and have a significant public health impact.

# What It Does ![image](https://user-images.githubusercontent.com/72274851/218503394-b52dfcc9-0620-4f44-94f5-46a09a5cc970.png)

The provided notebook "Predict Diabetes.ipynb" implements a machine learning model that predicts whether a patient has diabetes or not based on certain clinical and diagnostic measurements.

The dataset used in this notebook is the Pima Indians Diabetes Dataset, which contains various features such as blood glucose level, BMI, age, and pregnancy history, among others. The model uses these features to train a logistic regression algorithm to predict whether the patient has diabetes or not.

The notebook performs several steps to create and evaluate the model, including data preprocessing, feature engineering, and model training and testing. The accuracy of the model is evaluated using various performance metrics such as accuracy, precision, recall, and F1-score.

Overall, the notebook demonstrates how machine learning can be used to develop a predictive model for diabetes diagnosis based on clinical and diagnostic measurements, which could have potential applications in healthcare and medical research.

# How I built it ![image](https://user-images.githubusercontent.com/72274851/218502434-f6e66043-0db0-4f85-b7f4-f33b2d33df1f.png)

### ✅ First I Import libraries

### ✅Understand the data

### ✅Create a Correlation and visualize it

![1](https://user-images.githubusercontent.com/72274851/218495633-19d2cf0b-5b18-4774-8f3d-e18f6b77286b.jpg)

### ✅Test Different Models and find the best model out of it


- [x]LR: 0.848684 (0.036866)
- [x]KNN: 0.840789 (0.023866)
- [x]CART: 0.857895 (0.024826)
- [x]RF: 0.881579 (0.026316)
- [x]SVM: 0.853947 (0.036488)
- [x]XGB: 0.890789 (0.020427)
- [x]LightGBM: 0.885526 (0.024298)

- [x] SVM --> 0.10681818181818181
- [x] Logistic Regression --> 0.9522727272727273
- [x] RF --> 0.9840909090909091
- [x] XGBoost --> 0.9931818181818182


### ✅Save the model


# What I learned ![image](https://user-images.githubusercontent.com/72274851/218499685-e8d445fc-e35e-4ab5-abc1-c32462592603.png)



✅Building application using intel oneDAL:The Intel oneAPI Data Analytics Library (oneDAL) contributes to the acceleration of big data analysis by providing highly optimised algorithmic building blocks for all phases of data analytics (preprocessing, transformation, analysis, modelling, validation, and decision making) in batch, online, and distributed processing modes of computation.The library optimizes data ingestion along with algorithmic computation to increase throughput and scalability.

✅Building a diabetes prediction involves a significant amount of research and development. During the process, I likely learned a number of things, including:

✅Medical Science: I likely gained a deeper understanding of medical science and the various factors that affect health.

✅Machine Learning: I likely learned about different machine learning algorithms and how they can be applied to predict crop yields and make recommendations for farmers.

✅Data Analysis: I likely gained experience in collecting and analyzing large amounts of data, including historical crop yield data and soil data, to train our machine learning models.


✅Collaboration: Building a project like this likely required collaboration with a team of experts in various fields, such as soil science, machine learning, and data analysis, and I likely learned the importance of working together to achieve common goals.

These are just a few examples of the knowledge and skills that i likely gained while building this project. 
Overall, building a crop recommendation application is a challenging and rewarding experience that requires a combination of technical expertise and agricultural knowledge.



## Guide Lines 

### Packages and Tools Required:
```
Pandas 
Matplotlib
Seaborn
Scikit Learn
Jupyter Notebook
```
### Package Installation
```
pip install numpy
pip install pandas
pip install seaborn
pip install scikit-learn
pip install matplotlib
```
Jupyter Notebook Installation Guide  https://jupyter.org/install
