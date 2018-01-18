# trina_ros_ws
collection of ROS dependencies as modules for the trina motion software

# Contents
1. ebolabot               : launch files for the ebolabot system
2. baxter         (module): baxter packages
3. dtnamixel_motor(module): RHR fork with the Encoder message
4. hstar_amp      (module): mobile base packages
5. reflex-ros-pkg (module): up-to-date reflex gripper code
6. roboteq        (module): diagnostic tools

* dynamixel_motor is a part of canon ROS repository BUT we are using the RightHandRobotics
fork.
All the packages except ebolabot is using gitmodules for version control. We also moved away from wstools for Baxter packages for consistency.

use `git submodule update` or `sync` to update modules.
  
TODO: reflex-ros-pkg's CMakeLists are outdated and needs to be modified (gencpp is obsoloate?) followed by a merge request.
