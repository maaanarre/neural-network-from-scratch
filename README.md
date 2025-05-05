# neural-network-from-scratch


This project is a simple example of how a neural network works.  
It is written in Python and uses only **NumPy**.  
This can help beginners understand how to build and train a neural network without using big libraries like TensorFlow or PyTorch.

---

## 📁 Files in This Project

### 1. `Activation_Function.py`

This file has the **activation functions**. These are used in the neural network to add non-linearity. It supports:

- ReLU (Rectified Linear Unit)
- Sigmoid
- Tanh

Each function has:

- `feed_forward` – to calculate the activation
- `back_prop` – to calculate the gradient during training

---

### 2. `fc_layer.py`

This file has the **fully connected layer** (also called dense layer). Each layer:

- has weights (initialized randomly)
- uses one activation function
- can do forward pass and backward pass
- can update its weights using gradient descent

---

### 3. `nn.py`

This file creates the **neural network** using fully connected layers. You can:

- Add layers with activation functions
- Do forward pass (to get predictions)
- Do backward pass (to train the model)

---

### 4. `main.py`

This is the **test file**. It creates some random data and tests the activation function.

---
