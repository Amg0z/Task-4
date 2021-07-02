# Task-4
fist add this command
sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation

then I bulit the map and robort by this command 
cd ~/catkin_ws/src
    git clone https://github.com/wh200720041/warehouse_navigation.git
    cd ..
    catkin_make
    source ~/catkin_ws/devel/setup.bash
    then I run it by this command
        roslaunch warehouse_simulation warehouse_simulation.launch
