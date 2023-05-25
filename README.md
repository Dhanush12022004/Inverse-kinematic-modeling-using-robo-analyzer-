# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
STEP 1:Open Robo Analyser

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/66def37e-14a5-4b1e-9e9b-d6eb6b45a2a3)

STEP 2:Set DoF as 3.

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/40e1f10c-b319-43b0-924d-150f001873de)

STEP 3:Select IKin in Analyses to set the parameters .

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/345d3fa9-f489-4359-a654-deb01d95b8cb)

SETP 4: After setting the parameters ,select FKin in analyses.

 ![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/ee5297f5-22b9-4815-92bd-e64c70263c78)

STEP 5: Select Graph -> Select Links or Joints to plot the graph respectively

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/df9bc708-8716-4431-95da-4f7fe91c7456)






### SIMULATION 
 
 
 ![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/ee5297f5-22b9-4815-92bd-e64c70263c78)

 
 
 
 
 ### PLOT 
 
 LINKS:
 
 LINK 1:
 
 ![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/e93e95af-b48a-4efc-be66-ea4036e21f74)


LINK 2:

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/df9bc708-8716-4431-95da-4f7fe91c7456)

LINK 3:

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/8d5a9788-071a-4aba-9a87-4868ef510970)


JOINTS:

JOINT 1:

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/fd461064-7add-438d-b45b-562046d3536e)


JOINT 2:

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/bf8f62eb-f20c-4ce8-bb4d-a17ff21573bc)

JOINT 3:

![image](https://github.com/Dhanush12022004/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135558/2618db91-2391-403e-9e4b-7d4d88655dc0)



 
 
 
 
 
 
 
 


### RESULTS :  
Therefore the  analysis of the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and plotting  the graph of joint angle for a given  input end effector position is performed successfully.
