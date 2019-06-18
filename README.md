# ridgeback_yumi
# ridgeback_yumi without ridgeback 
1)Add the following lines in the /etc/hosts 
192.168.125.1		yumi-robot
192.168.125.3		OPTODAQ-LEFT
192.168.125.4		OPTODAQ-RIGHT
192.168.125.201         yumi-grippercamera-r
192.168.125.202         yumi-grippercamera-l

2) Edit ip address to 192.168.125.50 

3) add the ROS_IP=192.168.125.50 in .bashrc

4) roslaunch ridgeback_yumi_launch yumi_optodaq.launch 

