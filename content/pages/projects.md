Title: Projects
Date: 2025-11-05
Status: published

### PX4 Autonomy
<a href="https://github.com/rick-dn/px4_autonomy" class="btn btn-primary mt-3" target="_blank">GitHub</a>

**Project Overview**: px4_autonomy is a lightweight ROS2 interface for PX4 drone offboard control. It provides clean service-based APIs for autonomous flight operations—arm, takeoff, goto, velocity control, and landing—abstracted from the complexity of PX4 messaging. Designed for rapid development of autonomous drone applications on embedded systems like Jetson Orin Nano.
**Future Roadmap**: Vision-based autonomy through modular computer vision nodes: ArUco marker detection and pose estimation (deployed), object detection with YOLO (complete), and upcoming semantic segmentation. Advanced perception via visual SLAM for drift-free navigation, multi-sensor fusion combining GPS/IMU/vision data, and 3D pose estimation for precise object tracking and manipulation tasks. Goal: a production-ready autonomous drone stack balancing performance and accessibility.

### UDL Aakash
**Overview:** UDL Aakash is a production-grade ROS2-PX4 flight controller enabling autonomous drone operations through modular, safety-first architecture.
**Current:** Centralized vehicle management with position control, state machine, continuous PX4 heartbeat, and service-based command interface.
**Next 3 months:** Multi-control modes (velocity, attitude, trajectory), geofencing, battery monitoring, mission execution, and hardware validation on real drones.
**Future:** Vision integration (YOLO, ArUco, 3D reconstruction), SLAM for GPS-denied flight, LLM-powered autonomous agents, and Jetson TX2 deployment.

**Test bed**: sitl: ROS-PX4 Gazebo sim, hitl: PixHawk-f450, vision: Jetson Orin 