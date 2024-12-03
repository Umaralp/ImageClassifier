# Image Classifier

This repository demonstrates a **Convolutional Neural Network (CNN)** implemented using TensorFlow/Keras to classify images. The project is built as a foundation for image classification tasks and uses the popular MNIST dataset for handwritten digit recognition.

## 📜 Project Overview
This project:
- Implements a CNN model to classify handwritten digits (0–9).
- Utilizes the MNIST dataset for training and testing.
- Showcases the application of deep learning in image recognition.

## 📂 Dataset
- The **MNIST dataset** consists of:
  - **60,000 training images**.
  - **10,000 test images**.
- Each image is grayscale, with dimensions **28x28 pixels**.

## 🛠️ Features
- Preprocessing pipeline:
  - Normalization of pixel values to the range `[0, 1]`.
  - Reshaping input images to `(28, 28, 1)` for compatibility with CNNs.
  - One-hot encoding for labels.
- CNN Architecture:
  - **Convolutional Layers** for feature extraction.
  - **Pooling Layers** for dimensionality reduction.
  - Fully connected layers for classification.
- **Model Evaluation**: Accuracy metrics and test set predictions.

## 🚀 Getting Started
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Libraries: `TensorFlow`, `NumPy`, and `Matplotlib`.

  
Install dependencies:
pip install tensorflow numpy matplotlib

Running the Project
Clone the repository:
git clone https://github.com/Umaralp/ImageClassifier.git

Navigate to the project directory:
cd ImageClassifier

Run the Python script:
python mnist_cnn.py

📊 Model Performance
Training Accuracy: ~99%
Test Accuracy: ~98%

🖼️ Example Output
Here’s a sample prediction from the model:


📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.

🤝 Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.

📧 Contact
For questions or feedback, reach out:

Umaralp: junaid.umar.ju@gmail.com
GitHub Profile: Umaralp https://github.com/Umaralp
