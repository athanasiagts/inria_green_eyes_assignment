# Image parsing
The file raw_images.bin contains one or more images in RAW 8bit Bayer format recorded
with an OpenMV cam M7 (it’s an Open Source camera) at a resolution of 640x480px.
The image_writer.py script was written in May of 2020 to record these images.
Write a program to read the raw images, transform them into RGB and write them to disk
using as lossless-compressed image file. Your program should be able to handle binary files
that exceed the size of RAM.
Expected results: source code, executable or equivalent with instructions how to use it.
# Image processing
Propose an algorithm to transform the salads.png image into a binary mask showing the
location of salad pixels (vs. background/soil pixels).
Transform the image (original or mask) such that the salad rows appear parallel. You don’t
have to do the transformation on the whole image, and may transform a portion of it.
# Data generation
Write a program that can create a dataset of 1000 synthetic images composed of a textured
background and between 0 and 4 instances of an object. The background base texture is
given in background.png. The object.png should be blended with background at random
positions and at random angles.
Write an COCO-style annotations for object detection for the generated dataset (only id and
bbox attributes are mandatory).
Expected results: code or description of your generation procedure, annotation file.
# Machine Learning
The file yolo_training.png shows the results of training a Yolo v4 on thermal images. The
mAP is very high on validation data set, but the results on the test set and on real data
(same domain, but not present in the dataset) are disappointing and do not match the mAP
at all.
What could cause such results?
