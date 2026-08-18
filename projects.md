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
<img title="Whole-Body Control Extension for Convex MPC Quadruped Locomotion" alt="Alt text" src="/images/wbc.png">
</center>

<center>
<b style="font-size:30px"> Whole-Body Control Extension for Convex MPC Quadruped Locomotion</b> 
</center>
<br>
<ul id="left">
    <li> Extended a convex MPC locomotion stack for the Unitree Go2 quadruped in MuJoCo with a custom whole-body contact-force controller. </li>
    <li> Formulated a real-time QP over joint torques and contact forces using OSQP and Pinocchio, enforcing rigid-body dynamics, friction pyramid constraints, and torque limits, cutting friction-cone violations from 92.5% to 0% on low-friction surfaces while solving in 1.3 ms against a 5 ms real-time budget. </li>
    <li> Extended the controller with an event-triggered residual PPO correction, trained via imitation learning from the MPC controller's own reference trajectories, activating only on detected disturbance to cut peak roll by 22-25% under lateral pushes with under 1.5% compute overhead and zero regression to nominal walking. </li>
</ul>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/go2-convex-mpc" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>

<center>

<div id="bordering">
<center>
<img title="POMDP Navigation in MiniGrid" alt="Alt text" src="/images/pomdp.jpg">
</center>

<center>
<b style="font-size:30px"> POMDP Navigation in MiniGrid</b> 
</center>
<br>
<ul id="left">
    <li> Compared POMCP (online POMDP planning) against recurrent PPO and A2C with LSTM across 5 MiniGrid environments of increasing complexity. </li>
    <li> Recurrent PPO solved all 5 environments including a 6-room layout while POMCP degraded on larger tasks due to exponential belief space growth. </li>
    <li> Identified LSTM memory, exploration bonuses, and correct action-space design as jointly necessary for success in multi-room POMDPs. </li>
</ul>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Sairamzz/RL_MiniGrid/tree/main" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>


<center>

<div id="bordering">
<center>
<img title="Camera Lidar Temporal Calibration" alt="Alt text" src="/images/Camera_Lidar_Temporal_Calibration.png">
</center>

<center>
<b style="font-size:30px"> Camera Lidar Temporal Calibration</b> 
</center>
<br>
<ul id="left">
    <li> Built an offline temporal calibration pipeline for camera-LiDAR time synchronization on the Hunter robot, as part of my EECE7150 Autonomous Field Robotics course project at Northeastern University. </li>
    <li> Constructed a cross-modal alignment metric using projected LiDAR points scored against Canny edge distance transforms, then estimated the inter-sensor time offset via Powell optimization and dense grid search, recovering a consistent ~73 ms offset. </li>
    <li> Extended to joint 7-DOF optimization over temporal offset and extrinsic parameters using IMU pre-integration for motion compensation, and validated alignment using LiDAR-to-image projection overlays. </li>
</ul>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/rituraj-navindgikar/camera-lidar-calibration" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>



<center>

<div id="bordering">
<center>
<img title="3D Reconstruction Using Structure-from-Motion" alt="Alt text" src="/images/3D_Reconstruction_Using_Sfm.png">
</center>

<center>
<b style="font-size:30px"> 3D Reconstruction Using Structure-from-Motion</b> 
</center>
<br>
<ul id="left">
    <li> Built a complete incremental Structure-from-Motion pipeline from scratch to recover sparse 3D structure and camera poses from 24 images of a Buddha statue, as part of my EECE7150 Autonomous Field Robotics course project at Northeastern University. </li>
    <li> Implemented SIFT feature extraction, RANSAC-based Essential matrix estimation, and cheirality-based pose recovery, then triangulated points and extended the map incrementally via PnP. </li>
    <li> Applied global bundle adjustment using GTSAM with Huber robust loss, reducing mean reprojection error from 1.28 px to 0.55 px, a 57% improvement. </li>
</ul>
<br>
<div id="frozen-btn">
<center>
   <a href="https://github.com/Aryaman22102002/3D_Reconstruction_Using_Sfm" target="_blank">
   <button class="green">Checkout</button>
   </a>
</center>
</div>
<br>
</div>

<br>
<br>


<center>

<div id="bordering">
<center>
<img title="bbs_scan_matching_cpu" alt="Alt text" src="/images/3d_bbs.png">
</center>

<center>
<b style="font-size:30px"> BBS Scan Matching Cpu</b> 
</center>
<br>
<ul id="left">
    <li> Reimplemented a simplified, CPU-only version of 3D-BBS (Branch-and-Bound Scan Matching, ICRA 2024) for training-free global LiDAR localization, as part of my EECE5550 Mobile Robotics course project at Northeastern University. </li>
    <li> Built a voxel map using a spatial hash table, defined a 4D search space (x, y, z, yaw), and implemented hierarchical Branch-and-Bound search with a max-priority queue for candidate pruning. </li>
    <li> Evaluated on KITTI Sequence 00, achieving under 5 m ATE and under 1-degree AOE across perturbed and fake initializations. </li>
