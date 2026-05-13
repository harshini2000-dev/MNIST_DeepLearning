# MNIST_DeepLearning

**Project Overview**

This project builds a Neural Network (Deep Learning model) to recognize handwritten digits (0–9) using the MNIST dataset.
The model is trained using TensorFlow/Keras and achieves ~97%+ accuracy on test data.

📊 **Dataset**

We use the MNIST dataset, which contains:

- 60,000 training images
- 10,000 testing images
- Each image is 28×28 grayscale
- Labels: digits from 0 to 9

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/34e9904b-c0d1-4566-a10c-b836c8e645df" />
<img width="450" height="450" alt="image" src="https://github.com/user-attachments/assets/a3aeaacc-7561-47eb-8aed-57e589a8ca1a" />

**⚙️ Model**

A simple Feedforward Neural Network (ANN) is used:
```
Flatten (28x28 → 784)

        ↓
        
Dense (128 neurons, ReLU)

        ↓
        
Dense (10 neurons, Softmax)
```

**Activation Functions**

 - ReLU → used in hidden layer
 - Softmax → used in output layer for probabilities

**⚙️ Technologies Used**
 - Python
 - TensorFlow / Keras
 - NumPy
 - Matplotlib
 - Jupyter Notebook

**📈 Results**
 - Training Accuracy: ~98.5%
 - Test Accuracy: ~97.4%
 - Loss: ~0.07

**📚 Future Improvements**

 - [ ] Replace ANN with CNN (better accuracy)
 - [x] Add confusion matrix visualization
 - [ ] Save & load trained model
 - [ ] Build web app using Streamlit and deploy

**⭐ Outcome**

This project is a beginner-friendly deep learning system that demonstrates how neural networks can learn to recognize handwritten digits with high accuracy.
