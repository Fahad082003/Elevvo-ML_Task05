Traffic Sign Recognition using CNN

Elevvo Internship – Task 05

Description
This project implements a Convolutional Neural Network (CNN) to classify traffic signs using the GTSRB dataset. The model is trained with data augmentation, L2 regularization, Dropout, and learning rate scheduling for robust performance.

Dataset
GTSRB (German Traffic Sign Recognition Benchmark)
Train & Test images resized to 64x64
Labels inferred from folder structure

Model Architecture
Conv2D → MaxPooling → Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Dropout → Softmax
Optimizer: Adam
Loss: Sparse Categorical Crossentropy
Callbacks: ReduceLROnPlateau
Data Augmentation
Rotation, Width/Height Shift, Zoom, Shear
Rescaling 1./255

Results
Training Accuracy: 95.3%
Validation Accuracy: 89.2%
Predictions visualized with true vs. predicted labels

Dependencies
Python 3.x
TensorFlow / Keras
NumPy, Pandas, OpenCV, Matplotlib, Seaborn
Scikit-learn

NumPy, Pandas, OpenCV, Matplotlib, Seaborn

Scikit-learn
