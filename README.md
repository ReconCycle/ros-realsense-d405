# Docker ROS Realsense d405

This code is almost the same as for [ros-realsense](https://github.com/reconcycle/ros-realsense).

The difference is that we use https://github.com/rjwb1/realsense-ros instead of https://github.com/IntelRealSense/realsense-ros/tree/ros1-legacy

The reason is that ros1-legacy branch does not support the d405.

See here for the relevant issue: https://github.com/IntelRealSense/realsense-ros/issues/2737

I now try with the latest version of `ros1-legacy`, by creating my own fork with the appropriate fix: https://github.com/sebastian-ruiz/realsense-ros.git


## It might be required to match the firmware version that the camera runs on:

Matching this version 2.51.1 with the firmware, according to [this table](https://dev.intelrealsense.com/docs/firmware-releases) we apply firmware `Signed_Image_UVC_5_13_0_55.bin` to the camera.
