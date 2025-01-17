
# Reference Apps for Video Analytics using TensorRT 5 and DeepStream SDK 3.0 #

This repository contains the reference applications for video analytics tasks using TensorRT and DeepStream SDK 3.0.
### Note that this repo only works for DeepStream 3.0. ###

  ![DS3 Workflow](.DS3-workflow.png)

## Getting Started ##
We currently provide four different reference applications:

For further details, please see each project's README.

### CaffeMNIST : [README](CaffeMNIST/README.md) ###

### Yolo : Yolo has been removed since Yolo is natively supported from Deepstream 4.0

### Anomaly Detection : [README](anomaly/README.md) ###
  The project contains auxiliary plug-ins to show the capability of Deepstream SDK in anomaly detection.
  ![sample output](.opticalflow.png)

### SENet : [README](senet/README.md) ###
  SENet is used to demonstrates secondary inference on detected objects.<br/>
  The sample output from Deepstream senet application is shown below.<br/>
   ![sample output](.sample_senet.png)
