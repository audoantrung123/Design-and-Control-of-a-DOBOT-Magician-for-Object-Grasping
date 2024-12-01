# Design and Control of a DOBOT Magician for Object Suctioning

An Off-policy Reinforcement Learning Algorithm for Optimal Tracking Control Problem

Full report: [Link](https://drive.google.com/drive/folders/1paShYH4LNmUfNl9dPRv1EbUq-We0ztPf?usp=sharing) 
## 1. Introduction
This project focuses on the design and control of a DOBOT Magician robotic arm for object suctioning. We aim to develop a robust system capable of reliably grasping and manipulating objects using a suction cup end-effector. This involves hardware design and the integration of perception techniques to identify and locate objects, calculating forward and inverse kinematics, planning efficient motions to reach and grasp them, and implementing control algorithms to ensure stable and adaptive suctioning.  This research contributes to the advancement of robotic manipulation and has potential applications in diverse fields such as manufacturing, automation, and logistics, where precise and adaptable object handling is essential.


## 2. MODEL DESIGN AND CONSTRUCTION

<p align="center">
  <img src="https://github.com/user-attachments/assets/9f233989-aefb-48cf-84aa-b211b6af81f6" width="40%" />
</p>
<p align="center"> Figure 1. Creating a Dobot Magician Model in Autodesk Inventor</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cfa810ed-9508-46c4-99a4-8461405431ae" width="40%"/>
</p>
<p align="center"> Figure 2. Designing a Custom Robot Base</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f61fa130-ab50-427a-880c-44c74191a18c" width="40%" />
</p>
<p align="center"> Figure 3. Designing Link 1 of the Robot Arm</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a99effe0-afc7-42b2-b12f-78f3e77e88a2" width="40%" />
</p>
<p align="center"> Figure 4. Designing Link 2 of the Robot Arm</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c9825790-abbe-414b-ac7d-a33818015bc1" width="40%"/>
</p>
<p align="center"> Figure 5. Suction mechanism</p>

## 3. Computation and Validation of Kinematics

<p align="center">
  <img src="https://github.com/user-attachments/assets/6f5ab98b-e53b-499d-b881-c58709f4b4fc" width="50%" />
</p>
<p align="center"> Figure 6. Establishing the Robot's Kinematic Chain and Joint Axes</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b2d99121-80ab-4e21-b98b-0ca3eecab09b" width="50%" />
</p>
<p align="center"> Figure 7. Deriving the Denavit-Hartenberg (DH) Parameters</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8ca690c0-ab1c-459a-ad54-24266d033b5e" width="50%" />
</p>
<p align="center"> Figure 8. Forward and Inverse Kinematics Verification in Simulink</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5e1e7047-c36a-43ce-9c4d-2391ec3f6adb" width="50%" />
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/9d3c6e18-0097-4895-a5de-ae2f425bd6a5" width="50%"/>
</p>
<p align="center"> Figure 9. Robot Dynamics Simulation in Simulink</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/5abea4f7-1a4c-43cc-bbad-54ca20ea9978" width="50%"/>
</p>
<p align="center"> Figure 10. Mathematical Formulation of Inverse Kinematics/p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/7d343bb4-19d6-4460-a6a0-6363d0cee06f" width="50%"/>
</p>
<p align="center"> Figure 11. Mathematical Formulation of Forward Kinematics</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/942171ff-16a6-4876-b11e-401e24bb0ed7"width="50%" />
</p>
<p align="center"> Figure 12. MATLAB Code for Inverse Kinematics Calculation</p>


## 4. Experrimental Testing

<p align="center">
  <img src="https://github.com/user-attachments/assets/a5947a62-cb73-4e02-bd11-48bfb37321a3" width="50%"/>
</p>
<p align="center"> Figure 13. Graphical User Interface (GUI) for Robot Control</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/48db4cf6-ab5e-4261-8641-c55a402b37e7" width="30%" />
</p>
<p align="center"> Figure 14. Actual Robot Model</p>

## 5. Conclusion

In conclusion, this project successfully achieved the following:

* **Completion of the Inventor design and construction of the Robot Magician model:** The physical robot was built based on the design created in Autodesk Inventor.
* **Kinematic analysis and verification:** Both forward and inverse kinematics were calculated and validated, ensuring accurate positioning and control of the robot arm.
* **Computation and simulation:** Necessary calculations and simulations were performed to determine the robot's workspace and optimize its performance. (You might want to be more specific here about what was calculated and simulated, e.g., "workspace analysis," "motion planning simulations," etc.)
* **Successful design of the user interface:** A user interface was developed to enable intuitive control and monitoring of the robot.
* **Accurate motor control and object grasping:** The robot achieved 100% accuracy in grasping objects within its operational workspace.








