CNN-based Image Classification with Multiple Datasets
This repository contains two separate implementations of Convolutional Neural Networks (CNN) trained on two different datasets:

Kaggle Dataset: The first notebook (CNN-Kaggle.ipynb) is trained on a dataset from Kaggle, focused on image classification tasks.
NUAA Dataset: The second notebook (CNN-NUAA.ipynb) uses the NUAA dataset, likely related to face detection or liveness detection, based on common uses of this dataset.
Project Overview
This project showcases the application of CNNs for image classification using two distinct datasets. Both datasets are preprocessed and trained using Keras and TensorFlow frameworks. The goal of this project is to demonstrate the adaptability of CNNs across different domains with minimal architectural changes.

Key Features
Multiple datasets: The CNNs are trained on different datasets, allowing for a comparison of model performance across domains.
Keras/TensorFlow implementation: Both models are implemented using Keras and TensorFlow for easy customization and scalability.
Visualization and Evaluation: The notebooks include model accuracy, loss visualizations, and evaluations such as confusion matrices, and accuracy scores to assess model performance.
Datasets
Kaggle Dataset:
This dataset is used for training an image classification model, likely sourced from a Kaggle competition or public dataset.
NUAA Dataset:
The NUAA dataset is commonly used for face liveness detection or related image recognition tasks.
Requirements
Python 3.x
TensorFlow
Keras
Matplotlib
NumPy
Pandas
Jupyter Notebook
How to Run
Clone the repository.
Install the required packages from requirements.txt or using:
bash
Copy code
pip install -r requirements.txt
Open either CNN-Kaggle.ipynb or CNN-NUAA.ipynb in Jupyter Notebook.
Follow the steps in the notebook to load data, train the model, and visualize results.
Results
The CNN models achieve reasonable accuracy on both datasets, showcasing the potential of CNNs for different image classification tasks. The Kaggle model focuses on general image classification, while the NUAA model is trained on a more specialized task, like face liveness detection.


