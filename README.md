In traditional image processing, convolution kernels (also called filters) do not involve trainable weights. These kernels, like the one you shared, are predefined matrices with fixed values that serve a specific purpose, such as edge detection, sharpening, blurring, etc. They don't change during the process—they are applied "as is" to an image to produce a particular effect.

However, in deep learning, specifically in convolutional neural networks (CNNs), convolutional layers do have trainable weights. In CNNs:

The kernel values (weights) are initially set randomly.
During training, these weights are adjusted based on the loss function, enabling the network to learn useful features for the task (like detecting edges, textures, shapes, or more complex patterns) from the data itself.
So, while classical convolutional filters are static, convolutional filters in CNNs are dynamic and learned from data, which allows CNNs to adaptively learn features useful for specific tasks, such as image classification, object detection, and more.
