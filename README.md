# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:

1. Open the software named Robo analyzer.

2. Select the robo with the degree of freedom as per requirement.

3. Change the values of the link length with the given values.

4. Make sure the robo is ready and start simulation. 

5. After that plot the graph between the link and the joints.

6. Update the DH parameters of the link configuration and end effector configuration.


### SIMULATION 

4 DOF

![Screenshot (262)](https://user-images.githubusercontent.com/86832944/199653969-8edd7004-f47f-4002-91e7-db2819332f27.png)

 
 6 DOF
 
 ![Screenshot (263)](https://user-images.githubusercontent.com/86832944/199654228-8f0a5022-cec6-4438-b6e8-462f25d379b5.png)
 
 
 ### PLOT 
 
 4 DOF
 
 ![Screenshot (265)](https://user-images.githubusercontent.com/86832944/199654703-2723cd4e-96e6-4a32-a2e6-515dd05c21cd.png)
 
 6 DOF
 
 ![Screenshot (264)](https://user-images.githubusercontent.com/86832944/199654752-75a009e1-cdc3-42e1-8942-120852c453f0.png)




### RESULTS :  

Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
