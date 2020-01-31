# Use the OpenCV to Compute the Intersection area and Union area

[![](https://img.shields.io/badge/Language-Python-blue)](https://github.com/chiehpower/cv2_intersection_union)  [![](https://img.shields.io/badge/Library-OpenCV-lightgrey)](https://github.com/chiehpower/cv2_intersection_union/blob/master/Get%20the%20intersection%20area%20and%20union%20area%20between%20two%20irregular%20shapes.ipynb) 

Goal: Get the intersection area and union area between two irregular shapes.

## Introduction

We could find many articles which were talking about how to deal with the intersection and union area for bounding boxes. That's quite easier than irregular shapes because we can clearly know where crossover points are. However, if there are two irregular shapes and we wanna compute the intersection area, it is hard to find the inside area for using simple intuitive mathematics method. So we should use another method to calculate the area for intersection and union. 

First of all, we know the cv2 which provided a very convenient tool, `cv2.contourArea`. It can compute the area of contour. So we just need to find the contour, and then we can compute the area easily.

Second, in order to calculating the contour, we need to let the image be a **grayscale image**. Therefore, we will use the tool of cv2, `cv2.threshold`. 

Eventually, after we get the grayscale image, we can find the contour by `cv2.findContours`. 

## Projects

- Deal with the images, and then compute the are value of intersection and union - [Link](https://github.com/chiehpower/cv2_intersection_union/blob/master/Get%20the%20intersection%20area%20and%20union%20area%20between%20two%20irregular%20shapes.ipynb)

- Deal with the 2D coordinates (x,y), and then compute the are value of intersection and union - [Link]() 

