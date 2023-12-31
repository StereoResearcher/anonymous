# SAMTormer: SAM-Tuning Transformer for Stereo Matching
This repository will contain the source code for our paper. Our code will be made public when the manuscript is accepted.

## Requirements
The code has been tested with  PyTorch 1.12.0 and Cuda 11.3

## Required Data
To evaluate/train SAMTormer, you will need to download the required datasets. 
* [Sceneflow](https://lmb.informatik.uni-freiburg.de/resources/datasets/SceneFlowDatasets.en.html#:~:text=on%20Academic%20Torrents-,FlyingThings3D,-Driving) (Includes FlyingThings3D, Driving & Monkaa)
* [Middlebury](https://vision.middlebury.edu/stereo/data/)


By default `stereo_datasets.py` will search for the datasets in these locations. You can create symbolic links to wherever the datasets were downloaded in the `datasets` folder

```Shell
├── datasets
    ├── SceneFlow
        ├── FlyingThings3D
            ├── frames_cleanpass
            ├── frames_finalpass
            ├── disparity
        ├── Monkaa
            ├── frames_cleanpass
            ├── frames_finalpass
            ├── disparity
        ├── Driving
            ├── frames_cleanpass
            ├── frames_finalpass
            ├── disparity
    ├── Middlebury
        ├── MiddEval3
        ├── 2014
```
