# haptic-sensor-reverse-engineering.



Title: Reverse Engineering an Optical Displacement Sensor for Robotics Odometry

Description: In this project, I reverse-engineered a Microsoft Optical Mouse PCB (X01-03410-02) to explore its potential as a low-cost, high-precision Odometry Sensor for autonomous robotics.

Key Engineering Features:

Component Salvage: Identified and mapped two high-cycle micro-switches to be repurposed as collision-detection bumpers.

Optical Flow Analysis: Investigated the 1500+ FPS CMOS sensor for its ability to track movement across diverse textures—a critical component for SLAM (Simultaneous Localization and Mapping).

Power Management: Utilized the existing USB interface to create a stable 5V power bus for the logic board.

Potential AI Application: Feeding the X/Y coordinate data into a Reinforcement Learning model to train a virtual agent on how to navigate physical space based on real-world friction and displacement.
