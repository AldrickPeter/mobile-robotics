---
layout: default
title: Wolf and Rabbit
---

<div class="hero-side-images">
  <img src="assets/images/wolf.avif" alt="Wolf" class="side-image left-image">
  <div class="hero-center">
    <h1>Wolf and Rabbit</h1>
    <p class="hero-subtitle">
      A ROS 2 multi-robot pursuit project using two TurtleBots, vision sensing, and distance measurement.
    </p>
  </div>
  <img src="assets/images/rabbit.avif" alt="Rabbit" class="side-image right-image">
</div>

## 1. Link to our GitHub Pages
[Visit our GitHub Pages site](https://aldrickpeter.github.io/mobile-robotics/)

## 2. 7-character short hash of our commit
`{{ site.github.build_revision | slice: 0, 7 }}`

## Project Description
Our project, **Wolf and Rabbit**, uses two TurtleBot robots to perform a pursuit scenario.

## Main Features
- **ROS 2** for communication and robot control
- **Vision sensors** for target detection and tracking
- **Distance sensors** for measuring relative distance
- Two TurtleBots interact as:
  - **Wolf**: detects and chases the rabbit
  - **Rabbit**: acts as the moving target

This project demonstrates multi-robot interaction, perception, and autonomous pursuit behavior in a ROS 2 environment.

## GitHub Repository
[mobile-robotics repository](https://github.com/AldrickPeter/mobile-robotics)