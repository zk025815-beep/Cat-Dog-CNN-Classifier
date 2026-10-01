# Cat-Dog CNN Classifier

A deep learning image classification project that uses a Convolutional Neural Network (CNN) to classify images as either **Cat** or **Dog**.

## Project Overview

This project demonstrates an end-to-end image classification workflow using TensorFlow/Keras.

The project includes:

* Dataset downloading using KaggleHub
* Image validation and cleaning
* Image preprocessing
* CNN model development
* Model training and evaluation
* Cat vs Dog image prediction
* FastAPI deployment for inference

## Dataset

The project uses the **Dog and Cat Classification Dataset** from Kaggle.

The dataset is downloaded programmatically using KaggleHub, so the dataset itself is not stored in this repository.

Dataset source:

`bhavikjikadara/dog-and-cat-classification-dataset`

## Project Structure

```text
cat-dog-cnn-classifier/
│
├── notebook/
│   └── cat_dog_cnn_classifier.ipynb
│
├── app/
│   └── app.py
│
├── models/
│   └── .gitkeep
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pillow
* KaggleHub
* FastAPI
* Uvicorn

## Workflow

```text
Kaggle Dataset
      ↓
Dataset Download
      ↓
Image Validation & Cleaning
      ↓
Image Preprocessing
      ↓
CNN Model
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Cat / Dog Prediction
      ↓
FastAPI
```

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd cat-dog-cnn-classifier
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Running the Notebook

Open:

```text
notebook/cat_dog_cnn_classifier.ipynb
```

Run the notebook cells to:

1. Download the dataset
2. Clean invalid images
3. Prepare the dataset
4. Build the CNN
5. Train the model
6. Evaluate performance
7. Test predictions

## FastAPI

The FastAPI application is located in:

```text
app/app.py
```

Run the API with:

```bash
uvicorn app.app:app --reload
```

Then open the API documentation at:

```text
http://127.0.0.1:8000/docs
```

## Model Output

The model predicts one of two classes:

* Cat
* Dog

## Future Improvements

* Hyperparameter tuning
* Data augmentation
* Transfer learning using a pretrained CNN
* Improved model accuracy
* Docker deployment
* Cloud deployment

## Author

Zeeshan Khan
