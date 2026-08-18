---
layout: page
title: Work Experience
permalink: /work_experience/
---

<html>
<head>
<style>
#bordering{
  width: 1100px;
  height: 140x;
  padding: 20px;
  border: 5px solid red;
  margin: 0;
}
#left{
 text-align: left;
}
</style>
</head>
</html>

<br>

<center>
<div id ="bordering">
<br>
<center>
<img title="siliconsynapselab" alt="Alt text" src="/images/siliconsynapse.png" style="height:347px; width:638px;">
</center>
<br>
<br>
<center>
<b style="font-size:30px"> Graduate Research Assistant (Master's Thesis) at the Silicon Synapse Lab, Northeastern University, Boston, MA </b>
</center>
<br>
<center>
<b style="font-size:20px"> Thesis Title: Agile Flight of a Morphing Robot Using Posture Manipulation and Thrust Vectoring</b><br>
<b style="font-size:20px"> Advisor: Prof. Alireza Ramezani </b><br>
<b style="font-size:20px"> Duration: May 2025 - May 2026 </b>
</center>
<ul id="left">
    <li> Proposed a hierarchical motion planning and control framework for agile trajectory tracking on M4, a morphing aerial robot (6 kg) capable of transitioning between ground and aerial configurations, developing an NMPC trajectory optimizer and whole-body controller via inverse-dynamics-based modeling of multi-joint kinematics, accelerated with ACADOS and ALTRO for real-world hardware deployment. </li>
    <li> Demonstrated high-speed sharp turns of up to 120° in MATLAB and Simscape, showing that actively reconfiguring the robot's appendages via posture manipulation and thrust vectoring reduces peak tracking error by over 60% versus fixed-geometry drone baselines at entry speeds up to 10.5 m/s. </li>
    <li> Benchmarked and performance-optimized a QP solver-based real-time control loop with solve times below 0.6 ms, validating stable hover under randomly changing joint configurations. </li>
    <li> Performed hardware-in-the-loop integration and motor servo control on a VOXL2 + ESC embedded system via frequency-domain system identification, estimating system parameters (gain K, time constant τ, delay L) using Nonlinear Least Squares and Bode analysis, and built a thrust-to-PWM pipeline modeling nonlinearity, motor lag, and delay. </li>
</ul>
<br>
<center>
<a href="https://www.researchgate.net/publication/404704424_Agile_Flight_of_a_Morphing_Robot_using_Posture_Manipulation_and_Thrust_Vectoring" target="_blank"> Link to My Thesis </a>
</center>
</div>

<br>
<br>

<center>
<div id ="bordering">
<br>
<center>
<img title="moonlab" alt="Alt text" src="/images/moon_lab.png">
</center>
<br>
<br>
<center>
<b style="font-size:30px"> Research Intern at the Multi-Robot Autonomy (MOON) Lab, IISER Bhopal, Bhopal, India </b>
</center>
<br>
<center>
<b style="font-size:20px"> Project Title: MPC-based UAV Path Planning Algorithm With CFD-Based Wind Field Estimation </b><br>
<b style="font-size:20px"> Project Duration: January 2023 - March 2024 </b>
</center>
<ul id="left">
    <li> Worked as a research intern at the Multi-Robot Autonomy Lab at IISER Bhopal under the guidance of Dr. P. B. Sujit and Dr. Manoj Kumar Tripathi. </li>
    <li> Designed a trajectory optimization and motion planning algorithm for UAVs using nonlinear MPC with CasADi and IPOPT, enforcing obstacle-avoidance constraints and wind-aware path replanning in dynamic, cluttered environments. </li>
    <li> Trained a data-free physics-informed neural network (DeepXDE, TensorFlow backend) to solve steady-state RANS equations for millisecond-level wind-field inference, enabling 100% collision-free navigation under randomized wind disturbances while reducing control effort by 9% versus a full CFD-driven planner. </li>
</ul>
<br>
<center>
<a href="https://github.com/Aryaman22102002/UAV_Path_Planning_MPC" target="_blank"> Link to Project </a>
</center>
</div>

<br>
<br>

<center>
<div id ="bordering">
<br>
<center>
<img title="eYSIP" alt="Alt text" src="/images/eysip.jpeg">
</center>
<br>
<br>
<center>
<b style="font-size:30px"> Summer Research Intern at the Embedded Real-Time Systems Laboratory (ERTS/e-Yantra Lab), IIT Bombay, Mumbai, India </b>
</center>
<br>
<center>
<b style="font-size:20px"> Project Title: Prota: The ROS Bot </b><br>
<b style="font-size:20px"> Project Duration: June 2022 - July 2022 </b><br>
</center>
<ul id="left">
    <li> Developed Prota: The ROS Bot as part of the e-Yantra Summer Internship, a low-cost open-source educational autonomous ground vehicle designed to teach ROS, SLAM, and navigation from the ground up. </li>
    <li> Performed hardware bring-up and multi-sensor integration of LiDAR, IMU, wheel encoders, depth camera, and proximity sensors on a Raspberry Pi, developing ROS drivers for data acquisition and performing sensor calibration, fusion, and time synchronization for reliable odometry and localization in a GPS-denied environment. </li>
    <li> Executed real-time SLAM using particle-filter-based localization (GMapping, Hector SLAM) and the ROS move_base navigation stack with AMCL and costmap-based obstacle avoidance, validated in Gazebo/RViz simulation and then on physical hardware. </li>
</ul>
<br>
<center>
<a href="https://drive.google.com/drive/folders/1mtaB0RybpWtX2-aTeWSyXiaaacoF5-rM" target="_blank"> Link to Project Poster and Certificate of Completion </a>
</center>
</div>
