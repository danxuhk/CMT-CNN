<<<<<<< HEAD
# Caffe for Faster R-CNN

Caffe fork that supports Fast**er** R-CNN, forked from [BLVC/caffe](https://github.com/BVLC/caffe) on June 27th, 2015.

### Compile for Windows
0.	Download a VS 2013 solution ([Onedrive](https://onedrive.live.com/download?resid=4006CBB8476FF777!17218&authkey=!AOqDbPj7Idd4O4w&ithint=file%2czip), [DropBox](https://www.dropbox.com/s/mqw7b7qqx0dojkb/caffe_library.zip?dl=0), [BaiduYun](http://pan.baidu.com/s/1hqGojnI)) which include some related libraries.
0.	Copy all files in this repo to .\caffe in the solution.
0.	Prepare external libraries of OpenCV/Boost/MKL. Refer to the links below:
 - [OpenCV](http://opencv.org/downloads.html)
 - [Boost with pre-bulit binaries](http://sourceforge.net/projects/boost/files/boost-binaries/)
 - [MKL](https://software.intel.com/en-us/intel-parallel-studio-xe)
0.	Switch the configuration to “Release_Mex” for compiling mex for MATLAB interface.
0.	In the VS solution, modify “Include Directories” and “Library Directories” to point to your external libraries.
0.	Set “Caffe” project as startup project.
0.	Rebuild the entire solution.
0.	Copy all files in .\x64\Release_Mex to faster_rcnn-master\external\caffe\matlab\caffe_faster_rcnn.

### Known issues for Windows:
0.	If not using VS 2013, you need to re-build the solution in .\Library\leveldb. Then copy the built leveldb.lib to .\x64\Release_Mex.
0.	If you are not using OpenCV 2.4.9, copy the corresponding opencv dll files to .\x64\Release_Mex.
=======
# Learning Cross-Modal Deep Representations for Robust Pedestrian Detection
By Dan Xu, Wanli Ouyang, Elisa Ricci, Xiaogang Wang and Nicu Sebe
## Introduction
CMT-CNN is a pedestrian detection approach asscoiated to an arxiv submission https://arxiv.org/abs/1704.02431 which is accepted at CVPR 2017. The code is implemented with Caffe and has been tested under the configurations of Ubuntu 14.04, MATLAB 2015b and CUDA 8.0.
## Cite CMT-CNN
Please consider citing our paper if the code is helpful in your research work:
<pre>@inproceedings{xu2017learning,
  title={Learning Cross-Modal Deep Representations for Robust Pedestrian Detection},
  author={Xu, Dan and Ouyang, Wanli and Ricci, Elisa and Wang, Xiaogang and Sebe, Nicu},
  journal={CVPR},
  year={2017}
}</pre>
## Requirements
>>>>>>> 660c7ede5b5e916f6b2490a4ede4cf647ab60b2a
