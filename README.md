# JetsonNanoUbuntu20_Disk with Ultralytics libraries installed
32 GB SD card image for Jetson Nano based on Ubuntu 20 and compatible Yolov8 Ultralytics library
The image was developed for my practical session classes nad projects on AI and embedded systems at ![image](https://github.com/edicek/JetsonNanoUbuntu20_Disk/assets/45590306/66593064-9ddc-4a5c-90bd-d008f52b9c35)


This disk image is based on the initial Qengineering Ubuntu 20.04 SD card image (https://qengineering.eu/install-ubuntu-20.04-on-jetson-nano.html; https://github.com/Qengineering/Jetson-Nano-Ubuntu-20-image; distributed under BSD 3 license).

![image](https://github.com/edicek/JetsonNanoUbuntu20_Disk/assets/45590306/c389048c-1d83-469a-b9fa-5ed463f236b6)

Compressed (~11GB) image file is available here: https://shorturl.at/bpyD3

Basic features :
- Ultralytics libraries  (YoloV8 8.124) installed
- Compatibility with TensorRT preserved
- Disk space optimized
- RAM utilization after boot optimized (running processes reduced, no printing service, scanner, etc...)

Remark: warning on the compatibility of the Numpy package due to the Ultralytics requirements and TensorFlow compatibility
