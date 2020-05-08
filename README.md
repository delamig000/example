
# ROS package: Example

This package is an example of some things that are achievable using the Robot Operating System (ROS). The package includes my_aplication, my_servies, and my_topics. My_aplication is built to show the use of a timer in ROS. The package counts down 5 seconds and reports to the user how much time is left and how much time was allotted every second after the package was launched. My_services is used to take in a phrase from the terminal and output how many words were present in the phrase. My_topics returns to the user every second a pair of real and imaginary numbers between 1-0 that were randomly generated.

## Requirements
The package was designed to be used on a system running Ubuntu 18.04 using ROS Melotic. Python 2.7.17 is also needed.

## Installation and configuration
Assuming the repository has already been installed on the system, in order to run the code, the command "catkin_make" must be entered into the terminal while in the repository workspace. Once the repository has been built the command "source devel/setup.bash" must also be issued to source the build. Now the repository is ready to be used.

## Getting started
To launch a package, you must be in the workspace on the terminal and type "roslaunch" followed by the package name and then press tab and enter. If you want to run the my_services package then you must do the same as above but also type "input:=" and then in parenthesis type the statement you desire.

## Usage
This package is to be used for educational purposes only. The package also was to be designed to be used with a launch file, however the packages can also be ran using the "roscore" and "rosrun" commands. When finished using any of the packages it is advised to issue a ctr+c command to kill the program.
