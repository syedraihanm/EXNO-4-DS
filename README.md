# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.
# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![Ds exp 4 ipynb - Colab_page-0001](https://github.com/user-attachments/assets/badc3c65-5478-4d29-a4f6-b7f55e83f099)
![Ds exp 4 ipynb - Colab_page-0002](https://github.com/user-attachments/assets/3d9e1d88-a3d4-405d-9dbf-11e1aaca0a28)
![Ds exp 4 ipynb - Colab_page-0003](https://github.com/user-attachments/assets/5e6eae16-66b5-4bb1-8b57-3076666b0da4)
![Ds exp 4 ipynb - Colab_page-0004](https://github.com/user-attachments/assets/2efb7023-0b36-4ec2-95eb-d0e71daf1876)
![Ds exp 4 ipynb - Colab_page-0005](https://github.com/user-attachments/assets/7a52dd65-c680-44ca-b93c-cb21b105a162)
![Ds exp 4 ipynb - Colab_page-0006](https://github.com/user-attachments/assets/78f1af03-33ea-4f91-b884-4c396767deee)

# RESULT:
         Thus we have read and performed  Feature Scaling and Feature Selection process and save the data to a file.
