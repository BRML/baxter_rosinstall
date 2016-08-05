# Baxter rosinstall files
This repository holds rosinstall files for conveniently installing the BRML data acquisition (baxter_daq.rosinstall) and pick and place (baxter_pnp.rosinstall) frameworks for the Baxter research robot.
These files can be used with wstool to install the mentioned frameworks.

## Description of installed ROS packages:

- **baxter_data_acquisition**: the core package of the data acquisition framework. Implements experiments and data recording.
- **baxter_pick_and_place**: the core package of the pick-and-place framework. Implements a pick-and-place demonstration.
- **depth_sensors**: depth sensor models for Gazebo.
- **baxter_tools**: tools required for controlling Baxter.
- **baxter_interface**: customized version of the Baxter SDK.
- **baxter_common**: customized version of the Baxter description.
- **baxter_simulator**: the Baxter simulated in Gazebo.
- **baxter_pykdl**: kinematics and dynamics of the Baxter research robot
- **iai_kinect2**: connecting the Kinect v2 to ROS
