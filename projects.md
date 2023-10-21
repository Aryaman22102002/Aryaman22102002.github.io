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






