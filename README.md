# ultralytics4channel
Ultralytics 8.2.5 modified to train and predict for 4-channel (RGBD) images.

In this repository I modified the source code of ULtralytics to allow training and prediction for 4-channel images.
Main modifications are:

- changing cv2.imread() functions to include cv2.IMREAD_UNCHANGED
- change how the mosaic is generated for logging (plotting)
- change every variable for channel number from 3 to 4.

You find the steps in the pdf  file.

If you use my modifications, please cite this repository.

```
@misc{GHA-ultralytics4ch,
  author = {Anna Gelencsér-Horváth},
  title = {Modify Ultralytics 8.2.5 to accept 4-channel images for training and prediction},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/g-h-anna/ultralytics4channel}},
}
```

contact:
```
gha@itk.ppke.hu
```
