# University of houston | ECE                                                                                 
# ECE 5397/6397: Introduction to Robotics                                                                      
# Spring 2016

## **Schedule**

**Note: Reading assignments should be completed before the lecture for which they are assigned.**

| Date | Topics | Assignment | Due
| --- | --- | --- | --- |
Jan 19 | General introduction and overview of the course | Read Chap. 1, [student registration Swarmathon][student-res]
Jan 21 | Rotation matrices, SO(n) |  Read 2.1, 2.2, Each team make an account on the [Swarmathon Forum][swarm-forum], run the [Swarmathon outreach][swarm-outreach]
Jan 22 | [Webinar – Student Orientation / Hardware](http://nasaswarmathon.com/timeline/), will be shown in room N328, 1 PM CST |
Jan 26 | Coordinate transformations, composition of rotations, homogeneous transformations |  Read 2.3, 2.4, 2.7
Jan 28 | Coordinate transformation examples, Parameterizations of SO(3), Euler angles |  Read 2.5, github checkin #1
Feb 02 | Similarity transformations, rotations w.r.t. the fixed frame, axis/angle representation. Introduction to forward kinematics | Read 3.1 and 3.2 | **HW 01**
Feb 04 | Forward kinematics: Denavit-Hartenberg convention and the derivation of D-H transformation matrix, assigning link frames using the DH convention. |  Ch 1 & 2 [A Gentle Introduction to ROS][AGITR]
Feb 09 | Forward kinematics examples | [Ch 3 & 4][AGITR]
Feb 11 | Inverse kinematics: general overview, geometric method, kinematic decoupling | Read 3.3 | **HW 02** (FWD Kinematics)
Feb 16 | Inverse kinematics examples: Articulated arm, SCARA arm, and spherical wrist. | [Ch 5 & 6][AGITR]
Feb 18 | Introduction to angular velocity, skew symmetric matrices | Read 4.1-4.3 | **HW 03** (INV Kinematics)
Feb 23 | so(3) and the derivative of a rotation matrix, velocity of a point attached to a moving frame, addition of angular velocities | Read 4.4-4.6
Feb 25 | The manipulator Jacobian | [Ch 7][AGITR]
Mar 01 | Jacobian examples  | [Ch 8][AGITR]
Mar 03 | Manipulator singularities | Read 4.9 | **HW 04** (Jacobian)
Mar 08 | Computer vision overview, segmentation | Read 11.3
Mar 10 | Segmentation by minimizing within-group variance, recursive formulation for within-group variance | Read 11.3
Mar 15 | SPRING BREAK
Mar 17 | SPRING BREAK
Mar 22 | Connected components, moments | Read 11.4-11.5 | **HW 05** (Computer Vision)
Mar 24 | Position and orientation in binary images | [Ch 9][AGITR]
Mar 29 | Imaging geometry | Read 11.1-11.2
Mar 31 | Exam 1
Apr 05 | Camera calibration,  Visual servo control Chapter 12
Apr 07 | Introduction to path planning: configuration space obstacles for polygons that translate in the plane, generalized Vornoi graphs, visibility graphs, cell decomposition. | Read 5.1 | **HW 06** Imaging Geometry
Apr 12 | Path planning using artificial potential fields | Read 5.2
Apr 14 | Path planning using artificial potential fields (cont), planning as optimization | Read 5.3  
Apr 18-22 | Swarmathon at NASA Kennedy Space Center | [Ch 10][AGITR]
Apr 19 | Sampling-based methods for path planning | Read 5.4 | **HW 07** (Config Space)
Apr 21 | Inverse Velocity , projection onto the null space of the manipulator Jacobian | Read 4.11
Apr 26 | Singular value decomposition, Manipulability | Read 4.12 & Appendix B
Apr 28 | Manipulability, gradient projection to achieve secondary tasks. | | **HW 08** (Interaction matrix)

<!-- Links -->
[student-res]:http://nasaswarmathon.com/student-registration-form/
[swarm-forum]:http://swarmathon.discussion.community/
[swarm-outreach]:http://nasaswarmathon.com/outreach/
[AGITR]:https://cse.sc.edu/~jokane/agitr/
