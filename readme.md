# Detection of Acute Lymphoblastic Leukemia using Transfer Learning

This repository contains the code for an undergraduate digital signal processing lab project focused on the detection of Acute Lymphoblastic Leukemia using transfer learning.

## Project Overview

Acute Lymphoblastic Leukemia (ALL) is a type of cancer that affects the white
blood cells, specifically the lymphocytes. It is the most common type of cancer in
children but can also affect adults. In the context of detecting ALL, transfer learning involves using some pre-trained models that have already been trained on a large dataset of images to quickly and accurately identify ALL in new images.

## Datasets

The dataset used in the project can be obtained from: [Link](https://www.kaggle.com/datasets/obulisainaren/multi-cancer)

Download the `ALL` folder for Acute Lymphoblastic Leukemia detection.

## Methodology

The project follows these steps:

1. **Split Dataset**: Splitting the dataset for training and testing.
2. **Model Fine-Tuning**: Fine-tuning the pre-trained models.
2. **Model Evaluation**: Evaluate the model on unseen images. 

## Scripts

The Jupyter notebooks for different stages of the project:

- `split_folders.ipynb`: To split the dataset into train/test/split
- `training.ipynb`: Model fine-turning
- `new_predictions.ipynb`: Model evaluation on new images

## Usage

To run the project, follow these steps:

1. Clone the repository.
2. Install the required dependencies.
3. Download the dataset from the given link (as a folder) in the same directory.
3. Run the .ipynb files in the following order:
   - split_folders.ipynb
   - training.ipynb
   - new_predictions.ipynb
5. For other datasets: modify the filename, input and output dimensions in the code

## Contact

For any queries, please reach out at [sadmansakib26@iut-dhaka.edu](mailto:sadmansakib26@iut-dhaka.edu).