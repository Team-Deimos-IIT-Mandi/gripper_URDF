# 🤖 URDF for Mars Rover Gripper Assembly

This repository contains the URDF (Unified Robot Description Format) files generated from the SolidWorks assembly of the **gripper subsystem** in our Mars Rover project. These files are designed for use in ROS-based simulation environments like RViz and Gazebo.

## 🔍 What is URDF?

URDF is an XML-based format used to describe a robot’s physical structure, joints, and visual geometry. It enables simulation, motion planning, and visualization without needing the physical hardware.

## 🔧 How These Files Were Created

The gripper assembly was modeled and mated in SolidWorks, then exported using the official URDF Exporter plugin. The process included:
- Defining joint types and coordinate systems
- Assigning link hierarchies
- Exporting STL meshes and URDF structure

## 📁 Repository Contents

- `/meshes`: STL files for each gripper component
- `robot.urdf`: URDF file describing the gripper's structure and joints
- Optional config/launch files for ROS integration

## 🚀 Use Cases

- Simulate gripper motion in Gazebo
- Visualize joint behavior in RViz
- Integrate with ROS control packages
- Test grasping kinematics and joint limits

---
