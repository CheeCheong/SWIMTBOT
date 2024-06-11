# SWIMTBOT

A brief description of what this project does and who it's for.

## Table of Contents

- [Package Name](#package-name)
- [Steps to Launch the File](#steps-to-launch-the-file)
- [Contact](#contact)

## Package Name

pongbot_description

## Steps to Launch the File

Follow these steps to set up and launch the pongbot_description package:

1. Create the necessary directory:
    ```bash
    mkdir -p ~/ros2_swimtbot/src
    ```

2. Navigate to the directory:
    ```bash
    cd ~/ros2_swimtbot/src
    ```

3. Clone the repository:
    ```bash
    git clone https://github.com/CheeCheong/swimTbot.git
    ```

4. Build the package:
    ```bash
    colcon build
    ```

5. Source the setup script:
    ```bash
    source ~/ros2_swimtbot/install/setup.bash
    ```

6. Launch the display:
    ```bash
    ros2 launch pongbot_description display.launch
    ```

7. Launch RViz with Gazebo:
    ```bash
    ros2 launch pongbot_description rviz.gazebo.launch.py
    ```

8. Launch RViz with Gazebo and a specific world:
    ```bash
    ros2 launch pongbot_description rviz.gazebo.launch.py world:=./src/pongbot_description/worlds/obstacles.world
    ```

9. Run the teleop twist keyboard:
    ```bash
    ros2 run teleop_twist_keyboard teleop_twist_keyboard
    ```

## Contact

Chee Cheong - [wongcc239@gmail.com](mailto:your-email@example.com)

Project Link: [https://github.com/CheeCheong/swimTbot](https://github.com/CheeCheong/swimTbot)
