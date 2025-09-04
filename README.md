# Cats vs Dogs Image Classifier

## Project Overview
This project is a deep learning-based image classifier that distinguishes between images of **cats** and **dogs**. The model is trained using a dataset provided by freeCodeCamp. It uses Convolutional Neural Networks (CNNs) to learn visual patterns from the images and predict the correct label.

---

## Dataset
- The dataset contains images of cats and dogs split into **train**, **validation**, and **test** sets.  
- Folder structure:
-cats_and_dogs/
-├── train/
-│ ├── cats/ # Training images of cats
-│ └── dogs/ # Training images of dogs
-├── validation/
-│ ├── cats/ # Validation images of cats
-│ └── dogs/ # Validation images of dogs
-└── test/ # Test images (unlabeled)
-(images)


- Dataset Source: [freeCodeCamp Cats and Dogs Dataset](https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip)

| Dataset Split | Cats | Dogs | Total |
|---------------|------|------|-------|
| Train         | 1000 | 1000 | 2000  |
| Validation    | 500  | 500  | 1000  |
| Test          | 500  | 500  | 1000  |


## Dependencies
Make sure you have the following installed:

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib (optional, for visualization)
- os, zipfile, urllib (Python standard libraries)

---

## Installation / Setup
1. Clone the project or download the repository.
2. Install required Python packages:

```bash
pip install tensorflow numpy matplotlib
