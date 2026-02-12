

Temple Architecture Analysis using Deep Learning
Executive Summary

Temple Architecture Analysis is a deep learning based image classification system designed to identify Indian temple architectural styles namely Dravidian, Nagara and Vesara. The project applies transfer learning using a pretrained MobileNetV2 model and integrates Grad CAM visualization to improve interpretability of predictions.

The system processes temple images, extracts structural features, and classifies them into architectural categories with probabilistic confidence scores. The trained model achieved a final test accuracy of 89.19 percent on a balanced dataset of 1475 images.

A structured preprocessing pipeline was implemented including duplicate removal, stratified data splitting, image normalization and augmentation. The training process was conducted in two phases: initial feature extraction followed by selective fine tuning with reduced learning rate and early stopping to prevent overfitting.

Grad CAM was incorporated to highlight the architectural regions influencing the model decision, ensuring transparency and reliability of predictions.

An interactive web interface was developed using Gradio, enabling users to upload temple images and obtain predictions along with visual explanations and confidence metrics.

This project demonstrates the application of computer vision and transfer learning techniques in cultural heritage analysis and architectural classification.
