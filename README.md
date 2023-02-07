# Diagnosing-the-Lumbar-Deformity-using-Machine-Learning-Models

The lumbar spine plays a very important role in our load transfer and mobility. Vertebrae
localization and segmentation are useful in detecting spinal deformities and fractures. Understanding
of automated medical imagery is of main importance to help doctors in handling the time-consuming
manual or semi-manual diagnosis. This project presents the methods that will help clinicians to grade
the severity of the disease with confidence, as the current manual diagnosis by different doctors has
dissimilarity and variations in the analysis of diseases. The lumber
spine is localized using YOLOv5 which is the fifth variant of the YOLO family. It is the fastest and the
lightest object detector. Mean average precision (mAP) of 0.975 is achieved by YOLOv5. To diagnose
the lumbar lordosis, we correlated the angles with region area that is computed from the YOLOv5
centroids and obtained 74.5% accuracy. Cropped images from YOLOv5 bounding boxes are passed
through HED U-Net, which is a combination of segmentation and edge detection frameworks, to
obtain the segmented vertebrae and its edges. Lumbar lordortic angles (LLAs) and lumbosacral
angles (LSAs) are found after detecting the corners of vertebrae using a Harris corner detector with
very small mean errors of 0.29° and 0.38°, respectively.


Kindly email at malaikamushtaq00@gmail.com if you need mid sagittal MRI images with yolo annotations.

Paper Link: https://www.mdpi.com/1424-8220/22/4/1547
