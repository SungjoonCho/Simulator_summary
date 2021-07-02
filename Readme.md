# Simulator Summary

### Gazebo

  * [Publishing rgb, depth image with ROS(Using multi realsense camera)](https://github.com/SungjoonCho/gazebo_sim_multicamera)
  
  * [Publishing rgb, depth image with ROS(Using realsense, L515, Azure kinect + Aidbot)](https://github.com/SungjoonCho/gazebo_sim_multicamera_complete)
  
  * [Mesh on Gazebo scene(Using PCD file)](https://github.com/SungjoonCho/mesh_on_gazebo)
  
  * [Creating pointcloud with pcd file](https://github.com/SungjoonCho/Pointcloud_PcdFile-on-Gazebo)
 
### Webots

  * [Publishing rgb, depth image with ROS(Using multi realsense camera)](https://github.com/SungjoonCho/Webots_multiCamera)

### CoppeliaSim

  * [Creating mesh shape in CoppeliaSim with Depth frame from realsense in online](https://github.com/SungjoonCho/CoppeliaSim_DepthFrame)
  
  * [Creating pointcloud in CoppeliaSim with Depth frame from realsense in online](https://github.com/SungjoonCho/CoppeliaSim_DepthFrame)
  
  * [Controlling pose with ROS](https://github.com/SungjoonCho/CoppeliaSim_poseControl)
  
 
 ### Result of experiment with Robotics simulator

|  | Gazebo | CoppeliaSim | Webots | 
| :----: | :----: | :----: | :----: | 
| Multi sensor with ROS | O | O | O | 
| Pose control with ROS | O | O | △| 
| Creating mesh, PC with ROS & realsense depth frame | X | O | X | 


### Comparison Summary for Robotics simulator

|  | Gazebo | CoppeliaSim | Webots | 
| :----: | :----: | :----: | :----: | 
| Components (ex. chair, table) | Many | Many | Many | 
| Plugin language | C++ | Lua, C | C++ | 
| Tutorial, API | Good, Many | Not diverse, Many | Not diverse, Many | 
| CMakeLists or building plugin script | Need | Do not need to build each time | | 
