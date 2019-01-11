# Visual-Tactile_Dataset
A novel visual-tactile dataset for robotic manipulation
***********************************************************
* Name:       Visual Tactile dataset built by Intel's Eagle Shoal robot hand
* Author:     Tsinghua University and Intel Labs China
* Date:       2018/08/14
* License:    Community Data License Agreement – Permissive – Version 1.0
* Paper:       Wang, T., Yang, C., Kirchner, F., Du, P., Sun, F., & Fang, B. (2019). Multimodal grasp data set: A novel visual–tactile data set for robotic manipulation. International Journal of Advanced Robotic Systems. https://doi.org/10.1177/1729881418821571
***********************************************************
There are three file types in the Eagle Shoal Dataset. They
are .txt, .jpg and .mp4, respectively.

It is recommanded to use numpy function loadtxt to load the
.txt files, opencv function imread to load .jpg files, and
opencv function VideoCapture to open .mp4 files. Here is an
example.

import numpy as np
import cv2

data = np.loadtxt("<Path-to-txt-file>")

# For opencv3
img = cv2.imread("<Path-to-jpg-file>", cv2.IMREAD_COLOR)

video = cv2.VideoCapture("<Path-to-jpg-file>")
