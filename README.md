# ultralytics4channel
Ultralytics 8.2.5 modified to train and predict for 4-channel (RGBD) images.

In this repository I modified the source code of ULtralytics to allow training and prediction for 4-channel images.
Main modifications are:

- changing cv2.imread() functions to include cv2.IMREAD_UNCHANGED
- change how the mosaic is generated for logging (plotting)
- change every variable for channel number from 3 to 4.

Step of my modifications can be found in this document:
[My steps to modify YOLO to YOLO with 4 channels.pdf](https://github.com/g-h-anna/ultralytics4channel/files/15223626/My.steps.to.modify.YOLO.to.YOLO.with.4.channels.pdf)
