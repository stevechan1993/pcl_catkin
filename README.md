# pcl_catkin
Catkinized version of the latest version (1.9.1) of the Point Cloud Library (PCL) (http://pointclouds.org/).

To get (and build) the ROS packages that depend on PCL you should also use

```
git submodule update --init --recursive
```

such that you have them matching this PCL version.

## Install dependency
```
This package has three dependecies: Eigen, libbullet-dev and catkin_simple
Eigen need build from source code
catkin_simple should put into catkin_ws/src
sudo apt install libbullet-dev

```
