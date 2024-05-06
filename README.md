# ultralytics4channel
Ultralytics 8.2.5 modified to train and predict for 4-channel (RGBD) images.

In this repository I modified the source code of ULtralytics to allow training and prediction for 4-channel images.
Main modifications are:

- changing cv2.imread() functions to include cv2.IMREAD_UNCHANGED
- change how the mosaic is generated for logging (plotting)
- change every variable for channel number from 3 to 4.

A more detailed description can be found in this document:

[My steps to modify YOLO to YOLO with 4 channels.pdf](https://github.com/g-h-anna/ultralytics4channel/files/15223626/My.steps.to.modify.YOLO.to.YOLO.with.4.channels.pdf)

![image](https://github.com/g-h-anna/ultralytics4channel/assets/74008708/89e97ce1-ef8b-4e1b-a647-7444f3d98533)
