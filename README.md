# waifu2x-bash

This is a command line background manager for personal use. It adjusts the background image to proper size, rename and rearrange files. Many parameters in the scripts are hardcoded so you may need to change these values accrodingly.

**WARNING: The Python Waifu2x code used here is not yet optimized. Tread with caution.**

Based on [waifu2x by nagadomi](https://github.com/nagadomi/waifu2x).

## Dependencies

* Python 2.7
* numpy
* scipy
* PIL (or Pillow)
* PyOpenCL

And an OpenCL implementation.

## Usage

    $ python2 cl-waifu2x.py miku_small.png miku_small_cl.png models/scale2.0x_model.json
    Choose platform:
    [0] <pyopencl.Platform 'Intel(R) OpenCL' at 0x7fa4d7f10110>
    [1] <pyopencl.Platform 'NVIDIA CUDA' at 0x7fa4d8026f80>
    Choice [0]:
    Set the environment variable PYOPENCL_CTX='' to avoid being asked again.
    100.0%...Done
    29004 pixels/sec
    925359122 ops/sec
    
Before 

## Performance

This script is for Mac so there is no much difference 
