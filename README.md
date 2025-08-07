# Apple Instance Segmentation using Mask R-CNN and Detectron2

## Project Overview
This project's objective was to develop and evaluate a computer vision model capable of performing instance segmentation on images of apples. The model was built using the powerful Detectron2 framework, which provides a robust and efficient implementation of state-of-the-art detection and segmentation algorithms.

## Model and Configuration
The chosen model for this task was **Mask R-CNN**, a well-regarded algorithm for instance segmentation.

* **Framework:** Detectron2
* **Model:** Mask R-CNN with a ResNet-50-FPN backbone
* **Pre-training:** The model utilized weights pre-trained on the COCO dataset for effective transfer learning.
* **Training Iterations:** The model was trained for **5000 iterations**.

## Dataset
The model was trained and evaluated on a subset of the **MinneApple dataset**, a benchmark specifically designed for apple detection and segmentation. The dataset's characteristics presented a unique challenge:

* **Total Images:** 670
* **Total Annotations:** 28,183
* **Annotation Density:** An average of **42.06 apples per image**.

The relatively small number of images combined with the high density of crowded, often overlapping, apples in each scene made this a challenging task for the model to learn and generalize from.
