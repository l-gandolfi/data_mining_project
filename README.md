# Data and Text Mining

## Cervical Cancer risk: a Data Mining Approach

### Team member:
- Luca Gandolfi
- Bruno Palazzi
- Stefano Sacco

### Project aim:
Cervical cancer is a cancer arising from the cervix. Using information 
about sexual activities, smoking, contraceptives usage, infectious diseases and medical tests about a sample of 858 women provided by [kaggle](kaggle.com) in this [dataset](https://www.kaggle.com/loveall/cervical-cancer-risk-classification), an analysis about **Cervical Cancer risk factors** has been performed. The aim of this study is to apply Data Mining techniques to a real case of study, in order to obtain useful insights.


### Main tasks:

#### Data Exploration
The dataset has been inspected in order to understand values
distribution for some attributes, perform data imputation on missing values and understand correlation among attributes throug a Correlation Matrix. This approach is useful to better understand the problem and to obtain an insight on what should be done next.

#### Clustering 
Clustering task has been performed on data, selecting specific attributes, in 
order to find hidden groups inside this sample of women. Once clustering tasks 
has been accomplished, it has been decided to investigate every clsuter found
looking for some common characteristics. Furthermore, a visual inspection 
of these clusters has been provided by a t-SNE plot.

#### Classification
In order to predict whether a woman will result positive
to Biopsy test given some attributes, a classification task has been performed 
using four different models:

- 2 different SVM (Support Vector Machines) SMO and sPegasos
- Multi Layer Perceptron
- Keras Deep Neural Network

Furthermore, to improve models performances it has been decided to perform Oversampling, Feature Extraction and Feature Selection, comparing results.

### How to run this project
The entire project has been developed using a free platform called **Knime** (link [here](https://www.knime.com/downloads/download-knime) to download it). Knime is an easy-to-use platform that offers an high-level view for developing steps. In fact it provides several ready to use nodes for different tasks (machine learning, data manipulation and many more). Once you have downloaded Knime from the official site and **file .knwf** from this repository, all you have to do is:

- Open Knime.
- Go through **File** > **Import KNIME workflow**.
- Now select **file.knwf** you've just downloaded from this repository.
- Run the project by clicking **green button** or pressing **SHIFT + F7**. (You can also run every single node by **right-clicking** on the node and choosing **Execute**)
