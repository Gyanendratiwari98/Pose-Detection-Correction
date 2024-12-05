# Pose-Detection-Correction
Develop an AI model that identifies yoga poses and provides real-time feedback for alignment and accuracy.
Yoga Pose Classification
This repository contains a machine learning project that classifies yoga poses into five categories: Downdog, Goddess, Plank, Tree, and Warrior2. The model is trained using a custom dataset and implements a convolutional neural network (CNN) for pose detection and classification.

Dataset
The dataset used for this project is the Yoga Pose Classification Dataset.

Dataset Details:
License: CC0-1.0 (Public Domain)
Classes:
Downdog
Goddess
Plank
Tree
Warrior2
Training Images: 800
Validation Images: 197
Project Workflow
Data Preparation :

Images were preprocessed and split into training and validation sets.
Standard augmentations were applied to increase dataset diversity.
Model Architecture:

The model is a CNN with the following layers:
[Add details about layers, e.g., Conv2D, Pooling, Dense]
Optimizer: [e.g., Adam]
Loss Function: Categorical Crossentropy
Training:

Number of epochs: 12
Validation accuracy achieved: 93.91%
Evaluation:

Performance metrics such as accuracy, precision, recall, and F1-score were used for evaluation.
A confusion matrix was generated to identify misclassifications.
Results
Training and Validation Metrics:
Training and Validation Loss: The loss consistently decreased over epochs, with validation loss stabilizing around 0.15.

Training and Validation Accuracy: The model achieved a validation accuracy of 93.91% by the 12th epoch.

Classification Report:
Class	Precision	Recall	F1-Score
Downdog	13%	13%	13%
Goddess	20%	23%	21%
Plank	21%	22%	21%
Tree	29%	26%	27%
Warrior2	16%	15%	15%
Macro Average (Precision, Recall, F1-Score): 20%
Predicted Sample
Input Image:

Predicted Class: Plank

Confidence: 99.18%


Future Work
Data Augmentation:
Use techniques such as rotation, flipping, and scaling to further augment the dataset.
Model Optimization:
Experiment with deeper architectures like ResNet or EfficientNet.
Fine-tune hyperparameters for better performance.
Class Imbalance Handling:
Address class imbalance to improve precision and recall across all classes.
Real-time Implementation:
Integrate the model into a real-time yoga pose correction system.
