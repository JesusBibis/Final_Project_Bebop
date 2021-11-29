# Multiple Drone Control


## Members 

Jesus Orlando Rodriguez Ramirez A01731627

Carlos Ignacio Villalobos Sanchez A01731558

Jesús Flores Bibiano A01327143

## Information

The zip file available at the repository contain all the modification made to the original ros programs to control bebops, this include 

* 2 Node creation file that represent each of the drones 
* A new keyboard setting to control both drones
* A set of intructions to desing figures using the drones 

## Instructions

1- Clone the repository to your computer, make sure you have ros kinetic installed correctly

2- Previously we follwed the guide to install all ros kinetic dependencies even if they have already reached end of life

3- Open a terminal and run the comand "roscore"

4- Open a new terminal cd into the project folder and run catkin_make

5- After is finished run the desired drone package with roslaunch bebop_driver bebop_node_1.launch

6- If you wish to run another drone then open a new terminal cd into the project folder and run the desired drone package eg roslaunch bebop_driver bebop_node_2.launch

7- Also we follwed the steps to change bebop ip to give each drone a unique ip and avoid network conflicts

8- To run the camera view open a new terminal cd into project folder and use rosrun Image_viewer Image_viewer

9- To run the keyboard control for the drone open a new terminal cd into project folder and use rosrun teclado teclado

10- For each change you make in teclado or Image_viewer you will need to run catkin_make --pkg teclado teclado or catkin_make --pkg Image_viewer Image_viewer to make sure your changes are compiled correctly

