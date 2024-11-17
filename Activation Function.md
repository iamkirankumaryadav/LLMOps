# Activation Functions

- Activation functions are crucial components that introduce non-linearity into the model.
- This non-linearity is essential for learning complex patterns in data.
- Without it, a neural network would simply be a linear model, no matter how many layers it has.

### How do they work?
1. **Input:** A neuron receives input signals, each multiplied by a weight.
2. **Weighted Sum:** These weighted inputs are summed together, and a bias term is added.
3. **Activation Function:** The result of the weighted sum is passed through an activation function.
4. The activation function introduces non-linearity, transforming the input into an output.
5. **Output:** The output of the activation function is then passed to the next layer of neurons or used as the final output of the network.

### Why are they important?
- **Non-Linearity:** They enable the network to learn complex patterns that cannot be captured by linear models.
- **Decision-Making:** They help the network make decisions based on the input data.
- **Feature Extraction:** They aid in extracting relevant features from the input data.

### Common Activation Functions
1. **Sigmoid:**
- Squashes the input to a value between 0 and 1.
- Used in older networks but less common now due to the vanishing gradient problem.

2. **Tanh:**
- Similar to sigmoid but outputs values between -1 and 1.
- Can be more effective than sigmoid in some cases.

3. **ReLU (Rectified Linear Unit):**
- Outputs the input directly if it's positive, otherwise, it outputs 0.
- Widely used due to its simplicity and efficiency.

4. **Leaky ReLU:**
- A variant of ReLU that outputs a small positive value for negative inputs.
- Helps address the "dying ReLU" problem.

5. **ELU (Exponential Linear Unit):**
- Similar to Leaky ReLU but uses an exponential function for negative inputs.
- Can be more effective than Leaky ReLU in some cases.

6. **Softmax:**
- Often used in the output layer for multi-class classification.
- Converts a vector of numbers into a probability distribution.

### Choosing the Right Activation Function:
- The choice of activation function depends on the specific problem and network architecture.
- However, ReLU and its variants are commonly used in many modern neural networks due to their simplicity and effectiveness.
