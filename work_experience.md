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
<img title="siliconsynapselab" alt="Alt text" src="/images/siliconsynapse.png">
</center>
<br>
<br>
<center>
<b style="font-size:30px"> Graduate Research Assistant (Master's Thesis) at the Silicon Synapse Lab, Northeastern University, Boston, MA </b>
</center>
<br>
<center>
<b style="font-size:20px"> Thesis Title: Agile Flight of a Morphing Robot Using Posture Manipulation and Thrust Vectoring </b><br>
<b style="font-size:20px"> Duration: May 2025 - Present </b>
</center>
<ul id="left">
    <li> Proposed a hierarchical control framework for agile trajectory tracking on the Multi-Modal Mobility Morphobot (M4) (6 kg), a morphing aerial robot capable of transitioning between ground and aerial configurations, under the guidance of Prof. Alireza Ramezani. </li>
    <li> Developed the NMPC trajectory optimizer using nonlinear optimization (CasADi/IPOPT), a QP-based real-time thrust allocator, and a thrust-to-PWM mapping pipeline for hardware deployment on a conventional quadrotor platform. </li>
    <li> Demonstrated in simulation that actively reconfiguring the robot's appendages across aerodynamic regimes to utilize posture manipulation and thrust vectoring outperforms fixed-geometry baselines in tracking error and thrust redistribution, enabling high-speed sharp turns of up to 120°. </li>
    <li> Validated QP-based real-time thrust allocation under active posture manipulation, demonstrating stable hover throughout randomized joint configuration changes. </li>
    <li> Performed bench-top motor-ESC characterization via frequency-domain system identification on a VOXL + ESC stack, estimating system parameters (gain K, time constant τ, delay L) from step and sinusoidal excitation using Nonlinear Least Squares and Bode analysis; validated by inverting the model into a force-to-PWM mapping. </li>
</ul>
</div>

<br>
<br>

<center>
<div id ="bordering">
<br>
<center>
<img title="moonlab" alt="Alt text" src="/images/moon_lab.jpeg">
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
    <li> Co-developed CFDMPC, a novel framework integrating PINN-based wind field estimation with NMPC (CasADi/IPOPT) for wind-aware UAV path planning in cluttered environments, achieving 100% collision-free navigation across all obstacle configurations while the constant-wind baseline crashed in every multi-obstacle scenario. </li>
    <li> Trained a data-free PINN using DeepXDE (TensorFlow backend) to solve steady-state RANS equations without precomputed simulation data, enabling millisecond-level wind field inference at arbitrary spatial locations compared to 5 wall-clock hours for traditional CFD solvers. </li>
    <li> Validated robustness under randomized inlet velocities and directions; demonstrated PINN-predicted wind fields outperform panel-method estimates that misguide the planner into turbulent high-shear gap regions between obstacles, reducing control effort ~9% vs. a full CFD-driven planner. </li>
</ul>
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
    <li> Designed the full mechanical and electrical system: created a modular CAD model in Fusion 360, fabricated the chassis, and designed a custom PCB housing an ESP32 WROOM 32 daughterboard with MPU9250 9-axis IMU, 6x Time-of-Flight sensors, and a TFT display. </li>
    <li> Integrated LiDAR, IMU, optical encoders, depth camera, and proximity sensors on a Raspberry Pi; calibrated and synchronized all sensor streams for reliable odometry and localization in a GPS-denied environment. </li>
    <li> Deployed GMapping and Hector SLAM, used AMCL for localization and ROS move_base for autonomous navigation; validated the full navigation stack first in Gazebo/RViz simulation and then on physical hardware. </li>
</ul>
<br>
<center>
<a href="https://drive.google.com/drive/folders/1mtaB0RybpWtX2-aTeWSyXiaaacoF5-rM" target="_blank"> Link to Project Poster and Certificate of Completion </a>
</center>
</div>
