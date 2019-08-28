QtKittiVisualizer
=================

Description
-----------

The **QtKittiVisualizer** allows viewing the 3D point clouds and bounding boxes of the [raw KITTI data sets](http://www.cvlibs.net/datasets/kitti/raw_data.php).  It is a tool based on *Qt*, the *PCL* and the *VTK*.

It includes the *C++* part of the [raw data development kit](http://kitti.is.tue.mpg.de/kitti/devkit_raw_data.zip) provided on the [official KITTI website](http://www.cvlibs.net/datasets/kitti/).

Build
-----------
Install requirements:
`sudo apt install libvtk`

`sudo apt install libpcl1.7` (better if you can install pcl 1.8)

`sudo apt install qt5`

Edit `CMakeLists.txt` look for PCL requirement , change to your available version of pcl. I can't install pcl 1.8.

`$cmake .`

`$make .`



License
-------

The new parts of the software are licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
