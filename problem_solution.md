# How Regularization Techniques Work

Regularization techniques address overfitting by targeting different aspects of the model or training process. Here's how they work:

1. **L1/L2 Regularization** 🏋️‍♂️

   - **What it tackles**: The weights of the model.
   - **How it works**: Adds a penalty to the loss function based on the size of the weights.

2. **Dropout** 🔌

   - **What it tackles**: The number of active nodes in the network.
   - **How it works**: Randomly disables a fraction of neurons during training, forcing the network to rely on multiple pathways and preventing over-reliance on specific neurons.

3. **Early Stopping** ⏱️

   - **What it tackles**: The training time.
   - **How it works**: Monitors validation performance and stops training when the model starts overfitting (validation error increases).

4. **Data Augmentation** 🖼️
   - **What it tackles**: The training data.
   - **How it works**: Expands the training dataset by applying transformations (e.g., rotations, flips, noise) to the input data, helping the model generalize better.

Each of these techniques targets a specific aspect of the model or training process to improve generalization and reduce overfitting.

---

**[← Previous](README.md)** | **[Next →](LX.md)**

## Navigation

- [Introduction to Regularization](README.md)
- [How Regularization Techniques Work](problem_solution.md)
- [Understanding L1 and L2 Regularization](LX.md)
- [Understanding Dropout Regularization](dropout.md)
- [Understanding Early Stopping](earlystop.md)
- [Understanding Data Augmentation](data_augmentation.md)
