# Fashion MNIST CNN Classifier 🧥👟

This project uses Convolutional Neural Networks (CNNs) with TensorFlow and Keras to classify images from the Fashion MNIST dataset.

## 🧠 Model Architecture
- Input: 28x28 grayscale images
- 2 Convolutional layers (64 filters each, 3x3 kernel, ReLU)
- 2 Max Pooling layers
- Flatten layer
- Dense layer (128 units, ReLU)
- Output layer (10 classes, Softmax)

## 🧪 Dataset
- **Fashion MNIST**: 70,000 images (60,000 train, 10,000 test)
- Labels: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

## 🚀 Training
- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- Epochs: 10

## 🔍 Visualizations
- Sample image display using Matplotlib
- CNN feature maps (activations) visualized from different layers

## 📁 Folder Structure
