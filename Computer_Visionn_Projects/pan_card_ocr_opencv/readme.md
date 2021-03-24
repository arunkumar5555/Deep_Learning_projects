## Pan card information extraction

## Requirements

### pytessaract  !pip install pytessaract
### pytessaract_ocr  !pip install pytessaract_ocr
### ftfy  !pip install ftfy
### numpy, scipy , opencv

## Steps

### 1. import required libraries

####  import os
#### import ftfy
#### import pytesseract
#### import re
#### import math
#### from scipy import ndimage
#### import cv2
#### import numpy as np

### 2. write a function for extract text from pan image

####  mention the input
####  convert input image to gray
####  do a canny edge detection
####  find the angle of the image
####  rotate the image depends upon the given image
####  use tesseract to extract text
####  use ftfy to correct the text
####  declare a regular expression for pan number and date of birth finally group them individually
#### print the output
