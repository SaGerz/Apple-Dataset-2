
Apple-detector-New - v2 2023-10-25 2:15pm
==============================

This dataset was exported via roboflow.com on October 25, 2023 at 7:26 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 2251 images.
Apple are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Fit (black edges))

The following augmentation was applied to create 2 versions of each source image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 15 and 55 percent of the image
* Random exposure adjustment of between -25 and +25 percent
* Salt and pepper noise was applied to 5 percent of pixels


