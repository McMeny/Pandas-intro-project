# Pandas-intro-project

This is a data analysis project I started to teach myself the Pandas library. 

# RESEARCH QUESTION: WHICH JOINT ON A 6-DOF ROBOTIC ARM INFLUENCES THE X,Y,Z POSITION OF THE END EFFECTOR?

Background:
Robotic manipulators enable precise and repeatable motions in robotic systems. They were made to move and interact with objects by mimicking the motion of a human arm. To control these manipulators, robot kinematics were developed to understand the geometric relationship between a robot's joint parameters and the position and orientation of its end-effector (device attached to the end of a robotic manipulator). This end effector is mounted on the wrist of a 6-DOF manipulator arm.

Forward kinematics is the computation of the end-effector's position in Cartesian space based on a known set of joint parameters (such as angles or displacements). This typically involves matrix transformations derived from the robot's kinematic chain using standardized approaches such as the Denavit-Hartenberg (DH) convention.

The dataset used in this project models the forward kinematics of the ABB IRB 120, a 6-DOF industrial robotic arm. Each sample consists of randomly sampled joint angles (q1 through q6), and the corresponding end-effector position computed using a DH-based FK model with over 15,000 configurations. Link to the dataset used can be found here: https://www.kaggle.com/datasets/sandibaressiegota/robot-kinematics-dataset?resource=download

# Potential extension: Can machine learning regressors predict joint angles from the Cartesian position of the end effector?