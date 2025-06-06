# Code-used-for-master-s-thesis-on-UAV-based-aquatic-vegetation-classification
# UAV-based Aquatic Vegetation Classification along the Lieve River

This repository contains the full codebase used in the master's thesis by **Sander Van Laere**, submitted in 2025 for the MSc in Bioscience Engineering at Ghent University.

## 📘 Project Summary

This project investigates the use of drone imagery and machine learning to classify aquatic vegetation along a canal in Belgium. High-resolution RGB images collected across multiple seasons were processed and used to train supervised classification models (Random Forest, SVM, CNNs including VGG16 and Vision Transformers). The models were evaluated for classification accuracy, robustness, and seasonal generalization. This repository contains the core scripts developed for this purpose.

## 🧠 Key Features

- Patch extraction from georeferenced UAV orthomosaics
- Manual annotation and dataset construction
- Augmentation pipeline (rotation, flipping, brightness)
- Training pipelines for Random Forest, SVM, and CNNs
- Evaluation tools: classification reports, confusion matrices, confidence plots
- Seasonal vegetation analysis and visualization tools
- Mapping predictions back onto orthophotos using geocoordinates
