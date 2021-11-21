 #  A Comparitive Study on Differential Privacy with Neural Networks
 
 ## Authors: Soundarya Ganesh & Araz Sharma
 
 This Folder contains codes, datasets and reports for a project on a comparitive study on Differential Privacy with Neural Networks
 
 **The Project included the following steps:**
 
1. Dataset Selection
2. EDA (Exploratory Data Analysis)
3. Feature Selection (Information + Privacy)
4. Pre-Processing

  	* 4.1 Check for Missing and Anomalous data
  
 	* 4.2 Encoding Categorical Columns
  
  	* 4.3 Standard Scaling
  
5. Train-Validation-Test Split
6. Two Approaches for Training
 I. Training an ANN
    Without Age Modification
    With Age Modification
    Dropping Age Feature
		II. Training a Differentially Private ANN
7. Results & Performance Metrics
8. Interpretation of Efficiency & Learning Outcomes

**In the sub-directory code**
* The File: **EAD_NormalANN** contains Notebook for training a normal ANN with the Churn Modelling Dataset
* The File: **EAD_Diff_Privacy_ANN** contains Notebook for training a Differentially Private ANN with the Churn Modelling Dataset
* Dataset used is: Churn_Modelling.csv

For Detailed Results and Explainations, please read the **Report Team17_ChurnModelling_DiffPriv_ANN**
 
 
 
 
 **Links for Reference:**
 
1.  https://www.kaggle.com/rohanpatnaik/churn-modelling-using-ann
2.  https://colab.research.google.com/github/anirudh161/privacy/blob/add-dpsgd-keras-tutorial/tutorials/Classification_Privacy.ipynb#scrollTo=wUEk25pgmnm-
3. https://www.youtube.com/watch?v=oNSelFJnPaM
4.  https://www.kaggle.com/shrutimechlearn/churn-modelling/code
