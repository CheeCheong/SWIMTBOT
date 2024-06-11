mkdir -p ~/ros2_swimtbot/src
cd ros2_swimtbot
colcon build
source ~/ros2_swimtbot/install/setup.bash
ros2 launch pongbot_description display.launch
ros2 launch pongbot_description rviz.gazebo.launch.py
ros2 launch pongbot_description rviz.gazebo.launch.py world:=./src/pongbot_description/worlds/obstacles.world
ros2 run teleop_twist_keyboard teleop_twist_keyboard
