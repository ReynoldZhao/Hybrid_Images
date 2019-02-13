# Hybrid Images

## Introduction

**Hybrid images** are static images that change in interpretation as a function of the viewing distance. The basic idea is that high frequency tends to dominate perception when it is available, but, at a distance, only the low frequency (smooth) part of the signal can be seen. By blending the high frequency portion of one image with the low-frequency portion of another, you get a hybrid image that leads to different interpretations at different distances.

## Features

* Write an image filtering function and use it to create **hybrid images**
* Using different kind of filters (e.g., Gaussian Blur kernel)
* Get high-pass features and low-pass features of different images and hybrid them into one image

## Structure

| Name          | Function                                                 |
| ------------- | -------------------------------------------------------- |
| resources/    | available images to hybrid                               |
| src/gui.py    | hybrid gui for python2.7                                 |
| src/gui3.py   | hybrid gui for python3.5                                 |
| src/hybrid.py | hybrid program with multiple hybrid algorithms functions |
| src/test.py   | test functions in hybrid.py                              |
| pyuiutils     | support files                                            |

## Usages

### Requirements

* Linux / Windows / MacOS
* python 2.7 / python 3.5
* cv2
* numpy
* pandas

### Compilation

``` python
cd python test.py
cd python gui.py
```

## Examples

### Images before hybriding

![](C:\Users\57844\Desktop\CV作业\实验原文件\实验1\Exp1_Hybrid_Images\resources\cat.jpg)

![](C:\Users\57844\Desktop\CV作业\实验原文件\实验1\Exp1_Hybrid_Images\resources\dog.jpg)

### Hybrid images

![](C:\Users\57844\Desktop\CV作业\实验原文件\实验1\Exp1_Hybrid_Images\resources\hybrid.png)