# Image Processing Projects Repository

These Jupyter notebooks contain practical assignments (TP1 and TP2) from the "Processamento de Imagem e Visão" course at Instituto Superior de Engenharia de Lisboa (ISEL), for the Licenciatura em Engenharia Informática e Multimédia. 
## TP1: Coin Detection and Analysis
TP1 focuses on image processing techniques for grayscale conversion, histogram analysis, and component selection (RGB) to optimize coin detection on a table surface.

- Extracts RGB channels and analyzes histograms to select the red channel for best contrast.
- Prepares images for binarization by identifying optimal thresholds via mean pixel values.

Implemented in Python using OpenCV and Matplotlib for visualization. 

## TP2: Motion Detection
TP2 develops a computer vision algorithm for detecting, classifying, and tracking moving objects (cars, people, others) in video footage.

- Background estimation using temporal median filtering (every 300 frames).
- Active pixel detection via absolute difference and thresholding.
- Morphological operations (closing, erosion, dilation) for noise reduction.
- Region extraction with contour finding, feature computation (area, aspect ratio, vertical position, color histogram), and classification based on thresholds.
- Outputs annotated video with bounding boxes and labels.

Uses OpenCV for video processing and real-time visualization. 

## Technologies
- Python 3 with OpenCV (cv2), NumPy, Matplotlib.
- Jupyter Notebook for development and documentation. 

## Authors
- André Silva (A45885)
- Pedro Azevedo (A47094)
