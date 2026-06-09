# pneumothorax-detection-deep-learning
## Objective
Because physicians often work long hours, fatigue can increase the risk of misdiagnosis. Therefore, the development of automated classification algorithms may assist physicians in diagnosing pneumothorax more accurately and efficiently. Such systems can support clinical decision-making, improve patient outcomes, and potentially save lives.
In this study, the objective is to investigate three open resources for pneumothorax detection, including the differences and characteristics of their models.
## Tools
Python, torch
## Models
Unet, Xception, AlbuNet34, Resnet50 and SCSEUnet
## Dataset
The source of the data comes from a competition held on Kaggle- SIIM-ACR Pneumothorax Segmentation. The dataset comprises 10679 DICOM files, encompassing cases both with and without pneumothorax in a ratio of 2379:8300 and annotations in the form of image IDs and run- length-encoded (RLE) masks. Some of the images contain instances of pneumothorax (collapsed lung), which are indicated by encoded binary masks in the annotations. Some training images have multiple annotations.
## Methodology
- Image Segmentation
- Evaluation index
- Compare 3 approaches of pneumothorax prediction
## What I learned
For every challenge we aim to solve using machine learning or deep learning techniques, having sufficient data is critical. Sometimes, the process of collecting this data from different sources can be daunting, and the composition of the data can also affect the results of the analysis. Although this project uses the data provided by Kaggle, I still need to learn about the composition and information of the data. In addition, I think it is important to fully understand the structure and information of the data to choose the model and parameters.
As for whether a complex model will have a relatively good accuracy rate? During my research on this issue, I found that it is not necessarily the case. We need to understand the types of problems we want to analyze and understand the characteristics of the model. As long as it is used properly, in fact, very basic architecture collocations can also have good analysis results.
Deep learning is an advanced field. When I first started, I didn’t know where to start. Fortunately, many people are very willing to share their research results and open their code on the Internet. With these resources, I began to build A complete Algorithm that has a concept. I always feel that researchers in this field will not stick to their own research results, but are happy to see everyone grow up together, solve various problems, and make contributions in various fields together. I hope that one day I can also be a researcher who can share my research results on the Internet and help others.
