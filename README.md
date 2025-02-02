# Pokemon DCGAN

A Deep Convolutional Generative Adversarial Network (DCGAN) implemented from scratch in Python within a Jupyter Notebook to generate Pokémon-like images. This project demonstrates the use of GANs for image synthesis.

---

# Overview

This project implements a DCGAN from scratch within a Jupyter Notebook. The primary goal is to explore generative modeling techniques by synthesizing images from the popular Pokémon franchise. The notebook includes code to load and process a dataset of over 10,000 Pokémon images.

---

## Features

- **From-Scratch Implementation:** Learn and experiment with GANs without relying on high-level libraries.
- **Custom Data Loader:** Unpacks the dataset and uses only front-facing images.
- **DCGAN Architecture:** Implements both the generator and discriminator networks using convolutional layers.
- **Complete Notebook:** All code, training loops, and visualizations are contained in one Jupyter Notebook.

---

## Dataset Details

- **Source:** [Dataset](https://www.kaggle.com/datasets/yehongjiang/pokemon-sprites-images?resource=download)
- **Training:** Only the front facing images of the Pokémon are loaded and used during training.
- **Batch Size:** A batch size of 32 is employed, resulting in approximately 255 iterations per epoch.
- **Customization:** You can modify the data loading cell in the notebook to adjust parameters or use a different dataset if desired.

---

## Sources

- Dataset: https://www.kaggle.com/datasets/yehongjiang/pokemon-sprites-images?resource=download
- Guide used to build project: https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html

---
