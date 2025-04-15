# Autonomous Robot
## Abstract
This project focuses on the **development and implementation** of an **autonomous navigation system** utilizing a **Velodyne LiDAR sensor**, integrated within the **ROS (Robot Operating System)** framework. This system is designed to enable **precise and efficient navigation** for autonomous vehicles by leveraging advanced modules in **perception**, **localization**, **path planning**, and **control**. The **perception component** employs the **Advanced LOAM (ALOAM)** algorithm to process raw LiDAR data, generating a detailed **point cloud map** of the surrounding environment. This map is then utilized by the **Normal Distribution Transform (NDT)** module in the **localization component** to **accurately estimate** the vehicle’s position in real time. For **path planning**, the system incorporates the **Pure Pursuit algorithm** to compute the **optimal path** based on the vehicle's current pose and the target trajectory. This module determines the necessary **steering angles** and **velocity** to follow the planned path effectively. Finally, the **control component**, interfaced via the **ROS-Canoe bridge**, executes the **planned motion** by sending commands to the vehicle’s **actuators**, ensuring **smooth and accurate movement**. This comprehensive architecture demonstrates a **robust and modular pipeline** for autonomous systems, ensuring **reliable**, **adaptive**, and **intelligent vehicle guidance** in **dynamic environments**.
## Introduction
### 🧭 System Architecture

The diagram below illustrates the pipeline for building an **autonomous robot** using a **Velodyne LiDAR sensor** within the **ROS framework**.

Every autonomous system is typically divided into four key modules:

1. **Perception**
2. **Localization**
3. **Path Planning**
4. **Control**

Each of these modules plays a **critical role** in the autonomous navigation process, by transforming and utilizing data to **guide the vehicle effectively and safely**.


![image](https://github.com/user-attachments/assets/fec28680-ca03-4894-9f57-2a36d6eb39d0)
