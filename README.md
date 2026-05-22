<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=transparent&height=120&text=Ikunio&fontSize=52&fontColor=F5F5F7&desc=Robotics%20%7C%20SLAM%20%7C%20Perception%20%7C%20Edge%20AI&descSize=16&descAlignY=75" />
</p>

<p align="center">
  <b>Robotics Algorithm Engineer</b><br/>
  ROS2 · LiDAR Navigation · SLAM · Computer Vision · Edge AI Deployment
</p>

<br/>

---

## Abstract

I focus on the design and implementation of robotic perception and navigation systems, with an emphasis on **ROS2-based autonomy**, **LiDAR localization**, **SLAM**, **vision-based object detection**, and **edge AI deployment**.

My work explores the integration of classical robotic algorithms and modern deep learning models, aiming to build systems that are not only accurate in controlled environments, but also reliable, deployable, and maintainable in real-world robotic platforms.

Currently, my engineering interests include:

- LiDAR-based localization and autonomous navigation
- ROS2 robotic software architecture
- YOLO-based visual perception
- RK3588 / RKNN model deployment
- Point cloud processing and global relocalization
- Multi-sensor fusion for mobile robots

<br/>

---

## Research & Engineering Interests

| Area | Focus |
|---|---|
| Robotic Perception | YOLO, OpenCV, object detection, visual localization |
| LiDAR Navigation | Livox MID-360, point cloud processing, Nav2, localization |
| SLAM & Relocalization | scan matching, global localization, map-to-odom estimation |
| Edge AI Deployment | ONNX, RKNN, TensorRT, model quantization |
| ROS2 Systems | C++, Python, TF tree, lifecycle nodes, robotic middleware |

<br/>

---

## Selected Projects

### RK3588s ONNX to RKNN

A deployment-oriented pipeline for converting ONNX models to RKNN format on RK3588 platforms.  
The project focuses on model conversion, quantization, environment configuration, and NPU inference deployment.

**Keywords:** `RK3588` `RKNN` `ONNX` `Quantization` `Edge AI`

[View Project](https://github.com/Ikunio/RK3588s_onnx2rknn)

<br/>

### RKNN ROS2

A ROS2-based inference package for deploying YOLO models on RK3588 NPU.  
The system connects deep learning inference with robotic middleware, enabling real-time perception in robot applications.

**Keywords:** `ROS2` `YOLOv5` `RKNN` `NPU` `Object Detection`

[View Project](https://github.com/Ikunio/rknn_ros2)

<br/>

### Lidar Nav2 Workspace

A ROS2 autonomous navigation workspace based on Livox MID-360 3D LiDAR.  
The project integrates LiDAR odometry, mapping, localization, navigation, and robot control modules.

**Keywords:** `ROS2` `C++` `Nav2` `LiDAR SLAM` `Livox MID-360`

[View Project](https://github.com/Ikunio/Lidar_nav2_ws)

<br/>

### PyQt5 YOLOv5

A desktop GUI application for YOLOv5-based object detection.  
The project provides a visual interface for model loading, image/video inference, and detection result visualization.

**Keywords:** `Python` `PyQt5` `YOLOv5` `Computer Vision`

[View Project](https://github.com/Ikunio/PyQt5-YOLOv5)

<br/>

---

## Technical Stack

<p align="center">
  <img src="https://img.shields.io/badge/ROS2-Humble-22314E?style=flat-square&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-17-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv5-Detection-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/RKNN-RK3588-6E6E73?style=flat-square" />
  <img src="https://img.shields.io/badge/SLAM-Localization-2C2C2E?style=flat-square" />
</p>

<br/>

---

## Experience

- Algorithm group leader in ROBOCON.
- Developed ROS2-based robotic perception and navigation systems.
- Worked with LiDAR, depth cameras, YOLO models, RKNN deployment, and robotic TF systems.
- Familiar with complete model deployment pipelines:

```text
PyTorch Model
      ↓
ONNX Export
      ↓
Model Quantization
      ↓
RKNN / TensorRT Deployment
      ↓
ROS2 Robotic System Integration
