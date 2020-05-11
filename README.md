# Final-Project

## ROS package: my_topics
### This is a simple message publisher and generates a message that is inputed into the command for the launch of a package. This can be useful for timing and setting up communication between different packages. This is helpful when trying to communicate with other packages such as my_services because it broadcasts the information for the other package.

## ROS package: my_services
### This package creates a server that has defined functions that other packages can reference and activate so that the server is running the function for the clients. This can be very useful for short timed requests, and will act out the command quickly.

## ROS package: my_actions
### This package has methods of task performing that can be commanded from a topic such as the my_topics package that will run once it recieves data or other information. In the case of this package this has the function of a timer. This is useful when used in conjuction with other packages that act an action.

## Requirements:
### Using these packages was done in a virtualbox machine with ubuntu, so those are general requirements in order to run these packages. The ubuntu version 18.04 specifically was used. The ROS program is also required to be able to use the packages. 

## Installation and Configuration:
### Forking these packages would be prefered.

## Getting started:
### As with most ROS packages you will need to use the command 'roscore' before opening a few other tabs in the CMD window if you want to work locally. Working locally is the prefered method as that is the way I worked on these packages, but working on github shouldn't be too different as long as you are working in the CMD window. 
### Within each package there will be seperete packages for each operation, such as the message_subscriber and the message_publisher packages. Each package needs to be used in a seperate window of the CMD and are launched with the command 'rosrun'

## Usage:
### Commands
#### - roscore
#### - rosrun
#### - source
#### 

