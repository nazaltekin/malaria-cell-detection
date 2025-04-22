# Malaria Detection
## Problem Definition
Malaria is a life-threatening disease that affects nearly half of the world's population. Traditional diagnosis involves manual inspection, which is time-consuming, labor-intensive, and prone to human error. An automated, accurate, and scalable system for malaria detection can significantly enhance early diagnosis, improve treatment outcomes, and reduce mortality — especially in regions with limited access to skilled healthcare professionals.
The objectives: What is the intended goal?

The goal is to build an efficient computer vision model using deep learning techniques that can automatically classify red blood cell images as either:
Parasitized (infected with malaria)
Uninfected (healthy or non-malaria-affected) This model should assist in early and reliable detection of malaria, reducing dependency on manual microscopic analysis.

This is a binary image classification problem where the task
Input: An RGB image of a red blood cell (32x32x3)
Output: A class label — either Parasitized or Uninfected
Using labeled image data, we aim to train a Convolutional Neural Network (CNN) that can learn to detect malaria-related patterns in red blood cells, and automatically classify whether or not the cell is infected. This falls under the domain of supervised learning in computer vision, with a focus on healthcare diagnostics.

## Data Description
There are a total of 24,958 train and 2,600 test images (colored) that we have taken from microscopic images. These images are of the following categories:

Parasitized: The parasitized cells contain the Plasmodium parasite which causes malaria
Uninfected: The uninfected cells are free of the Plasmodium parasites
