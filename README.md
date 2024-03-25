# hesai_description
URDF Model of hesai lidar products

The mesh was obtained from the original CAD provided by HESAI.

This repository is not associated to or maintained by HESAI.

Launch using the following. Reads Xacro and visualises Hesai mesh in Rviz

ros2 launch hesai_description  display.launch.py model:=urdf/hesai_standalone.urdf.xacro
