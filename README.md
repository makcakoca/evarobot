# evarobot

**Installing evarobot gazebo model** <br />

$ cd ~/catkin_ws/src <br />
$ git clone https://github.com/tu-darmstadt-ros-pkg/hector_gazebo.git -b indigo-devel <br />
$ git clone https://github.com/makcakoca/evarobot <br />
$ git clone https://github.com/ros-simulation/gazebo_ros_pkgs.git -b indigo-devel <br />
$ git clone https://github.com/ros-controls/control_toolbox.git -b indigo-devel <br />
$ git clone https://github.com/ros-controls/realtime_tools.git -b indigo-devel <br />
$ git clone https://github.com/ros-controls/ros_control.git -b indigo-devel <br />
$ cd ~/catkin_ws <br />
$ catkin_make <br />

**Running the gazebo model** <br />
$ roslaunch evarobot_description evarobot.launch <br />
 
**To work with rosbridge, you need rosbridge packet.** <br />
$ sudo apt-get install ros-indigo-rosbridge-server <br />
