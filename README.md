# hesai_description
URDF Model of hesai lidar products

The meshes was obtained from the original CAD provided by HESAI (step file).

This repository is not associated to or maintained by HESAI.

Launch using the following. Reads Xacro and visualises Hesai mesh in Rviz

ros2 launch hesai_description  display.launch.py model:=urdf/hesai_xt32_standalone.urdf.xacro

ros2 launch hesai_description  display.launch.py model:=urdf/hesai_qt64_standalone.urdf.xacro
