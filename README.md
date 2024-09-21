# Optimizing CNNs for Image Classification Using Advanced Gradient Descent Techniques

## Project Overview

This project focuses on optimizing Convolutional Neural Networks (CNNs) for image classification tasks using advanced gradient descent techniques. The primary goal was to explore how different optimization algorithms—such as Stochastic Gradient Descent (SGD), Adam, RMSprop, and Adamax—affect the training speed and accuracy of CNNs when applied to the CIFAR-10 dataset.

### Key Features
- **Dataset**: CIFAR-10, consisting of 60,000 32x32 color images across 10 classes.
- **Model Architecture**: CNN with convolutional, pooling, dropout, and fully connected layers.
- **Optimization Techniques**: Implemented and compared the effectiveness of SGD, Adam, RMSprop, and Adamax optimizers.
- **Regularization Methods**: Applied techniques like Dropout and L2 regularization to prevent overfitting.
- **Performance Metrics**: Evaluated models based on test accuracy and training time.

### Results
- **Baseline Accuracy**: 70.71%
- **Best Performance**: Achieved 85.50% accuracy using the Adam optimizer with learning rate scheduling.
- **Other Optimizers**: SGD (83.30%), RMSprop (84.50%), and Adamax (84.79%) showed competitive performance.

### Tools & Frameworks
- **TensorFlow** and **Keras** were used for model development, training, and evaluation.

## Future Work
- Explore additional optimizers such as Nadam and AMSGrad.
- Test on larger datasets and more complex architectures like ResNet or DenseNet.
- Use hyperparameter optimization techniques to fine-tune models further.
