---
layout: page
title: Projects and Competitions
permalink: /projects/
---

<html>
<head>
<style>
#frozen-btn {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 5vh;
}
button {
  border: 0;
  margin: 20px;
  text-transform: uppercase;
  font-size: 20px;
  font-weight: bold;
  padding: 15px 50px;
  border-radius: 50px;
  color: white;
  outline: none;
  position: relative;
}
button:before{
  content: '';
  display: block;
  background: linear-gradient(to left, rgba(255, 255, 255, 0) 50%, rgba(255, 255, 255, 0.4) 50%);
  background-size: 210% 100%;
  background-position: right bottom;
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  bottom:0;
  right:0;
  left: 0;
  border-radius: 50px;
  transition: all 1s;
  -webkit-transition: all 1s;
}
.green {
   background-image: linear-gradient(to right, #25aae1, #40e495);
   box-shadow: 0 4px 15px 0 rgba(49, 196, 190, 0.75);
}
.purple {
   background-image: linear-gradient(to right, #6253e1, #852D91);
   box-shadow: 0 4px 15px 0 rgba(236, 116, 149, 0.75);
} 
.purple:hover:before {
  background-position: left bottom;
}
.green:hover:before {
  background-position: left bottom;
}
#bordering{
  width: 1000px;
  height: 100x;
  padding: 10px;
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

<div id="bordering">
<center>
<img title="bbs_scan_matching_cpu" alt="Alt text" src="/images/3d_bbs.png">
</center>

<center>
<b style="font-size:30px"> bbs_scan_matching_cpu</b> 
</center>
<br>
As part of my EECE5550 Mobile Robotics course's project at Northeastern University, I reproduced a simplified, CPU-only version of the implementation of the 3D-BBS (Branch-and-Bound Scan Matching) algorithm for global localization using LiDAR data. This project aligns 3D LiDAR scans to a voxelized map by exhaustively searching a 4D pose space (x, y, z, yaw) and scoring candidates using voxel occupancy overlap. This algorithm was originally proposed in the 3D-BBS: Global Localization for 3D Point Cloud Scan Matching Using Branch-and-Bound paper.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/bbs_scan_matching_cpu" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>


<div id="bordering">
<center>
<img title="Cruise_Control_System" alt="Alt text" src="/images/Cruise_Control_System.jpg">
</center>

<center>
<b style="font-size:30px"> Cruise_Control_System</b> 
</center>
<br>
As part of our ME5659 Control Systems Course course's project at Northeastern University, we focused on designing and comparing three different controllers: PID, Lead-Lag, and LQR, for regulating the velocity of a Toyota Camry XLE under aerodynamic and rolling resistance forces. 
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/Cruise_Control_System" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<div id="bordering">
<center>
<img title="Sensor Fusion Of GPS And IMU Data For Automotive Dead Reckoning" alt="Alt text" src="/images/NUANCE.jpg">
</center>

<center>
<b style="font-size:30px"> Sensor Fusion Of GPS And IMU Data For Automotive Dead Reckoning</b> 
</center>
<br>
Created custom ROS 2 messages and drivers for GPS and IMU sensors and collected data using the NUANCE autonomous car provided by Northeastern University. Analyzed the IMU's noise characteristics through Allan Variance and calibrated magnetometer by correcting hard and soft iron distortions and error compensation in IMU and GPS data. Compensated for accelerometer bias to estimate the vehicle’s forward velocity, and fused the yaw angle computed from the gyroscope and magnetometer data using a complementary filter to estimate heading for Dead Reckoning with IMU.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/Sensor_Fusion_of_GPS_and_IMU_Data_for_Automotive_Dead_Reckoning" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<div id="bordering">
<center>
<img title="FAST-LIO Loop Closure Test On NUANCE" alt="Alt text" src="/images/LIO_SAM.png">
</center>

<center>
<b style="font-size:30px"> FAST-LIO Loop Closure Test On NUANCE</b> 
</center>
<br>
Collected data in NUANCE autonomous car using the Ouster 3D lidar, VectorNav (VN-100) IMU, and GPS sensors while driving around the streets of Boston. Tested FAST-LIO, FAST-LIO LC, and LIO-SAM on standard datasets as well as on our data, displayed the results for FAST-LIO and FAST-LIO LC, and highlighted challenges faced in LIO-SAM. Compared the results obtained from FAST-LIO and FAST-LIO LC to highlight the advantages of Loop Closure in SLAM algorithms. 
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/FAST_LIO_Loop_Closure_Test_On_NUANCE" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>


<div id="bordering">
<center>
<img title="Pick and Place Using PincherX100 Robot Manipulator" alt="Alt text" src="/images/PincherX100.png">
</center>

<center>
<b style="font-size:30px"> Pick and Place Using PincherX100 Robot Manipulator</b> 
</center>
<br>
Performed pick-and-place task for a cylindrical payload using the PincherX100 robot manipulator. Employed concepts such as forward kinematics and Inverse Kinematics and designed a Trajectory Planner for the end-effector of the arm. Implemented obstacle avoidance along with the normal pick-and-place function of the arm.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/PincherX100_Pick_and_Place" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>



<div id="bordering">
<center>
<img title="Dairy Bike" alt="Alt text" src="/images/db.png">
</center>

<center>
<b style="font-size:30px"> Eyantra Robotics Competition, Theme: Dairy Bike</b> 
</center>
<br>
Secured 3rd place in the Eyantra Robotics Competition 2021 - 2022. Developed a two wheeled bike which uses Linear Quadratic Regulator (LQR) to balance itself. Used State-Space equations and Euler Lagrange method to mathematically model the bike. Designed a custom 4-DOF arm to pick and place the dairy products. Navigated the bike through the arena overcoming various obstacles placed at different points in the entire arena.
<br>
<br>

<center>
<a href="https://drive.google.com/file/d/1yrA_5KhckoPCn6MJgsTdeu6OGA6UzV08/view" target="_blank"> Link to certificate of merit </a>
</center>

<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Jash-Shah/Dairy-Bike-E-Yantra" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<div id="bordering">
<center>
<img title="walle_sim_ros2" alt="Alt text" src="/images/walle_sim_ros2.png">
</center>

<center>
<b style="font-size:30px"> Wall-e-simulation-ros2 </b> 
</center>
<br>
Designed a two-wheeled robot and wrote self-balancing and line-following algorithms for it using Propotional Integral Derivative (PID) controller. Solidworks was used to design the robot. Used ROS 2 Foxy and Gazebo to simulate it.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/Wall-e-simulation-ros2" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<div id="bordering">
<center>
<img title="OptiDepth" alt="Alt text" src="/images/OptiDepth.jpg">
</center>

<center>
<b style="font-size:30px"> OptiDepth </b> 
</center>
<br>
Performed accelerated depth estimation on reflective and transparent surfaces through quantization optimization.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/KunalA18/OptiDepth" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<div id="bordering">
<center>
<img title="obstacle_avoidance" alt="Alt text" src="/images/obs_avd.png">
</center>

<center>
<b style="font-size:30px"> Obstacle Avoidance </b> 
</center>
<br>
Implemented an obstacle avoidance algorithm on a differential drive robot and simulated it using ROS Noetic and Gazebo.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/Obstacle-Avoidance" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<div id="bordering">
<center>
<img title="RRT" alt="Alt text" src="/images/RRT.png">
</center>

<center>
<b style="font-size:30px"> Rapidly Exploring Random Trees (RRT) Algorithm </b> 
</center>
<br>
Implemented the Rapidly Exploring Random Trees (RRT) Algorithm from scratch using Object-Oriented Programming (OOPs) in Python. Created a simulation to visualize the working of the algorithm using Matplotlib. Made some of the parameters dynamic, such as having random start and goal positions each time, and taking the number of obstacles as input from the user within a specific range. Also, devised some parameters, such as the number of iterations required, the number of final waypoints needed, and the total distance traversed, to evaluate the performance of the algorithm.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/RRT" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<div id="bordering">
<center>
<img title="street_racer" alt="Alt text" src="/images/race.png">
</center>

<center>
<b style="font-size:30px"> Street-Racer-2D </b> 
</center>
<br>
Made a gesture controlled 2D car racing game using phaser.js and OpenCV.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/ParthShirole/Street-Racer-2D" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>


<div id="bordering">
<center>
<img title="Wall-E-Sim" alt="Alt text" src="/images/Wall-E-Sim.jpg">
</center>

<center>
<b style="font-size:30px"> Wall-E-Sim </b> 
</center>
<br>
Contributed to enhancing the existing simulations in this repository as well as creating the new self-balancing task. These CoppeliaSim simulations are used as assignments to teach first-year students various concepts like Proportional Integral Derivative (PID) controller tuning, line-following, self-balancing, and maze-solving, as a part of the WallE workshop conducted by the members of the Society Of Robotics And Automation (SRA), VJTI. 
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/SRA-VJTI/Wall-E-Sim" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>


<div id="bordering">
<center>
<img title="lsa" alt="Alt text" src="/images/3D_view_PCB.png">
</center>

<center>
<b style="font-size:30px"> PCB Design LSA </b> 
</center>
<br>
Designed a Printed Circuit Board (PCB) for Line Sensor Array (LSA). It was a basic assignment to get familiar with PCB Designing and KiCAD.
<br>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/PCB_Design_LSA" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>
</center>






