# ROS

# Description:

Using a turtlebot 3 in a simulated environment equipped with 2 intel real sense R200 cameras and implement RTAB for mapping the environment
Caution: The real time factor is too low in the gazebo because of the memory limitation in vmware

Due to the contract issue, I can't share the entire workspace with you. I have only attached the launch files for your reference. 
# Description of launch file
world.launch: Will launch the world in gaebo with the trutlebot3
mapping2.launch: Will start RTAB mapping and open RTAB viewer
teleop.launch: For controlling the robot
