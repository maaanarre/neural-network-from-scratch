# neural-network-from-scratch


This is a  simple example of how a neural network works
This can helped me understand how to build and train a neural network without using big libraries like TensorFlow/pytorch

---
![image](https://github.com/user-attachments/assets/451b95f4-4068-4282-862c-aab28d8d85be)


## Files

### 1. `Activation_Function.py`

This file has the **activation functions**. These are used in the NN. It supports:

- ReLU (Rectified Linear Unit)
- Sigmoid
- Tanh

Each function has:

- `feed_forward` – to calculate the activation
- `back_prop` – to calculate the gradient during training

---

### 2. `fc_layer.py`

This file has the **fully connected layer** (dense layzer). Each layer:

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
