# University of houston | ECE                                                                                 
# ECE 5397/6397: Introduction to Robotics                                                                      
# Spring 2016

* **Location**: [D3](http://www.uh.edu/maps/buildings/?short_name=d3) [W205](http://www.uh.edu/infotech/php/classrooms.php?class_id=63)
* [**Class**](https://fp.my.uh.edu/psc/saprd_fp/EMPLOYEE/HRMS/c/COMMUNITY_ACCESS.CLASS_SEARCH.GBL): 	11:30am-1:00pm, Tues & Thurs, 	01/19/2016 - 05/13/2016 
* **Office hours**: 2:00-3:00pm, Tues & Thurs	in N386, or by appointment
* **Instructor**:  Dr. Aaron T. Becker, [email](mailto:atbecker@uh.edu), phone: (713) 743-6671
* **Teaching Assistant**: Li Huang, [email](mailto:lihuang.mech@gmail.com), phone: (713) 743-7296

## **Course Description**:

 *Fundamentals of robotics including rigid motions; homogeneous transformations; forward and inverse kinematics; velocity kinematics; motion planning; trajectory generation; sensing, vision; control. Also, introduction to swarm programming, search strategies, and distributed planning and control.*

## **Project 1, Swarmathon**:

 The University of Houston was selected as a finalist for the [NASA Swarmathon Challenge](nasaswarmathon.com). As a finalist, we have been awarded three ‘swarmie’ robots, as well as access to a simulator environment in ROS for testing algorithms. Students will form 2-person teams.  Each team will complete three challenges in ROS, concluding with an in-class competition on the Swarmathon challenge. Winning teams will be allowed to implement on the hardware robots and will compete in the national competition.  Before class begins, please complete [the introductory modules](http://nasaswarmathon.com/outreach/) and install [ROS Indigo](http://wiki.ros.org/indigo/Installation/Ubuntu), on your computer.

## **Project 2, Robot Arm**:

 Students will form 2-person teams.  Each team will build and control their own robot arm, powered by servos.  The instructor will provide standard laser-cut arm components; teams will purchase their own servos & Arduino Mega (or suitable clone). We will use these arms to implement automatic controllers, forward and inverse kinematics, and forward/inverse velocity control.  Teams may design their own laser-cut components for the final stage of the project.

## **Prerequisites**:


Credit for or concurrent enrollment in Calculus III ([MATH 2433](http://catalog.uh.edu/preview_course_nopop.php?catoid=6&coid=20471)), Linear Algebra ([Math 2331](http://catalog.uh.edu/preview_course.php?catoid=6&coid=20460)), Differential Equations ([MATH 3331](http://catalog.uh.edu/preview_course_nopop.php?catoid=6&coid=20471)), and {Automatic Controls ([ECE 4375](http://catalog.uh.edu/preview_course_nopop.php?catoid=6&coid=19213)) or Dynamics and Control of Mechanical Systems ([MECE 3338](http://catalog.uh.edu/preview_course_nopop.php?catoid=6&coid=2527))}

## **Textbook**:

[Robot Modeling and Control](http://www-cvr.ai.uiuc.edu/~seth/index.php?u=spongbook)

**Mark W. Spong, Seth Hutchinson, M. Vidyasagar,**

John Wiley and Sons, Inc., 2005

Readings and assignments will come from this book.  You may share a book with a classmate. Over the next 14 weeks we will intensively learn from chapters 1, 2, 3, 4, 5, 11, 12.

## **Grading**:

 Grades will be determined on the basis of exams, quizzes, attendance, and submitted homework grades with the following approximate weights.  The actual weights will be fixed at the end of the semester.

* 30%	Homework 
* 20%	Lab 
* 25%	Exam 1 
* 25% 	Exam 2
* You are allowed to discuss the homework problems and projects with your classmate but you cannot copy your classmate’s homework and project. 
* Suspected cases of dishonesty will be promptly submitted to department’s hearing officer, as per the University of Houston’s [Academic Honesty](http://catalog.uh.edu/content.php?catoid=6&navoid=1025%23Article_3._Categories_of_Academic_Dishonesty) policy.

## **Exam Schedule**:

  The FINAL EXAM will be given on Tues., May 10 from 11:00 am-2:00 pm, 

## **Late Policy**:

 Paper copies of your homework are due by 11:35am. A homework drop box will be physically locked after that time, and we will discuss the answers.

## **Goals**:

 By the course end, you will be able to implement and use:
Coordinate transforms, [rotation matrices](https://en.wikipedia.org/wiki/Rotation_matrix), [Denavit-Hartenberg convention](https://en.wikipedia.org/wiki/Denavit%E2%80%93Hartenberg_parameters), Robotics [kinematics](https://en.wikipedia.org/wiki/Forward_kinematics) and [inverse kinematics](https://en.wikipedia.org/wiki/Inverse_kinematics), [velocity kinematics](https://en.wikipedia.org/wiki/Robot_kinematics#Velocity_kinematics) and inverse velocity kinematics, basic [computer vision](https://en.wikipedia.org/wiki/Computer_vision), [path planning artificial potential fields](https://www.youtube.com/watch?v=r9FD7P76zJs), [sampling-based methods](http://planning.cs.uiuc.edu/ch5.pdf).  A lab component will integrate these topics with robotic hardware.

| Date | Topics | Assignment
| ----- | --- | --- |
Jan 19 | General introduction and overview of the course |Read Chap. 1, student registration swarmathon
Jan 21 | Rotation matrices, SO(n) | Read 2.1, 2.2, http://nasaswarmathon.com/outreach/
Jan 22 | [Webinar – Student Orientation / Hardware](http://nasaswarmathon.com/timeline/) |
Jan 26 | Coordinate transformations, composition of rotations, homogeneous transformations | Read 2.3, 2.4, 2.7
Jan 28 | Coordinate transformation examples, Parameterizations of SO(3), Euler angles | Read 2.5, github checkin #1
Feb 02 | Similarity transformations, rotations w.r.t. the fixed frame, axis/angle representation. Introduction to forward kinematics | Read 3.1 and 3.2
Feb 04 | Forward kinematics: Denavit-Hartenberg convention and the derivation of D-H transformation matrix, assigning link frames using the DH convention. 
Feb 09 | Forward kinematics examples 
Feb 11 | Inverse kinematics: general overview, geometric method, kinematic decoupling | Read 3.3
Feb 16 | Inverse kinematics examples: Articulated arm, SCARA arm, and spherical wrist.
Feb 18 | Introduction to angular velocity, skew symmetric matrices | Read 4.1-4.3
Feb 23 | so(3) and the derivative of a rotation matrix, velocity of a point attached to a moving frame, addition of angular velocities | Read 4.4-4.6
Feb 25 | The manipulator Jacobian 
Mar 01 | Jacobian examples  
Mar 03 | Manipulator singularities | Read 4.9
Mar 08 | Computer vision overview, segmentation | Read 11.3
Mar 10 | Segmentation by minimizing within-group variance, recursive formulation for within-group variance | Read 11.3
Mar 15 | SPRING BREAK
Mar 17 | SPRING BREAK
Mar 22 | Connected components, moments | Read 11.4-11.5
Mar 24 | Position and orientation in binary images | 
Mar 29 | Imaging geometry | Read 11.1-11.2
Mar 31 | Exam 1
Apr 05 | Camera calibration,  Visual servo control Chapter 12
Apr 07 | Introduction to path planning: configuration space obstacles for polygons that translate in the plane, generalized Vornoi graphs, visibility graphs, cell decomposition. | Read 5.1
Apr 12 | Path planning using artificial potential fields | Read 5.2
Apr 14 | Path planning using artificial potential fields (cont), planning as optimization | Read 5.3  
Apr 18-22 | Swarmathon at NASA Kennedy Space Center
Apr 19 | Sampling-based methods for path planning | Read 5.4
Apr 21 | Inverse Velocity , projection onto the null space of the manipulator Jacobian | Read 4.11
Apr 26 | Singular value decomposition, Manipulability | Read 4.12 & Appendix B
Apr 28 | Manipulability, gradient projection to achieve secondary tasks.

**Academic Honesty Policy**: Students in this course are expected to follow the Academic Honesty Policy of the University of Houston.  It is your responsibility to know and follow this policy.  You must sign the Academic Honesty Statement on the last page of this handout, detach it, and submit it.  If you fail to do this, you may be dropped from the course. For more information, see the [Academic Honesty](http://catalog.uh.edu/content.php?catoid=8&navoid=1352) in the Undergraduate Catalog

**Religious Holy Days**: Students whose religious beliefs prohibit class attendance on designated dates or attendance at scheduled exams may request an excused absence.  To do this, you are **strongly encouraged** to request the excused absence, in writing, by Wednesday, February 3, 2015.  Please submit this written request to your instructor to allow the instructor to make appropriate arrangements. 
More information can be found [here](http://www.uh.edu/dos/studenthandbook/academicpolicy/a_holydays.html)

**Students with Disabilities**: Students with recognized disabilities will be provided reasonable accommodations, appropriate to the course, upon documentation of the disability with a Student Accommodation Form from the Center for Students with Disabilities. To receive these accommodations, you must request the specific accommodations, by submitting them to the instructor in writing, by Wednesday, February 3, 2015.  Students who fail to submit a written request will not be considered for accommodations. More information, can be found [here](http://www.uh.edu/dos/studenthandbook/academicpolicy/a_disability.html)

**Attendance**: Attendance at all classes is expected and required. The instructor may, if he chooses, take attendance in any class, at any time during the class. The instructor may do this as many times per class period as he chooses, without warning. The attendance grade can be included in the grade for the course.  Attendance at every class is expected.  Roll will be occasionally taken and an in-class exam may be given during any class period.  There will be no make-up of missed in-class exams.

**Grade Posting**: You may find out your grade in the course online using PeopleSoft.  Normally, the grades are available about one week after the final exam. The instructor is not allowed to give out grades over the phone or by email.  During the semester, grades will be posted on Blackboard in a secure manner, i.e., so that only you will have access to your grades. Final grades will also be posted on Blackboard at the end of the semester; however, the official grade reporting is done on PeopleSoft, not on the Blackboard.

**Grade Point Rule**: The following approximate grade point scale will be used in determining your grade.  This scale may be modified somewhat, but is included here so that you will have a general idea of how well you are doing in the course.  The final grade scale will be determined at the end of the semester.

* 90–100: A's
* 80–89.9: B's
* 70–79.9: C's
* 60–69.9: D's
* <60: F

**Withdrawal Policy**: The withdrawal dates listed in the Academic Calendar section of the Class Schedule will be followed strictly. You may drop the course without receiving a grade until Wednesday, February 4, 2015 which is the University's last day to drop without receiving a grade. After this date and until Monday April 6, which is the University's last day to drop, you may drop with a W if you have not exceeded your total W limit (the limit applies to undergraduate students only). Grades of Incomplete (I) will be given only when a small portion of the course has not been completed for a good reason.  If the material has been completed, an “I” grade cannot be given. Detailed information about these issues is available in the University of Houston Undergraduate Catalog.

**Blackboard**: We will be using the Blackboard Learn web site (http://www.uh.edu/blackboard) for posting of grades and email only. All documents and handouts will be available on the website at http://www.egr.uh.edu/courses/ece/Ece2300/. We will assume that your UH email alias (joejones@uh.edu) is pointed to a working email server, and that you are available at that address.

**Related Robotics Courses**: Consider taking 
* [MECE 3400 “Introduction to Mechanics”](http://catalog.uh.edu/preview_course_nopop.php?catoid=8&coid=25949), 
* COSC 4332 or 6332 - Medical Robots & Interventions
* INDE 7361 - Industrial Robotics
* ECE 6325 - State-Space Control Systems
* ECE 6335 - Digital Control Systems
* ECE 6390 - Linear Multivariable Control Systems
* ECE 7333 - Optimal Control Systems
* ECE 7334 - Advanced Digital Control Systems
