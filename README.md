# 🕶️ Aura Guide - Modular AI Vision Platform

Aura Guide is my personal open-source wearable AI platform. The goal is to build smart glasses that help me interact with the real world in natural ways — similar to E.D.I.T.H from Marvel, but built from scratch by me.

Instead of making one fixed device, I designed it as a **modular platform** — you can easily switch between different "AI modes" using simple gestures.

---

## 💡 Project Status

- **Current Stage**: Early prototype / Research + Development phase
- **Fully Self-taught**: All research, planning, and prototyping is done by me alone as a learning project.
- **Main Focus Right Now**: Building a working distance finder and gesture system.

---

## ✨ Key Features (Planned & In Progress)

### 1. 3D Distance Finder (The Smart Tape Measure)
- Uses two cameras (stereo vision) to calculate real-world distances
- Can measure distance from user to object **and** distance between two different objects
- Formula I'm using:  
  **Distance = (focal length × baseline) / disparity**

### 2. Gesture Control (Smart Controller)
- Pinch and throw gestures to "pick & drop" content
- Control TV, PC, laptop, or smart home devices using hand movements
- Plans to use MediaPipe + Wi-Fi / IR transmission

### 3. Explorer Mode (Educational Assistant)
- Real-time object and face recognition
- Can learn new objects/faces on the go
- Useful for identifying circuit parts, plants, obstacles, etc.

### 4. Helping Assistant for Navigation
- Audio feedback about surroundings
- Obstacle detection and guidance (especially useful for visually impaired)

---

## 🛠️ Current Progress

- Working distance measurement prototype (basic stereo vision)
- Object detection research using lightweight AI models
- Full Bill of Materials (BOM) prepared — estimated cost around ₹22,000–23,000
- Gesture logic and modular design planned on paper
- Hardware frame and camera mounting concepts ready

---

## 📊 Bill of Materials (BOM)

**Estimated Total Cost: ₹22,653**

| Component                  | Role                              | Approx. Price |
|---------------------------|-----------------------------------|---------------|
| Raspberry Pi CM5 (4GB)    | Main AI Brain                     | ₹7,999        |
| Waveshare Mini Base (A)   | IO + Camera Hub                   | ₹1,749        |
| Dual IMX219 Cameras       | Stereo Vision Eyes                | ₹3,222        |
| Portronics Luxcell 10K    | Power Supply                      | ₹799          |
| Waveshare 3007-B Fan      | Cooling                           | ₹299          |

---

## 🚀 Future Plans

- Build the physical glasses frame (using 3D printing)
- Integrate gesture recognition (MediaPipe)
- Add voice feedback
- Make the system fully modular so anyone can add new "AI Apps"

This entire project is born from my curiosity and passion for learning hardware + AI. It is my personal "Hardware Lab" where I turn theory into real prototypes.

---

**Made with curiosity by Althaf(The-Overlord-God)**  
Last updated: March 2026
