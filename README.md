# Build My World

## Project Overview
This project is part of the Robotics Software Engineer Nanodegree. The goal is to build a custom Gazebo world and simulate a robot environment using the Gazebo simulator.

The project demonstrates understanding of:
- Gazebo world creation
- Model placement
- Simulation environment setup
- Basic plugin integration (if used)

## Environment
- OS: Ubuntu 20.04 / 18.04
- ROS: ROS Noetic / Melodic
- Gazebo: Gazebo 11 / compatible version
- Compiler: g++

## Project Structure
```text
project_folder/
├── model/
├── world/
├── script/
├── CMakeLists.txt
└── README.md
```
World Description

The simulated environment includes:

    A custom indoor world
    Static objects such as walls, furniture, and other models
    Proper object placement to create a realistic robotics environment

How to Build and Run

Clone the repository

```bash

git clone <your-repo-link>
cd <your-project-folder>
```
Build the project
```bash

mkdir build
cd build
cmake ..
make
```

Launch the world

```bash

gazebo ../world/your_world_file.world
```
Features

    Custom Gazebo world
    Multiple inserted models
    Organized project structure
    Simulation-ready environment

### Plugin Information

If a plugin was implemented, describe:

    What the plugin does
    Which model it is attached to
    How it behaves during simulation

Example: This project includes a simple world plugin that prints a message to the terminal when the simulation starts.

### Results

The world launches successfully in Gazebo and displays the designed environment with all required models.
