# JetsonNano
Various projects for my Jetson Nano

---

# Hello AI World
NOTE: for all apps you will typically want to:
1. cd ~/Documents/jetson-inference
2. open the container via **docker/run.sh**
3. most examples are executed from the containers **build/aarch64/bin** folder

| Example    | Container Directory | Notes |
| :-------- | :------- | :------- |
| imagenet  | jetson-inference/build/aarch64/bin | ./imagenet.py images/orange_0.jpg images/test/output_0.jpg <br> ./imagenet.py images/cat_2.jpg <br> ./imagenet.py /dev/video0|
| detectnet | jetson-inference/build/aarch64/bin | ./detectnet.py --network=ssd-mobilenet-v2 images/peds_0.jpg images/test/output.jpg <br> ./detectnet.py "images/peds_*.jpg" images/test/peds_output_%i.jpg <br> ./detectnet.py /dev/video0 <br> ./detectnet.py /dev/video0 output.mp4      **# save to video file**    |
| posenet    | jetson-inference/build/aarch64/bin | ./posenet.py /dev/video0    |

## Hello AI World - Coding Your Own

mount that baby

# Acronymns

**COCO**
: Common Objects in Context

The COCO (Common Objects in Context) dataset is a large-scale dataset for object detection, segmentation, and captioning. It was first released in 2014 and has become a popular benchmark for machine learning algorithms in the field of computer vision.

DLN
: Deep Learning Networks 

ONNX
: Open Neural Network Exchange

Pascal VOC
: Vision Object Class

SSD
: Single Shot Detection


