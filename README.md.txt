# 🕶️ Aura Guide: The Modular AI Vision Platform

**Aura Guide** is a wearable, open-source AI platform built for curiosity and education. It transforms the world around you into a playground for data and interaction. 

Instead of a single-purpose device, Aura Guide is designed with a **Modular Core**—allowing you to switch between different "AI Apps" like object detection, 3D distance finding, and smart-home control with a simple gesture.

---

## 💡 Project Status & Learning Journey
> **Note:** This project is born entirely out of personal interest and a passion for learning.

* **Experimental Nature:** All technical details and designs are collected from extensive online research. I am a self-taught learner, and this project serves as my "Hardware Lab" to turn theoretical knowledge into a physical prototype.
* **Highly Modular:** This isn't just one gadget; it's a platform. It can be modified for anything from simple distance tracking to complex AI interactions.
* **Current Research Goals:** I am currently exploring:
    * **Distance Logic:** Calculating distance from camera-to-object and the distance between two different objects in 3D space using stereo-geometry.
    * **Gesture Interaction:** Using AI to detect hand pinches to "Pick & Drop" digital images or control a TV via Wi-Fi/IR.
    * **Theoretical Prototyping:** Learning how to map software logic onto hardware without prior professional experience.

---

## 🛠️ One Device, Many Modes
The Aura Guide system is built to handle various "Curiosity Projects" in one single frame:

### 🏠 1. The Smart Controller (TV & PC Control)
* **Function:** Point and gesture to control your TV volume or "Pick & Drop" images from your glasses to your PC desktop.
* **Tech:** Gesture mapping + Wi-Fi Sockets / IR transmission.

### 📏 2. The 3D Tape Measure (Distance Finder)
* **Function:** Uses stereo-triangulation ($Distance = \frac{f \times B}{d}$) to calculate:
    1.  The distance between the camera and a target object.
    2.  The physical distance between two separate objects in the frame.
* **Tech:** Dual-Eye (CSI0 & CSI1) depth geometry.

### 🎓 3. The Explorer (Educational AI)
* **Function:** Identifies parts on a circuit board, types of plants, or common objects and displays their names in your HUD.
* **Tech:** Real-time YOLOv11 object detection.

---

## 📊 Bill of Materials (BOM)
**Total Estimated Build Cost:** ₹22,652.98  

| Component | Role | Unit Price (Est.) |
| :--- | :--- | :--- |
| **Raspberry Pi CM5** | The Neural Processor (4GB/16GB) | ₹7,999 |
| **Waveshare Mini Base (A)** | IO Hub / Camera Connectivity | ₹1,749 |
| **Dual IMX219 Cameras** | Stereo Vision "Eyes" | ₹3,222 |
| **Portronics Luxcell 10K** | 22.5W Mobile Power Supply | ₹799 |
| **Waveshare 3007-B Fan** | Active Thermal Management | ₹299 |

---

