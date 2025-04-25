# 👕 Fashion MNIST Clothing Classification with TensorFlow

This is a guided project based on the official [TensorFlow tutorial](https://www.tensorflow.org/tutorials/keras/classification) that demonstrates how to classify images of clothing using a simple neural network. The Fashion MNIST dataset is used to train a model that can recognize different types of clothes such as shirts, shoes, bags, and more.

---

## 📂 Dataset

The [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist) contains 70,000 grayscale images (28x28 pixels) across 10 categories of clothing items:

| Label | Description       |
|-------|-------------------|
| 0     | T-shirt/top       |
| 1     | Trouser           |
| 2     | Pullover          |
| 3     | Dress             |
| 4     | Coat              |
| 5     | Sandal            |
| 6     | Shirt             |
| 7     | Sneaker           |
| 8     | Bag               |
| 9     | Ankle boot        |

- **60,000** training images
- **10,000** test images

---

## 🧠 Model Overview

The neural network is built using TensorFlow’s high-level Keras API:

- **Input Layer:** Flattens 28x28 input image into a 784-dimensional vector  
- **Hidden Layer:** Dense layer with 128 neurons and ReLU activation  
- **Output Layer:** Dense layer with 10 units and softmax activation  

**Training Settings:**

- Optimizer: `Adam`  
- Loss: `SparseCategoricalCrossentropy`  
- Metric: `Accuracy`  

---

## 💻 Getting Started

### 🛠️ Prerequisites

Make sure you have **Python 3.7+** installed. Then follow the steps below.

### 🔧 Setup with Virtual Environment (Recommended)

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/fashion-mnist-classification.git
   cd fashion-mnist-classification
