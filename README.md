# Deep Learning-Based Image Classification with Transfer Learning and Fine-Tuning  

## Project Overview  
This project implements image classification using the Airplanes, Motorbikes, and Schooners dataset. Three pretrained convolutional neural network models—Xception, ResNet101V2, and InceptionResNetV2—are fine-tuned to achieve high performance metrics.  

## Features  
- **Dataset:**  
  - Classes: Airplanes, Motorbikes, and Schooners  
  - Dataset split: 75% training and 25% testing  

- **Models Used:**  
  - Xception  
  - ResNet101V2  
  - InceptionResNetV2  

- **Techniques Applied:**  
  - **Transfer Learning:** Modified the classifier layers with dropout and batch normalization, training for 10 epochs.  
  - **Fine-Tuning:** Optimized by unfreezing layers as per model-specific rules and training for an additional 10 epochs.  

- **Evaluation Metrics:**  
  - Confusion Matrix  
  - Precision, Recall, and F1-Score   
 
**Usage**
Run Transfer Learning notebooks (Model1_TL.ipynb, Model2_TL.ipynb, Model3_TL.ipynb).
Use saved Transfer Learning models for Fine-Tuning notebooks (Model1_FT.ipynb, Model2_FT.ipynb, Model3_FT.ipynb).
Evaluate performance using confusion matrices and classification metrics.
**Results**
Xception, ResNet101V2, and InceptionResNetV2 models achieved high precision and recall for classifying the dataset.
Fine-Tuning further enhanced performance compared to Transfer Learning alone.
 
