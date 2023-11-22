# Histopathologic-Cancer-Detection

Overview

This repository contains code and resources for the Histopathologic Cancer Detection. The goal of this work is to develop an algorithm capable of identifying metastatic cancer in small image patches extracted from larger digital pathology scans. The dataset used in this work is a modified version of the PatchCamelyon (PCam) benchmark dataset, which is a subset of the Camelyon16 Challenge dataset.

Dataset

Training Images: 220,000

Evaluation Images: 57,000

Image Format: TIF

Image Size: 96 x 96 pixels

Channels: 3

Bits per Channel: 8

Data Type: Unsigned char

Compression: Jpeg

Data Description

The dataset is a balanced subset, with a 50/50 ratio between positive and negative examples.

Positive label indicates the presence of at least one pixel of tumor tissue in the center region (32 x 32px) of the image.

Negatively labeled images may contain metastases in the outer region.

Duplicates have been removed from the dataset.

Data Quality

All glass slides are part of routine clinical care and of diagnostic quality.

Slides were manually inspected for quality, and a pathologist was consulted if scanning issues might affect diagnosis.

File Descriptions

train_labels.csv: Ground truth labels for the images in the training folder.

train: Folder containing training images.

test: Folder containing images for prediction.