</ul>
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
<b style="font-size:30px"> Cruise Control System</b> 
</center>
<br>
<ul id="left">
    <li> Designed and simulated a longitudinal cruise control system for a Toyota Camry XLE using MATLAB and Simulink, as part of our ME5659 Control Systems course project at Northeastern University. </li>
    <li> Modeled vehicle dynamics including aerodynamic drag, rolling resistance, and drivetrain forces from real-world specifications. </li>
    <li> Designed and compared PID, LQR, and lead-lag controllers, achieving 1.59% overshoot with PID while identifying LQR's steady-state error and lead-lag's degraded performance under nonlinear dynamics, motivating optimization-based control (NMPC) as the natural next step for handling plant nonlinearities at higher speeds. </li>
</ul>
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
<ul id="left">
    <li> Collected GPS and IMU data using the NUANCE autonomous car provided by Northeastern University to perform automotive dead reckoning. </li>
    <li> Developed custom ROS 2 message types and drivers for the VN-100 IMU and GPS, and performed magnetometer hard-iron and soft-iron calibration via SVD-based ellipse fitting. </li>
    <li> Fused gyroscope-integrated yaw with corrected magnetometer yaw via a Butterworth complementary filter, and estimated forward velocity via zero-velocity-update-corrected accelerometer integration to reconstruct the full vehicle trajectory, validated against GPS UTM ground truth. </li>
</ul>
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
<ul id="left">
    <li> Collected a real-world urban LiDAR-inertial dataset aboard the NUANCE autonomous car, driving a loop through the streets of Boston near Northeastern's EXP Building. </li>
    <li> Attempted to run LIO-SAM on the collected data; encountered a blocking challenge, as LIO-SAM requires an external 9-DOF IMU with time-synchronized timestamps, which could not be resolved using the LiDAR's internal 6-DOF IMU. </li>
    <li> Successfully ran FAST-LIO (tightly-coupled iEKF-based LiDAR-inertial odometry) on the custom dataset, then deployed FAST-LIO-LC, an open-source loop-closure extension, which substantially reduced trajectory drift and improved global consistency versus the baseline. </li>
</ul>
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
<ul id="left">
    <li> Programmed a PincherX100 4-DOF robot arm in MATLAB to autonomously pick and place a cylindrical payload using analytical kinematics. </li>
    <li> Derived forward kinematics analytically using DH parameters, and solved inverse kinematics numerically via iterative Jacobian methods for arbitrary end-effector poses. </li>
    <li> Designed a joint-space trajectory planner using linear interpolation for smooth, singularity-avoiding motion, with a collision-avoidance constraint routing the arm around a cylindrical obstacle in the workspace. </li>
</ul>
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
<ul id="left">
    <li> Designed and simulated a two-wheeled dairy delivery robot in CoppeliaSim (CAD in Fusion 360), equipped with a custom 4-DOF arm, navigating an arena with slopes, speed breakers, sharp turns, and curved paths. </li>
    <li> Performed complete mathematical modeling in GNU Octave using Euler-Lagrange dynamics, deriving a linearized state-space model and designing an LQR controller to stabilize the two-wheeled platform. </li>
    <li> Implemented path following via waypoint interpolation and FK/IK for the 4-DOF arm, with custom Lua logic handling dynamic pickup and dropoff commands issued at runtime; placed 3rd out of 242 teams. </li>
</ul>
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
<ul id="left">
    <li> Designed and simulated a two-wheeled self-balancing and line-following robot in Gazebo using ROS 2, modeling the robot CAD in SolidWorks and exporting it as a URDF. </li>
    <li> Implemented and manually tuned PID controllers for self-balancing (inner loop) and line-following (outer loop) independently, then integrated both into a combined controller. </li>
    <li> Validated the full combined behavior in Gazebo/RViz simulation. </li>
</ul>
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
<ul id="left">
    <li> Investigated post-training quantization strategies to deploy monocular depth estimation models (MirrorNet, GDNet) on the OAK-D embedded hardware platform. </li>
    <li> Applied FP32-to-FP16 quantization, achieving a 69% reduction in model memory footprint and a 50% increase in inference throughput, enabling real-time depth estimation on the OAK-D. </li>
    <li> Extended the quantization pipeline to INT8 precision, systematically analyzing the accuracy-latency trade-off to characterize the limits of aggressive quantization on resource-constrained hardware. </li>
</ul>
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
