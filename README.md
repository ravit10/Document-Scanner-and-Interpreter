# Document-Scanner-and-Interpreter
A computer vision application that implements Optical Mark Recognition (OMR) by capturing human-marked documents and automatically analyzing the results using image processing techniques.

## Input Image
The input image is a bubble sheet with 5 questions with each question having 5 options (A, B, C, D, E) of which only 1 is the correct answer. A pencil is used to mark the “bubble” that corresponds to the correct answer.

## Computer Vision Techniques involved:
- Edge Detection
- Contour Outline
- Perspective Transform
- Thresholding

## Applications:
This application can be used to scan different type of documents, like Exam grading sheets, Grocery Shopping Receipts, Notes, interpret them as required and save them in a desirable file format like PDF, JPG, PNG, etc.

## Code Requirements:
The example code is in Python (version 2.7 or higher will work).

## Dependencies:
- import numpy
- import cv2
- import immutils
