# ComicConvert
# Cartoonify

Cartoonify is a Python script that converts images into cartoon-like representations using computer vision techniques.

## Features

- **Bilateral Filtering**: Applies bilateral filtering to smooth the image while preserving edges.
- **Edge Detection**: Detects edges in the smoothed image using the Canny edge detection algorithm.
- **Histogram Calculation**: Calculates histograms for each color channel of the image.
- **K-Means Clustering**: Performs K-means clustering on the histograms to determine color centroids.
- **Color Quantization**: Assigns each pixel to the nearest color centroid based on K-means clustering.
- **Contour Detection**: Detects contours in the edge-detected image using OpenCV.
- **Contour Drawing**: Draws contours on the output image.
- **Erosion**: Applies erosion to enhance the cartoon effect.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- SciPy

### Original Image
![Original Image](https://github.com/Raghavdargan/ComicConvert/raw/main/original2.jpg)


### Cartoonified Image:
![Cartoonified Image](https://github.com/Raghavdargan/ComicConvert/raw/main/cartoon.jpg)


