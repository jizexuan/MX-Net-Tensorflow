# Mirrored X-Net (MX-Net)
This repository contains tensorflow implemenation of the proposed weakly supervised model for geographic atrophy (GA) lesions segmentation:

## Contents
- [Dataset](#Dataset)
- [Requirements](#Requirements)
- [Running](#Running)

## Dataset
We utlize two different GA datasets (Dataset 1 and Dataset 2) and one normal (Dataset 3) dataset to evaluate the model. Each dataset contains SD-OCT cubes with three dimensions. All the cubes contain the advanced non-exudative AMD with GA.
> Our datasets were acquired with a Cirrus OCT device from Stanford University.
### The summarizations of data information on three datasets

|             |   Dataset 1  |   Dataset 2  |   Dataset 3  |
| ----------- | ------------ | ------------ | ------------ |
|     Size    | 512×128×1024 | 200×200×1024 | 512×128×1024 |
|    Cubes    |      51      |      54      |      63      |
| Individuals |      8       |      54      |      38      |
|     Eyes    |      12      |      54      |      62      |


## Requirements
* My running environments, based on Ubuntu 18.04:
    * Python==3.6
    * TensorFlow==1.13.1
    * numpy
    * matplotlib
    * opencv
    * pydensecrf

### * To Do
* [ ] Publish the address of our paper
* [ ] Submit the codes
* [ ] Introduce this work
