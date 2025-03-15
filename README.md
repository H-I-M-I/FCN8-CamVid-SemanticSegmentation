# FCN-8 for Semantic Segmentation

This project implements a Fully Convolutional Network (FCN-8) using a VGG16 backbone for semantic segmentation on road scene images from the CamVid dataset.

## Why This Project?
Semantic segmentation of road scenes is crucial in autonomous driving, traffic analysis, and urban planning, helping in object detection and scene understanding.

## Dataset Details & Preprocessing
- Uses the CamVid dataset, which includes road scene images with pixel-wise annotations for various objects (cars, pedestrians, road, signs, etc.).
- Images are resized for efficient processing.
- Preprocessing includes data normalization and one-hot encoding of labels.

## Features
- Uses FCN-8 for pixel-wise segmentation.
- Pretrained VGG16 backbone for feature extraction.
- Trained on the CamVid dataset for road scene segmentation.

## Code Overview
- Loads and processes the CamVid dataset.
- Uses VGG16 as a feature extractor in the FCN-8 model.
- Trains the model on labeled road scene images.
- Generates segmentation masks for different objects in the scene.
