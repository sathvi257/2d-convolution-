# INTRODUCTION TO CNN 

A Convolutional Neural Network (CNN) is a type of deep learning model designed to process and analyze visual data, such as images or videos. It leverages convolutional layers to automatically detect patterns, such as edges or textures, by applying filters to the input data. These filters help extract hierarchical features from low-level (edges, colors) to high-level (shapes, objects). CNNs typically include pooling layers for downsampling and reducing spatial dimensions, and fully connected layers at the end for classification or regression tasks. Thanks to their ability to learn spatial hierarchies, CNNs are particularly powerful for image recognition, object detection, and other computer vision tasks.

## OUR PROJECT - 2D CNN 

A 2D Convolutional Neural Network (2D CNN) is a specialized neural network designed to process two-dimensional data, such as images. It applies convolutional layers with 2D filters (kernels) to extract spatial features from the input data, like edges, textures, and shapes. These filters slide across the image in both height and width dimensions (heightxwidth), creating feature maps that capture important visual patterns. 2D CNNs also often include pooling layers to reduce the spatial size of feature maps, improving computational efficiency and robustness. This architecture is particularly effective in image classification, object detection, and other computer vision tasks.

## Steps involved in the same -

- [CONVOLUTION](#convolution)
- [MAXPOOLING](#maxpooling)
- [FLATTENING](#flattening)

# Step 1 - CONVOLUTION

This layer applies convolution operations to the input using a set of filters (kernels). Each filter performs a sliding window operation over the input, producing feature maps that highlight certain aspects of the image, such as edges, textures, or patterns. The convolution operation involves multiplying a portion of the input by the filter and summing the results.
Each filter has a specific size (e.g., 3x3 or 5x5) and typically multiple filters are used in a layer to capture different features.

Image and filter taken in our project is - 6x6 and 3x3 data respectively.
![image](https://github.com/user-attachments/assets/02d490e0-dfaa-4b6a-84bb-4a555cab9604)
![image](https://github.com/user-attachments/assets/70f4f5a6-cbc5-4aaa-816e-4a8106cb4287)

