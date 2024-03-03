# INT20H-2024-

# Algorithm development image segmentation
Data Mayhem solution's

### Summary
This repository contains a project on image detection and semantic segmentation using IMDB-WIKI dataset.


- **Task:** Object Detection, Image Segmentation, Averaging Images<br>
- **Data:** <a href='https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/'>Link</a> <br>
- **Link** <a href='https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/'>Link</a> <br>
- **Neural Network:** InceptionResNetV2
- **Scoring function:** Silhouette Score, Calinski-Harabasz Index and Davies-Bouldin Index

### How to run:
We have  two main files: face-detection.ipynb in order to deterction faces on images and cropping them to folder;
face-segmentation.ipynb in order to create image embeddings for each image clusterized them and averaging with VAE;  

All necessary files, models weights automatically loaded in face-segmentation.ipynb file. We have two files for image segmentation and image averaging model and directory with all cropped faces.
.
