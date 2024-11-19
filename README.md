# DeepLearning-FlowerClustering

A scenario is provided and deep learning (CNN) techniques are used to build a model that clusters Flowers into groups of 10. Concepts of Data Augmentation, Hyperparameter Tuning, L2 regularization and Early Stoppings are implemented.

**Scenario:** A renowned botanist, Dr. Krupa, has been working on understanding the visual characteristics that distinguish flower-species. While she has collected data on major flower species, To assist her research, you’ve been tasked with building a AI model. Dr. Krupas’s primary concern is that while you might be able to classify flowers into their main species categories (e.g., Flower1, Flower2,..ect), Some tulips may have slight color variations or petal shapes that aren't yet recognized as distinct varieties. Use a CNN Model to extract the features and build a model to group the similar flowers. Prepare a report that includes steps followed to build and finetuning of the model. Print the array of all classified flowers should be named categories listed above.

**Convolutional Neural Networks (CNN):** A specialized type of deep learning model designed for processing structured grid-like data, such as images. It contains
- > **Convolutional Layers:** Use filters (kernels) to extract features like edges, textures, or patterns from input data by sliding over it and performing mathematical operations.
- > **Pooling Layers:** Reduce the spatial dimensions of feature maps, retaining essential features while lowering computational cost (e.g., MaxPooling or AveragePooling).
- >** Fully Connected Layers:** Combine extracted features and perform the final classification or regression task.

**Sequential Model:** A simple way to build neural networks in which layers are added one by one in a linear stack. Each layer feeds into the next, without branching or looping.

**Data Augmentation:** A technique to artificially increase the size and diversity of the training dataset by applying transformations such as rotation, flipping, cropping, zooming, or shifting to the images.It helps prevent overfitting, as the model learns from a more diverse set of examples. It makes the model more robust to variations in real-world data.

**Hyperparameter Tuning:** The process of optimizing the hyperparameters of the model (e.g., learning rate, batch size, number of layers, filters, kernel size, etc.) to improve performance. It determines the best configuration for the model to achieve the highest accuracy or lowest loss without overfitting or underfitting.

**L2 Regularization:** Also known as Ridge Regularization, it adds a penalty term proportional to the square of the weights to the loss function, thereby discouraging overly large weights. It prevents overfitting by ensuring the model doesn't rely excessively on any single feature or input, leading to better generalization.

**Early Stopping:** A technique to stop the training process when the model's performance on the validation set stops improving, even if the training loss continues to decrease. It prevents overfitting by halting training at the optimal point where the model generalizes best to unseen data.
