# EXNO:4-DS
# AIM:
    To read the given data and perform Feature Scaling and Feature Selection process and save the data to a file.

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
<img width="777" height="640" alt="image" src="https://github.com/user-attachments/assets/17394b93-15e5-4ffe-a52a-eb2937f3cbe8" />
<img width="901" height="633" alt="image" src="https://github.com/user-attachments/assets/fee0eed9-8981-497e-8d23-9c3feba50bd4" />
<img width="668" height="782" alt="image" src="https://github.com/user-attachments/assets/9f3ad6de-1948-42ab-81b0-025b9841f205" />
<img width="601" height="767" alt="image" src="https://github.com/user-attachments/assets/c03d9841-8c3b-4c87-ade0-8e15b2bdb4f2" />
<img width="737" height="612" alt="image" src="https://github.com/user-attachments/assets/0c43e590-8553-4e6a-8321-bc36bb6bff17" />
<img width="736" height="646" alt="image" src="https://github.com/user-attachments/assets/f5361024-53ae-4906-bc66-aead53cceef6" />
<img width="836" height="663" alt="image" src="https://github.com/user-attachments/assets/4969a085-856a-45ca-bb0f-a43917e8ba85" />
<img width="982" height="562" alt="image" src="https://github.com/user-attachments/assets/ea92b027-ed55-4846-8d38-7414ce61c30a" />


# RESULT:
The given dataset was successfully read and cleaned. Feature Scaling was performed to bring the features into a suitable range, and Feature Selection was applied to identify the important features. The processed data was successfully saved to a file. Thus, feature scaling and feature selection were successfully performed.
