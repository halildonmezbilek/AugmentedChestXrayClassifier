# Classifying Common Thoracic Diseases with Augmented Pediatric Chest X-ray Dataset

## Introduction
This project aims to develop an AI model capable of classifying common thoracic diseases in pediatric patients using an augmented dataset of chest X-ray images. By incorporating advanced data augmentation techniques and leveraging the VinDr-PCXR dataset, we strive for high accuracy in disease classification, addressing the challenges of class imbalance and enhancing model generalizability.

## Dataset
The VinDr-PCXR dataset, originating from a pediatric hospital in Vietnam, comprises 9,125 high-quality X-ray images labeled for various lung pathologies. Our augmentation techniques expanded this dataset, improving the model's robustness and interpretability.

## Methodology
We utilized data augmentation methods and a deep convolutional neural network (DCNN) architecture for disease classification. Key to our approach was addressing the dataset's class imbalance and incorporating patient demographic data to improve diagnostic accuracy.

## Model Architecture and Training
Our model architecture includes ResNet-18 combined with YOLOv8 for feature extraction, with a focus on detecting critical findings from X-ray images. We employed weighted binary cross-entropy loss for training and optimized the model using Optuna for hyperparameter tuning.

## Getting Started
To replicate this study:
1. Clone the repository.
2. Download the VinDr-PCXR dataset from [PhysioNet](https://physionet.org/).
3. Run the Jupyter Notebook provided in the repository to train the model and evaluate its performance.

## Results
Our model demonstrates promising results, closely matching those of similar studies in terms of precision, recall, and F1-score. Further details and performance metrics are available in the project [documentation](https://halildonmezbilek.com/blog/project-classifying-common-thoracic-diseases-with-augmented-pediatric-chest-x-ray-dataset).

## Conclusion
This project underscores the potential of AI-assisted diagnostics in pediatric radiology, offering a robust tool for classifying thoracic diseases using augmented chest X-ray datasets.

## References
A list of references supporting this study, including relevant articles and datasets can be found at [documentation](https://halildonmezbilek.com/blog/project-classifying-common-thoracic-diseases-with-augmented-pediatric-chest-x-ray-dataset).
