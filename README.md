# Chest-Xray-Classification-Utilizing-CNN-with-Optimized-Hyperparameters
This study presents a deep learning algorithm developed from the ground up to categorize as well as confirm the existence of COVID in a set of X-ray imaging data. Designed a CNN architecture from the ground up to retrieve elements from provided X-ray data to categorize them and identify the individual contaminated with COVID.

(1) Dataset Description

(2) Preprocessing & Augmentation

(3) Proposed Architecture

(4) Tech/Stacks

(5) Result

(6) Conclusion

Dataset Description
The following public datasets were used in this study:

(1) https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

(2) https://data.mendeley.com/datasets/9xkhgts2s6

(3) https://www.kaggle.com/datasets/nih-chest-xrays/data

The first Database is used to compile chest X-rays of COVID-19 positive pictures and normal images. Images of bacterial pneumonia are sourced from the second Dataset. Furthermore, photos of pneumothorax are obtained from the third Dataset.

Preprocessing & Augmentation:

-Resized all pictures to 224 × 224 pixels,


-Used the min-max normalization method to rescale all pixel values [0, 1],

-Employed photo augmentation for solving the issue of a short dataset and to improve the accuracy rate while limiting model overfitting.

### Proposed Architecture

![Schematic](https://user-images.githubusercontent.com/48941639/216800649-3d1972bf-65d4-44e0-b5d9-1cf68894cd35.png)

## Fig: Schematic Block-diagram of the Convolutional Neural Architecture

### Tech/Stacks
 
 ## Python

 ## Keras/TensorFlow

### Results
## - Training & Validation Accuracy

![T-V-Accuracy](https://user-images.githubusercontent.com/48941639/216800671-10668072-c3b5-4306-bc33-6cce98918d1b.png)

  #                           Fig: Training and Validation Accuracy

### Learning Curve

![Learning Curve](https://user-images.githubusercontent.com/48941639/216800662-38ff01c1-4a06-462b-b24d-c518a68c1416.png)

  #                           Fig: Training and Validation Graph

### Confusion Matrix

![CM](https://user-images.githubusercontent.com/48941639/216800685-6fff0287-380e-4341-a97d-db48235940bc.png)

#                             Fig: Connfusion Matrix

### GradCAM

![GradCAM](https://user-images.githubusercontent.com/48941639/216800701-1680724c-6839-4e7f-8cd1-9794916f629a.png)

#                             Fig: Heatmap Visualization Using GradCAM

### Conclusion

Demonstrated how to use chest imaging to classify COVID and other lung-related illnesses. Developed this architecture from scratch and distinguished it from different approaches. This study will improve the health of at-risk individuals in the polluted area primarily affected by lung diseases. It will help the medical sector determine the conditions by analyzing the affected area of the chest x-ray.
