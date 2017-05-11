# rviz_plugin_skeleton
A minimal skeleton code for adding tools to RViz. Based on the PlantFlagTool example.

## To build

Add this directory to your src/ directory of a ROS workspace. Execute catkin_make in the main directory of that workspace to build.

## To test

- First, launch Rviz.
- Click the + button on the toolbar, and select rviz_plugin_skeleton/PlantFlag
- You should be able to add flags to your map

## To modify

- Download or fork this repository into your ROS workspace's src/ directory
- Perform a Find and Replace all operation with your favorite text editor, replace "rviz_plugin_skeleton" with the desired package name
- Change the tool name, icon, code, etc...