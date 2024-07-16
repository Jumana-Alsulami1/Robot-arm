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

![Screenshot 2024-07-10 030023](https://github.com/user-attachments/assets/217c23be-ff15-4f24-acb1-bbe5cf63f6bf)


5- Visualizes the communication between nodes and topics in the ROS.

![Screenshot 2024-07-10 030141](https://github.com/user-attachments/assets/6b5100e2-101c-4bf5-a519-91f2186c5bcc)


6- Displays the real-time data being published to the joint states topic.

![Screenshot 2024-07-10 030257](https://github.com/user-attachments/assets/68a28bbc-df0d-4618-afad-3a2d4cecb367)

7- Adjust the position of the joint of the robot arm.

![Screenshot 2024-07-10 030550](https://github.com/user-attachments/assets/62aefd5c-1af0-4757-b4ce-4874f1bc7c32)

Controlling the robot arm by Moveit and kinematics

8- Launch the gazebo to simulate the robot arms.

![Screenshot 2024-07-10 031148](https://github.com/user-attachments/assets/4889aa78-f222-473b-8a63-c4b454fe9b9c)


9- Change the permissions of the joint_states_to_gazebo.py file to make it executable. 

![Screenshot 2024-07-10 031847](https://github.com/user-attachments/assets/0174a743-e77a-43ea-9af2-3794451899cf)


10- Visualizes the communication between nodes and topics to control the robot arm.

![Screenshot 2024-07-10 032637](https://github.com/user-attachments/assets/084e922e-5b2c-428b-9c02-308d7e337716)


11- Plan the move of the robot arm in Moveit and see the actual move in the gazebo.

![Screenshot 2024-07-10 034306](https://github.com/user-attachments/assets/64830980-5d46-474a-bb30-cfb43ed8de50)

![Screenshot 2024-07-10 034437](https://github.com/user-attachments/assets/e3b9af97-ecee-4ad4-aecb-c102d9eb5a39)
