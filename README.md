# Machine-Unlearning
This project demonstrates the concept of machine unlearning using the MNIST handwritten digits dataset. The goal is to train a neural network to recognize digits, then selectively "unlearn" a specific digit, and finally retrain the model to recover its performance.

Key Features

Utilizes PyTorch for building and training the neural network
Implements a simple feedforward neural network for digit classification
Demonstrates the process of unlearning specific data (digit '5')
Visualizes the model's accuracy throughout the learning, unlearning, and relearning processes

Methodology

Initial Training: The model is trained on the full MNIST dataset.
Unlearning: The model is then made to "forget" the digit '5' using a novel unlearning technique.
Relearning: Finally, the model is retrained on the full dataset to recover its performance.

Technical Details

Dataset: MNIST handwritten digits
Model Architecture: 3-layer feedforward neural network
Unlearning Technique: Using a uniform distribution as the target for the digit to be unlearned
Performance Metric: Classification accuracy on the test set

Results
The project demonstrates:

High initial accuracy on digit classification
Significant drop in accuracy after unlearning digit '5'
Recovery and slight improvement in accuracy after relearning

Future Work

Experiment with unlearning multiple digits
Implement more sophisticated unlearning techniques
Explore the impact of unlearning on model interpretability

Conclusion
This project provides a practical demonstration of machine unlearning, a crucial concept in AI ethics and data privacy. It showcases how models can be made to selectively forget certain data while maintaining overall performance.
