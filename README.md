# evarobot

**Installing evarobot gazebo model**

$ cd ~/catkin_ws/src
$ git clone https://github.com/tu-darmstadt-ros-pkg/hector_gazebo.git -b indigo-devel
$ git clone https://github.com/makcakoca/evarobot/tree/master/evarobot_description
$ git clone https://github.com/makcakoca/evarobot/tree/master/im_msgs
$ cd ~/catkin_ws
$ catkin_make

**Running the gazebo model**
$ roslaunch evarobot_description evarobot.launch

**To work with rosbridge, you need rosbridge packet.**
$ sudo apt-get install ros-indigo-rosbridge-server
