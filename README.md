# Neural Network Classifier – A, B, C Recognition

This project builds a neural network from scratch (using only NumPy) to classify 5×6 binary pixel patterns representing letters **A**, **B**, and **C**.

## 🔧 Features
- Implemented feedforward and backpropagation
- Custom sigmoid and softmax functions
- Cross-entropy loss
- Accuracy tracking and matplotlib plots

## 🧠 Architecture
- Input: 30 pixels (5x6)
- Hidden Layer: 16 neurons
- Output Layer: 3 neurons (A, B, C)

## 🧪 How to Test
Use custom binary image as input like this:

```python
test_image = np.array([
    0,1,1,1,1,0,
    1,0,0,1,0,1,
    1,0,0,0,0,1,
    1,1,1,1,1,1,
    1,0,0,0,0,1
])
