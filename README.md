# I04
### Project Guide
Shivani Chanda - RAS Chair
### Mentors
Krisha Shah,
D.Jagannadha Reddy
### Members
Navitha R,
Suksha Kiran,
Rohit Karatagi,
Pranav Sudheer
## Acknowledgements

## Aim
The project aims to develop a robotic arm, in simulation, with an objective of pick and
place mechanism. We’ll mainly simulate the workspace,forward  kinematics and inverse
kinematics of the arm on MATLAB. If time permits, this can further be programmed to
segregate objects based on shape, size and color and then such bots can be used in
warehouses.
## Introduction
A robotic arm is a type of mechanical arm, usually programmable, with similar functions
to a human arm. A robotic arm can be used for automating various tasks which reduces
human effort which in turn will increase productivity.

![image](https://github.com/DJR-18/I04/assets/122470780/5522385e-4698-4553-ac40-2a70794c7922)
## Forward Kinematics
![WhatsApp Image 2023-05-08 at 17 52 38](https://github.com/DJR-18/I04/assets/122470780/70fe8c38-aff5-4f88-8764-e444a4a46a70)
This is forward kinematics block which receives angles and gives homogeneous matrix which gets converted to translation matrix and hence we get our
manipulator motion.Forward kinematics (for a robot arm) takes as input joint angles and calculates the Cartesian position and orientation of the end
effector. The end-effector/gripper is a device or tool that connects at the end of a robotic arm.
## Inverse Kinematics
![WhatsApp Image 2023-05-08 at 17 52 40](https://github.com/DJR-18/I04/assets/122470780/07db4b4e-b316-4ddc-9e2f-9bfd7172f934)
This is inverse kinematics block where we give translation vector which gets converted
to homogeneous matrix and which gets extracted to angles through inv kinematics block.
## Simscape multibody robot manipulator
![WhatsApp Image 2023-05-08 at 17 52 39](https://github.com/DJR-18/I04/assets/122470780/bc820556-da53-4fe1-b00e-d9ad8516d0ca)
![WhatsApp Image 2023-05-08 at 17 52 37](https://github.com/DJR-18/I04/assets/122470780/ec80d5c1-218e-4824-9071-351078f7a8f2)
## Final block system
![WhatsApp Image 2023-05-08 at 17 52 41](https://github.com/DJR-18/I04/assets/122470780/24cff656-6c7d-4269-be67-7d87f8f8fe92)
This is the final block system where first port of scope is the actual motion second
port gives the ideal motion and the third port gives the velocity.
## Conclusion

## References
https://ch.mathworks.com/help/sm/getting-started-with-simmechanics.html
https://ch.mathworks.com/help/simulink/slref/pidcontroller.html
https://ch.mathworks.com/help/sm/ug/joints.html
https://ch.mathworks.com/help/stateflow/getting-started.html?s_tid=CRUX_lftnav
