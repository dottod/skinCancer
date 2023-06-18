# Skin Cancer Detection

This repository contains code and resources for training a deep learning model to detect skin cancer from images. The model is designed to classify images as either cancerous or non-cancerous based on visual characteristics and patterns.

## Dataset

The dataset used for training the skin cancer detection model can be downloaded from Kaggle using the following link: [https://www.kaggle.com/datasets/surajghuwalewala/ham1000-segmentation-and-classification](https://www.kaggle.com/datasets/surajghuwalewala/ham1000-segmentation-and-classification).

### Dataset Preparation

To prepare the dataset for training, follow these steps:

1. Download the dataset from the Kaggle link provided above.
2. Extract the dataset files to a location of your choice.

Please note that the original dataset lacks image classification for non-cancer images. To address this, we have augmented the dataset by adding a "Non Cancer" folder. 

To merge the non-cancer images into the dataset, perform the following steps:

1. Download the "Non Cancer" folder from this repository.
2. Create a new folder named "mergedDatasets" in the root directory of the repository.
3. Copy the contents of the "Non Cancer" folder into the "mergedDatasets" folder.
4. Copy all the image files from the downloaded Kaggle dataset into the "mergedDatasets/images" folder.

The final directory structure should look like this:

skinCancerDetectionDL.ipynb
mergedDatasets/
images/
... (all the image files from both sources)

## Model Training

To train the skin cancer detection model, follow these steps:

1. Open the "skinCancerDetectionDL.ipynb" Jupyter Notebook file.
2. Execute the code blocks in sequential order to set up the environment, load the dataset, and train the model.
3. Start by running the initialization steps to ensure all the necessary dependencies and libraries are installed.
4. Continue executing the code blocks to train the deep learning model using the prepared dataset.
5. Monitor the training progress and evaluate the model's performance using the provided evaluation metrics.

Make sure to refer to the Jupyter Notebook file for detailed instructions and explanations of each step involved in the skin cancer detection process.

## Requirements

Before running the code, ensure that you have the following dependencies installed:

- Python (version 3.6 or higher)
- Jupyter Notebook
- TensorFlow (version 2.0 or higher)
- Keras (version 2.3.1 or higher)
- NumPy

## Contributing

Contributions to this repository are welcome. If you have any improvements or bug fixes, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.
