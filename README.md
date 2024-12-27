# In-depth-CNN-Cloud

## Model 1

**Target:**
  

*   Get the set-up right
*   Set Transforms
*   Set Data Loader
*   Set Basic Working Code
*   Set Basic Training  & Test Loop


**Results:**


*   Parameters: 6.3M
*   Best Training Accuracy: 99.99
*   Best Test Accuracy: 99.41


**Analysis:**


*   Heavy Model
*   Model is over-fitting


**File Link:**


[model_1.ipynb](./model_1.ipynb)

## Model 2

**Target:**
  
*   Reduce parameters bellow 20k count
*   Make sure, defined model get trained
*   Limit the 15 epoch


**Results:**


*   Parameters: 12,854
*   Best Training Accuracy: 99.32
*   Best Test Accuracy: 99.16


**Analysis:**


*   Light weight Model
*   Added Batch Normalization, MaxPool2d and dropout = 0.1
*   Initial 5 epocs has more test accuracy than training accuracy


**File Link:**


[model_2.ipynb](./model_2.ipynb)

## Model 3
**Target:**
  
*   Reduce parameters to 5k count
*   Make sure, defined model get trained
*   Limit the 15 epoch


**Results:**


*   Parameters: 5,048
*   Best Training Accuracy: 98.71
*   Best Test Accuracy: 99.21


**Analysis:**


*   Light weight Model
*   Added Batch Normalization, MaxPool2d and dropout = 0.1
*   Model is getting trained in very efficent way and in very fast


**File Link:**


[model_3.ipynb](./model_3.ipynb)

## Model 4
**Target:**
  
*   Reduce parameters bellow 10k count
*   Use skip connections
*   Limit the 15 epoch
*   Achieve test accuracy > 99.40%


**Results:**


*   Parameters: 7,902
*   Best Training Accuracy: 98.99
*   Best Test Accuracy: 99.41


**Analysis:**


*   Very light weight Model
*   Added Batch Normalization, MaxPool2d and dropout = 0.1
*   Initial 5 epocs has more test accuracy than training accuracy


**File Link:**


[model_4.ipynb](./model_4.ipynb)
