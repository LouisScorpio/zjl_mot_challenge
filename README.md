# zjl_mot_challenge
2019 ZHEJIANG LAB CUP GLOBAL AI COMPETITION MOT CHALLENGE BASELINE

## Introduction
This repository contains baseline code for 2019 zhejiang lab cup global AI competition multiple object tracking challenge. We use [yolov3](https://pjreddie.com/darknet/yolo/) to detect persons and [deep SORT](https://github.com/nwojke/deep_sort) algorithm for tracking. Of course you can use other methods based on automatic tracker initialization for MOT challenge. The code is for baseline only.

## Dependencies
The code can be runnning with Python 3.5. The following dependencies are needed:

- NumPy
- sklearn
- OpenCV
- TensorFlow
- keras

## Installation
First, clone the repository:
`git clone https://github.com/nwojke/deep_sort.git`

Then, download pre-trained models from [here](https://drive.google.com/open?id=1UboRIVsQP94J7NssxbcXpgIicEXTxxrH) and put it in '/networks'.

## Running
We assume your videos have been put in '/video':

`python demo.py --videos ['a1.ts']`
