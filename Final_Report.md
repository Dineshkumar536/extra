<center><a href="https://winterofcode.com/"><img src="https://camo.githubusercontent.com/c73f77959233a8adb69f3dee7bbb3ba5e016f4239c7496c82538cc60c984f56e/68747470733a2f2f77696e7465726f66636f64652e636f6d2f7374617469632f6d656469612f6f72672d6c6f676f2e39333564376634382e706e67" alt="gsoc" height="50"/></a>
<a href="https://www.python.org/">![](/images/header.jpg) height="45"/></a>
<a href="https://fury.gl/latest/community.html"><img src="https://raw.githubusercontent.com/divyake/Cysec-Hacktoberfest/dcc84465cfcff73981f8fcb5c8fe3b1710c007e1/assets/logo.svg" alt="DSC-IEM" height="45"/></a>
</center>

# Winter of Code Final Work Product
* **Name:** Abhinav Chauhan
* **Organisation:** DSC - NSEC
* **Project:** [DocScanner](https://github.com/dscnsec/DocScanner.git)

## Reading image using OpenCV
* images
![](/images/1.jpg)

## Image Preprocessing
* Converting orginal image to grey color
* Converting grey image to blurred image using Gaussian Blur
* Detecting edges using canny edge detector
* dilation and erosion of inage for better contour detection.
* images
![](/images/Threshold.jpg)

## Contour Detection
* He we handle all the contour Detected and keep only the one with the greatest contour area.
* After getting that contour we draw a bounding box around it for visualisation and keep the coordinates of the corners of the required contour detected.
* images 
![](/images/Conttour.jpg)

## Wrapping the Image
* In this step we wrap the image with the ordered points i.e. (0,0) (width, 0) (0, height) and (width, height) which we got from the reorder function.

## Result Image
* Here we diplay the the final scanned image.
* images
![](/images/Scanned.jpg)