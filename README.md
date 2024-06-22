# SWIMTBOT

This project is part of the Robotic + Lab Course (BHM 3943) supervised by Assoc. Prof. Ts. Dr. Muhammad Aizzat Bin Zakaria at Universiti Malaysia Pahang Al-Sultan Abdullah. The course focuses on the design and implementation of an autonomous robotic system using ROS2.

This project is done and supported by the software:
- Fusion 360
- Ubuntu 22.04
- RViz
- Gazebo

## Table of Contents
- [Package Name](#package-name)
- [Steps to Launch the File](#steps-to-launch-the-file)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Package Name
pongbot_description

## Steps to Launch the File

Follow these steps to set up and launch the pongbot_description package:

1. **Create the necessary directory:**
    ```bash
    mkdir -p ~/ros2_swimtbot/src
    ```
2. **Navigate to the directory:**
    ```bash
    cd ~/ros2_swimtbot/src
    ```
3. **Clone the repository:**
    ```bash
    git clone https://github.com/CheeCheong/swimTbot.git
    ```
4. **Build the package:**
    ```bash
    colcon build
    ```
5. **Source the setup script:**
    ```bash
    source ~/ros2_swimtbot/install/setup.bash
    ```
6. **Launch the display:**
    ```bash
    ros2 launch pongbot_description display.launch
    ```
7. **Launch RViz with Gazebo:**
    ```bash
    ros2 launch pongbot_description rviz.gazebo.launch.py
    ```
8. **Launch RViz with Gazebo and a specific world:**
    ```bash
    ros2 launch pongbot_description rviz.gazebo.launch.py world:=./src/pongbot_description/worlds/obstacles.world
    ```
9. **Run the teleop twist keyboard:**
    ```bash
    ros2 run teleop_twist_keyboard teleop_twist_keyboard
    ```

## Contact
Chee Cheong - wongcc239@gmail.com

Project Link: [https://github.com/CheeCheong/SWIMTBOT](https://github.com/CheeCheong/SWIMTBOT)

## Acknowledgements
- **Team Members:**
  - [Wong Chee Cheong](https://github.com/CheeCheong)
  - [Safwan bin Seruji](https://github.com/ichi-maru)
  - [Mursyied bin Mahazani](https://github.com/MuhamadMursyied)
  - [Muhamad Izzul Sirhan bin Mohd Rizal]()
  - [Tuan Muhamad Talhah bin Tuan Ishak](https://github.com/TMTalhah)

- **Advisor:**
  - [Assoc. Prof. Dr. Muhammad Aizzat Bin Zakaria](https://github.com/aizzat)

- **University:**
  - Universiti Malaysia Pahang Al-Sultan Abdullah

- **Faculty:**
  - Faculty of Manufacturing and Mechatronic Engineering Technology

## License
© 2024 SWIMBOT. All rights reserved.
