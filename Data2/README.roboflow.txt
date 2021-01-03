
Chess - v1 2021-01-03 8:05pm
==============================

This dataset was exported via roboflow.ai on January 3, 2021 at 1:07 PM GMT

It includes 48 images.
Chess are annotated in COCO format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 0 and 7 percent of the image
* Random Gaussian blur of between 0 and 1 pixels
* Salt and pepper noise was applied to 2 percent of pixels


