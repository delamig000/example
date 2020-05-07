
# ROS package: Example

This package is an example of some things that are achieveable using the Robot Operating System (ROS). The package includes my_aplication, my_servies, and my_topics. My_aplication is built to show the use of a timer in ROS. The package counts down 5 seconds and reports to the user how much time is left and how much time was alloted every second after the package was launched. My_services is used to take in a phrase from the termanal and out put how many words were pressent in the phrase. My_topics returns to the user every second a pair of real and imaginary numbers between 1-0 that were randomly generated.

## Requirements
The package was designed to be used on a system running Ubuntu 18.04 using ROS Melotic. Python 2.7.17 is also needed.

## Installation and configuration

Assuming the repository has already been installed on the system, in order to run the code the command "catkin_make" must be entered into the termainle while in the repository work space. Once the repository has been built the command "source devel/setup.bash" must also be issued to sorce the buld. Now the repository is ready to be used.

## Getting started
To launch a package you must be in the workspace on the termanal and type "roslaunch" followed by the package name and then press tab and enter. If you want to run the my_services package then you must do the same as above but also type "input:=" and then in paranthesis type the statement you desire.

## Usage
This pakage is to be used for educational purposes only. The pakage also was to be designed to be used with a launch file, however the packages can also be ran using the "roscore" and "rosrun" commands. When finished using any of the pakages it is advised to issue a ctr+c command to kill the program.