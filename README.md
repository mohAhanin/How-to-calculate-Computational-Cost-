FLOPs Estimation in Keras Models
This project demonstrates how to estimate the number of FLOPs (Floating Point Operations) for Keras-based neural networks. FLOPs are a key measure of computational complexity and are especially important when optimizing models for efficiency, speed, and deployment on edge devices.

📌 Overview
The notebook provides:

A custom function to compute FLOPs for each layer in a model.

A breakdown of operations per Dense and Flatten layers.

Consideration of activation function costs (e.g., ReLU, Softmax).

An example use case with a simple feedforward network.

Visual and quantitative comparisons of FLOPs across model configurations.

⚙️ Key Concepts
FLOPs focus on the forward pass — useful for evaluating inference cost.

Optimizer, loss, and metrics (from model.compile) influence training but not the FLOPs calculation in this context.

Lower FLOPs ≠ lower accuracy — the notebook explores trade-offs in model design.
