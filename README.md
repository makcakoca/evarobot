# evarobot

**Installing evarobot gazebo model** <br />

$ cd ~/catkin_ws/src <br />
$ git clone https://github.com/tu-darmstadt-ros-pkg/hector_gazebo.git -b indigo-devel <br />
$ git clone https://github.com/makcakoca/evarobot/tree/master/evarobot_description <br />
$ git clone https://github.com/makcakoca/evarobot/tree/master/im_msgs <br />
$ cd ~/catkin_ws <br />
$ catkin_make <br />

**Running the gazebo model** <br />
*$ roslaunch evarobot_description evarobot.launch <br />
 
**To work with rosbridge, you need rosbridge packet.** <br />
*$ sudo apt-get install ros-indigo-rosbridge-server <br />
