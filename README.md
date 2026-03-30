# Tensorflow VS PyTorch
In this notebook, I implemented a simple convolutional neural network (CNN) for digit classification using both TensorFlow and PyTorch

The aim of this project was to compare TensorFlow (Keras API) and PyTorch by implementing the same convolutional neural network (CNN) for digit classification in both frameworks.

### Model building:
In Keras, the model was defined in just ~7 lines of code, while in PyTorch it required ~20 lines due to the need to explicitly define the architecture and forward pass.

### Model training:
Keras allowed training in a single line using model.fit(), whereas in PyTorch I had to implement the full training loop manually, resulting in ~25–30 lines of additional code.

### Results:
Both frameworks achieved similar performance, with validation loss of approximately 0.058 (Keras) and 0.07 (PyTorch).

### Conclusion:
Keras provides a much simpler and more user-friendly workflow, similar to assembling building blocks, which makes it ideal for quick experimenting. In contrast, PyTorch requires more effort due to manual training loop implementation, but offers greater flexibility and control over the training process.
