## Attention-based Image Classification CNN

This repository contains code for an attention-based Convolutional Neural Network (CNN) for image classification. The model is designed to pay attention to relevant parts of the input images, improving classification accuracy.

### Prerequisites
Ensure you have the following packages installed:
- `numpy`
- `pandas`
- `matplotlib`
- `tensorflow`

### Usage
1. Clone the repository:

```bash
git clone https://github.com/<username>/Attention_based_image_classification_CNN.git
```

2. Navigate to the repository directory:

```bash
cd Attention_based_image_classification_CNN
```

3. Run the Python script:

```bash
python attention_cnn.py
```

### Description
- The script sets up data generators using `ImageDataGenerator` to load and preprocess images from directories. It rescales the pixel values of images to be in the range [0, 1].
- The model is built using the functional API of TensorFlow/Keras. It consists of convolutional layers followed by attention mechanisms and fully connected layers.
- The model is compiled using Adam optimizer with a learning rate of 0.0001 and categorical cross-entropy loss.
- Training is performed using the `fit` method on the training and validation data generators.

### Files
- `attention_cnn.py`: Python script containing the model definition, data loading, model compilation, and training.
- `LICENSE`: License file.
- `README.md`: This readme file.

### Acknowledgments
- This code is adapted from a research project on attention-based CNNs for image classification.
