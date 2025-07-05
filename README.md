#  Handwritten Digit Classifier

A simple deep neural network built using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

---

##  Project Objective

To build and train a deep learning model that can classify digits (0–9) with high accuracy using the MNIST dataset.

---

## 🧰 Tools & Technologies

| Category        | Tools                                      |
|----------------|---------------------------------------------|
| Programming     | Python                                      |
| Libraries       | TensorFlow, Keras, NumPy, Matplotlib        |
| Dataset         | MNIST (60,000 training + 10,000 testing)    |
| Visualization   | Matplotlib                                  |

---

## 🧠 Model Architecture

| Layer Type | Description              |
|------------|--------------------------|
| Input      | Flatten (28×28 → 784)    |
| Dense 1    | 128 units, ReLU          |
| Dense 2    | 64 units, ReLU           |
| Output     | 10 units, Softmax        |

---

## 🚀 How to Run the Project

### 📥 1. Clone the Repository

```bash
git clone https://github.com/your-username/mnist-digit-classifier.git
cd mnist-digit-classifier
