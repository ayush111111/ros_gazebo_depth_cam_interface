# ros_gazebo_depth_cam_interface


Task​ : Simulate a depth cam (​ http://gazebosim.org/tutorials/?tut=ros_depth_camera​ ).
Extract the video feed being published by the depth camera by creating an Image
subscriber, and display the camera feed using OpenCV.


Edited sdf file according to tutorial.

Kinect depth data extracted (/depth/image_raw topic)

cv_bridge converts ROS image to OpenCV processable data


