# YouTubeVIS data loading and evaluation
## Introduction

This package provides data loading and evaluation functionalities for video instance segmentation on [YouTubeVIS](https://youtube-vos.org/dataset/vis/). It is built based on [COCO API](https://github.com/cocodataset/cocoapi) designed for the MSCOCO dataset (http://cocodataset.org/). For evaluation metrics, please refer to the [descriptions](https://youtube-vos.org/dataset/vis/) for details.
We have only implemented Python API for YouTubeVIS. API in other languages are not available for now.

## Installation
To install:
```
cd PythonAPI
# To compile and install locally 
python setup.py build_ext --inplace
# To install library to Python site-packages 
python setup.py build_ext install
```

# Cython needs to be installed before pycocotools
pip install cython
pip install opencv-python pillow matplotlib
pip install git+https://github.com/haotian-liu/cocoapi.git#"egg=pycocotools&subdirectory=PythonAPI"
pip install GitPython termcolor tensorboard

## Contact
If you have any questions regarding the repo, please create an issue.
