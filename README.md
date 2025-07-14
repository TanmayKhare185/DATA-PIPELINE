 # 🧠 CIFAR-10 Image Classification using Convolutional Neural Networks (CNN)

This repository contains a deep learning project where a Convolutional Neural Network (CNN) is trained to classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) into 10 categories. The project is implemented using TensorFlow and Keras in Google Colab.

## 🚀 Project Highlights

- 📦 Dataset: CIFAR-10 (60,000 32x32 color images across 10 classes)
- 🧱 Model: CNN with 3 convolutional layers and 2 max-pooling layers
- 🎯 Output: Classification into categories such as airplane, dog, truck, etc.
- 📊 Performance: Achieves ~71% accuracy on the test set after 10 epochs

## 🛠️ Tech Stack

- Python
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pillow (PIL)

📈 Results

✅ Final Test Accuracy: ~71.3%

📉 Loss and accuracy curves plotted to analyze model training

📷 Sample predictions shown with color-coded correctness


📷 Sample Output

Predicted vs True labels are visualized using resized CIFAR-10 images. Labels are color-coded:

✅ Green = Correct Prediction

❌ Red = Incorrect Prediction
📦 Installation & Usage

1. Install dependencies:

pip install tensorflow matplotlib pillow


2. Run the notebook in Google Colab or locally using Jupyter.



💡 Future Improvements

Add data augmentation to boost performance

Use dropout layers to prevent overfitting

Experiment with advanced architectures like ResNet or VGG


🤝 Acknowledgments

TensorFlow documentation

CIFAR-10 dataset by Alex Krizhevsky
