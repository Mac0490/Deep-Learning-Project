Hessian Insights: Evaluating the Impact of Width, Batch Normalization, and Optimizers in Two-Layer Neural Networks
This project investigates the relationship between neural network optimization techniques and the Hessian matrix in two-layer neural networks. The study focuses on understanding how different network architectures and optimization strategies impact the Hessian matrix and overall model performance.

Key findings include:

Neural Network Width: Wider networks exhibit a larger Hessian matrix, indicating a greater ability to learn complex patterns. However, this also increases the risk of overfitting.

Batch Normalization: When batch normalization is applied, the reduction in the Hessian trace is more gradual compared to networks without it. This suggests that batch normalization introduces noise into the gradients, influencing the training dynamics.

Optimizer Impact: Different optimizers, such as ADAM and SGD, have distinct effects on the Hessian trace and model convergence. ADAM tends to navigate the loss landscape more aggressively, while SGD provides a steadier convergence.

Overall, the study sheds light on the critical role of the Hessian matrix in understanding the optimization landscape of neural networks. Future work could delve deeper into advanced optimization techniques and their interactions with the Hessian matrix to further improve model training and generalization.
