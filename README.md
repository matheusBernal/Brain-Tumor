# Brain Tumor Classification with CNN
This project implements a Convolutional Neural Network (CNN) to classify brain tumor images into four categories: Glioma, Meningioma, Pituitary, and No Tumor. The model is trained from scratch using custom CNN architecture to detect and categorize brain tumors from MRI images.
Key Features:
- Custom CNN Architecture: A deep CNN with multiple convolutional and pooling layers to learn complex patterns in brain tumor images.
- Multi-class Classification: The model classifies images into four categories (Glioma, Meningioma, Pituitary, No Tumor) using softmax activation for multi-class output.
- Data Preprocessing: Uses ImageDataGenerator to preprocess and normalize images for better model performance.
- Training Visualization: Displays plots of training and validation accuracy and loss to track model performance during training.
Dataset:
- Training Set: A dataset of brain tumor images, including Glioma, Meningioma, Pituitary, and No Tumor categories.
- Validation Set: A separate dataset to validate the performance of the model during training.
Requirements:
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pillow (PIL)
How to Run:
1. Clone this repository.
2. Install the required dependencies using `pip`.
3. Place your dataset in the correct directory structure (`./Train`, `./Val`).
4. Run the training script to train the model on the dataset.
Results:
- The CNN model successfully learns to classify brain tumor images into four categories with the potential for high accuracy.
