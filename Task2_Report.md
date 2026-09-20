# Task 2: Deep Learning – CIFAR-10 Image Classification

## Objective
To build and evaluate a Convolutional Neural Network (CNN) for classifying CIFAR-10 images into 10 different classes.

## Dataset
The CIFAR-10 dataset contains 60,000 color images of size 32×32 pixels belonging to 10 classes:
- Plane
- Car
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Model
A CNN model was implemented using PyTorch for image classification.

## Training Results
The model was trained for 3 epochs.

| Epoch | Training Accuracy |
|------|-------------------|
| 1 | 48.33% |
| 2 | 65.27% |
| 3 | 72.48% |

## Test Result
The final test accuracy achieved was:

**72.59%**

## Evaluation
A confusion matrix and classification report were generated to evaluate the model performance.

The model performed well on classes such as car, frog, ship and truck, while classes such as cat and bird were more difficult to classify.

## Inference
The trained model was tested on a sample CIFAR-10 image. The model correctly predicted:

**Actual Class: Cat**  
**Predicted Class: Cat**

## Conclusion
The CNN successfully classified CIFAR-10 images with a test accuracy of **72.59%**. The results show that the model learned useful visual features during training and was able to correctly classify many test images.