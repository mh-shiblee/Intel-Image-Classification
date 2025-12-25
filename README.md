# Intel-Image-Classification
End‑to‑end Intel scene classification with EfficientNet‑B2, custom attention heads, advanced augmentation, and Grad‑CAM explainability

This repository contains my full deep learning pipeline for the Intel Image Classification (scene) dataset. I start from a plain EfficientNet‑B2 baseline and gradually improve the model with stronger data augmentation, architectural tweaks (CBAM attention and multi‑scale features), and finally explain the model’s decisions using Grad‑CAM. The goal is not just to get good accuracy, but to understand why the network predicts each class (buildings, forest, glacier, mountain, sea, street) and what visual patterns it relies on.


## License
Code in this repository is released under the MIT License.  
The Intel Image Classification dataset is provided separately via Kaggle under its own terms.
