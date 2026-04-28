# White Blood Cell Classification

This repository presents my solution to the Kaggle Challenge on [White Blood Cell Classification](https://www.kaggle.com/competitions/ima205-challenge-2026), which aims to classify 13 types of white blood cells from microscopic images of blood smears. The dataset contains 28,901 training images with an extreme class imbalance (1183:1 ratio between the most and least frequent classes).

My approach progresses from classical machine learning (89 handcrafted features, dual cell/nucleus segmentation, SMOTE, GradientBoosting) to deep learning (ConvNeXt-Tiny, Focal Loss, MixUp/CutMix, backbone freezing, Test Time Augmentation), achieving a final macro F1 score of **0.77** on the private leaderboard. I managed to rank 20th out of more than 70 students of Télécom Paris for this challenge which was given during a course.

You can find the **[ML notebook](https://github.com/theoplg/White-Blood-Cell-Classification/blob/main/main_ML.ipynb)** and **[deep learning notebook](https://github.com/theoplg/White-Blood-Cell-Classification/blob/main/main_DL.ipynb)** presenting the full process, as well as a **[report](https://github.com/theoplg/White-Blood-Cell-Classification/blob/main/WCB_report.pdf)** providing a detailed description of the methodology and results.
