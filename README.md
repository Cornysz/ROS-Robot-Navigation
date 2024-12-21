# Avoidance of Obstacle for Autonomous ROS-Based Robots

This repository showcases the design and implementation of an advanced autonomous robot capable of real-time obstacle avoidance. Using **Robot Operating System (ROS)** and **Gazebo simulation**, this project combines cutting-edge algorithms with a modular framework to enable efficient, adaptable, and robust navigation in dynamic environments. Whether you're an enthusiast or a professional, this project offers valuable insights into the future of robotics.

---

## 🤝 Acknowledgments

Special thanks to **Ika Candradewi, S.Si., M.Cs.**, for her invaluable guidance and support throughout this project. This project was created and developed by:
- **Raghda Hassa Parardhya Cornika** (23/511502/PA/21810)
- **Ali Rabbani Rasyidin Baadilla** (23/516139/PA/22057)
- **Manafad Aulia Lananggalih** (23/511416/PA/21790)

---

## 🚀 Project Overview

In a world increasingly reliant on autonomous systems, this project stands out by addressing one of the most critical challenges: obstacle avoidance. By simulating and testing a differential drive robot equipped with advanced sensing and motion planning, we present a scalable solution that bridges theoretical robotics and practical applications.

### Key Features
- **Real-time Obstacle Avoidance**: Seamlessly adapts to obstacles using dynamic sensor data.
- **ROS Integration**: Ensures efficient and reliable communication between software components.
- **Gazebo Simulation**: Provides a realistic environment to rigorously test and validate the system.
- **Differential Drive Mechanism**: Offers precision and simplicity in movement control.
- **Modular Design**: Facilitates ease of maintenance, upgrades, and scalability.

---

## 📜 Objectives
1. Develop a responsive **Obstacle Avoidance Algorithm** leveraging real-time sensor feedback.
2. Create a fully integrated system combining hardware models and robust software frameworks.
3. Test and refine the robot in diverse simulated scenarios to ensure reliability.
4. Establish a solid foundation for future innovations, including multi-robot systems and real-world deployment.

---

## 🛠️ Implementation

### Environment Setup
1. **Simulation Environment**:
   - Built in **Gazebo** with customizable static and dynamic obstacles.
   - Designed to mimic real-world scenarios for rigorous testing.
2. **Robot Model**:
   - Differential drive architecture modeled with URDF for flexibility and precision.

### Software Stack
- **ROS Noetic**: Central communication framework.
- **Gazebo**: Physics-accurate simulation for robust testing.
- **Python**: Powering the core algorithms.
- **Ubuntu 20.04**: Reliable and consistent development environment.

---

## 📊 Testing and Evaluation

### Benchmarks
- **Static Obstacle Course**: Evaluates performance in environments with stationary barriers.
- **Dynamic Obstacle Course**: Tests adaptability to moving obstacles.
- **Complex Environments**: Assesses navigation in tight and densely packed spaces.

### Metrics
- **Success Rate**: Percentage of collision-free navigation attempts.
- **Average Time to Goal**: Measures efficiency in reaching objectives.
- **Path Optimality**: Evaluates how closely the path follows the theoretical minimum.

---

## 📈 Results

Through rigorous testing, the robot demonstrated:
- Consistent obstacle detection and avoidance in diverse scenarios.
- Adaptive and smooth motion planning, even in dynamically changing environments.
- High success rates and efficient performance, reinforcing the system's reliability.

---

## 🌟 Future Directions

- **Enhanced Sensors**: Incorporate 3D LiDAR and stereo cameras for richer environmental mapping.
- **Advanced Path-Planning**: Integrate algorithms like A* or Dynamic Window Approach (DWA) for optimized navigation.
- **Multi-Robot Collaboration**: Explore swarm robotics for complex tasks.
- **Real-World Deployment**: Transition to physical robots and test in non-ideal conditions.

---

## 📚 References
- [ROS Wiki](http://wiki.ros.org)
- Bekey, G. A., "Autonomous Robots," MIT Press.
- Koenig, N., & Howard, A., "Design and Use Paradigms for Gazebo."
