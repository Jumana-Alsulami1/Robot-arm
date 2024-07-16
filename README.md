# Robot-arm

This task controls a robot arm using the Joint State Publisher and through movement and kinematics. The task is implemented using ROS on Ubuntu 20.04 within a virtual machine.

Controlling the robot arm by joint_state_publisher

1- Set up the ROS environment to create a workspace.

![Screenshot 2024-07-10 021538](https://github.com/user-attachments/assets/52eb957f-41bb-44f0-a2e0-0ed19b8d25e0)

![Screenshot 2024-07-10 022528](https://github.com/user-attachments/assets/b753c171-97dc-4b65-91d8-61a4876cae36)

2- Clone the robot arm package from the smart method repository.

![Screenshot 2024-07-10 023227](https://github.com/user-attachments/assets/b6cd2a1c-4ee8-4e88-928d-854eaf3d8396)

3- Install all the dependencies.

![Screenshot 2024-07-10 023440](https://github.com/user-attachments/assets/a2b4653f-662f-4497-8513-9b2435a0c959)

![Screenshot 2024-07-10 023725](https://github.com/user-attachments/assets/727f0acc-58ea-4ba4-9027-99967d55d61e)


![Screenshot 2024-07-10 023807](https://github.com/user-attachments/assets/bfe643ef-ab9e-4605-beda-6091863e10d3)

![Screenshot 2024-07-10 023929](https://github.com/user-attachments/assets/bfd6ba19-6505-44e6-bf3d-490f1d85f051)

![Screenshot 2024-07-10 024008](https://github.com/user-attachments/assets/af5263f2-5d0d-4c53-a184-efa13a196264)



4-Open the robot arm where you can control it with the joint state publisher.


5- Visualizes the communication between nodes and topics in the ROS.


6- Displays the real-time data being published to the joint states topic.


7- Adjust the position of the joint of the robot arm.

Controlling the robot arm by Moveit and kinematics

8- Launch the gazebo to simulate the robot arms.


9- Change the permissions of the joint_states_to_gazebo.py file to make it executable. 


10- Visualizes the communication between nodes and topics to control the robot arm.


11- Plan the move of the robot arm in Moveit and see the actual move in the gazebo.
