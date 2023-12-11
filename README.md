# WHITE BOX METHOD TO CLASSIFY THE HEALTH STATUS OF ENDOMETRIAL-TISSUE

### Overview
This project focuses on diagnosing endometrial cancer through Whole Slide Images (WSI) of H&E stained tissue samples. An innovative "whitebox" technique was proposed, achieving an impressive 80% accuracy on tissue diagnosis within the selected scope of WSI.

### Key Features
- Review of Historical Techniques: Explored color normalization, texture descriptors, and segmentation methods.
- Autoencoder for Low-Dimensional Representation: Implemented a Tensorflow-based Autoencoder for capturing low-dimensional representations, addressing staining protocol variations.

### Feature Extraction and Classification:

- Extracted morphological and color features based on a pathologist's protocol.
- Utilized Logistic Regression for classification, emphasizing the features' significance in the diagnosis.
- Medical Image Analysis Pipeline:
       * Pre-processed WSI with resizing and color correction.
       * Deployed the model on Paperspace using Tensor cores and Keras API.
