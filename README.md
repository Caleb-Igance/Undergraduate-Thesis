# Undergraduate Thesis: Text Recognition Using Fourier Transform as a Metric.

This project was undertaken as a senior undergraduate honors thesis at East Tennessee State Univserity between August 2016 and May 2017. My thesis advisor was Dr. Jeff Knisley.

The file Thesis.ipynb is a Jupyter Notebook. The code in that file imports a data set of 62 character classes of images, 1067 images each, for a total of 62 X 1067 = 66154 images. The images are in gray-scale: moveover, they contain the character in black and white space everywhere else. 

The code does the following steps:
  1) find the contours in the images;
  2) takes the contour of largest area in each image to be the only information describing each image;
  3) calculate the Fourier transform of each contour;
  4) create a kNN classifier on the Fourier transforms.
