# Similarity Document Template Matching and Feature Map Extraction using ResNet-101 & Vector database

This repository hosts a program leveraging the ResNet-101 convolutional neural network to extract feature maps from images. These feature maps are then transformed into vector representations and loaded into Qdrant, a vector search engine, for efficient similarity matching. The program is specifically designed to identify and retrieve the top 10 most similar images to a given input image, based on their feature map proximity in the vector space.

## Overview

The project capitalizes on the capabilities of the ResNet-101 architecture for feature extraction, enabling the creation of compact vector representations of images. These vectors are then utilized within Qdrant, a powerful vector search engine, to perform similarity matching efficiently. By comparing feature map similarities, the program can identify visually similar images to a given input image, facilitating applications such as image search and retrieval.

## Methodology

1. **Feature Extraction**: Utilize ResNet-101 to extract high-level feature maps from images.
2. **Vector Transformation**: Transform the extracted feature maps into compact vector representations.
3. **Vector Search Engine Integration**: Load the vector representations into Qdrant for efficient similarity matching.
4. **Similarity Matching**: Given an input image, compare its vector representation with those stored in Qdrant to identify the top 10 most similar images.

## Usage

1. **Image Processing**: Ensure that the input images are preprocessed appropriately, if necessary, to align with the requirements of ResNet-101.
2. **Feature Extraction**: Utilize the provided script to extract feature maps from the images using ResNet-101.
3. **Vector Transformation**: Transform the extracted feature maps into vectors suitable for vector space representation.
4. **Vector Search Engine Configuration**: Configure Qdrant to load the vector representations for similarity matching.
5. **Similarity Document Matching**: Use the provided functionality to identify the top 10 most similar images to a given input image.

## Requirements

- Python 
- ResNet-101 implementation (e.g., PyTorch, TensorFlow)
- Qdrant (vector search engine)
- Image processing libraries (e.g., OpenCV)


## Running the Program

1. Ensure that the input images are available and preprocessed (if necessary).
2. Execute the feature extraction script to generate feature maps.
3. Transform the feature maps into vector representations.
4. Load the vectors into Qdrant.
5. Utilize the similarity matching functionality to find the top 10 most similar images to a given input image.
