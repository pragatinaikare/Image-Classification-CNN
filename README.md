# Clothing Classification Using FashionMNIST Dataset

#### BLOG LINK - 

### Table of Contents
- Introduction
- Instructions to Run the Code
- Dataset Overview
- Models Trained
- Results and Evaluation 
- Model Interpretability 
- Project Report



### Introduction
-----
In this project, We are creating a classification model to accurately identify various articles of clothing using the FashionMNIST dataset, enabling accurate identification and categorization of various articles of clothing.

### Instructions to Run the Code
---
Prior to initiating the project, verify that all necessary dependencies are installed.


### Dataset Overview
---
Prior to executing the code, ensure your data is structured as specified below and locate it within the "Data" directory:

Data - https://drive.google.com/drive/folders/1adq5kWrFdUy3TnWCA3Is3e7n1DT8YiGX?usp=sharing

### Models Trained 
---
- Results 


| Model                 | Best Parameters                           | Accuracy |
|-----------------------|-------------------------------------------|----------|
| Convolutional Neural Network (CNN) | filters_layer1 = 64, filters_layer2 = 128, filters_layer3 = 256, kernel_size = (3,3)  | 91.97%   |
| Random Forest         | 'max_depth': None, 'n_estimators': 300         | 86.85%   |
| K-Nearest Neighbors   | 'n_neighbors': 7        | 86.26%   |
| Decision Tree         | 'criterion': 'entropy', 'max_depth': None        | 76.92%   |



### CNN Model Interpretability Using Grad-CAM
---

In this project, Grad-CAM was employed as a crucial interpretability tool to visualize and comprehend the decision-making process of the Convolutional Neural Network (CNN) model. Grad-CAM facilitates understanding by highlighting the regions within images that heavily influence the model's predictions, aiding in discerning which parts of the input image contribute most to the model's classification decisions.



In the provided image above, the Grad-CAM heatmap illustrates the regions contributing significantly to the model's classification decision. These visualizations are instrumental in explaining the CNN's behavior, providing valuable insights into its inner workings.



Project Report
Refer to the project_report.pdf file in this repository for a comprehensive report detailing the data preparation, exploratory data analysis, model selection, evaluation metrics, interpretability, and business insights.

