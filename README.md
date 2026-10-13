# AR-Based Smart Machine Monitoring System Using Unity

> An Augmented Reality-based industrial visualization system for viewing a 3D industrial plant, machines, and machine animations through a mobile application.

## 📌 Project Overview

The **AR-Based Smart Machine Monitoring System** is an IIC project developed to provide an AR-based visualization of an industrial plant and its machines through a mobile application.

The implementation combines **QR/reference target recognition, Unity, Vuforia, 3D plant models, Blender-based model processing and animation, and Android APK development**.

The application workflow is:

```text
QR / Reference Target
        ↓
Mobile Camera
        ↓
Vuforia Target Recognition
        ↓
Unity AR Environment
        ↓
3D Industrial Plant
        ↓
Machine Visualization
        ↓
Machine Animation
        ↓
Android APK
```

## 🎯 Objectives

- Develop an AR-based visualization of an industrial plant.
- Display 3D machines and plant components through a mobile camera.
- Use Vuforia for AR camera and target recognition.
- Optimize a large industrial 3D model for Unity/mobile use.
- Add animation to represent machine movements and operating conditions.
- Import Blender-created/modified animation into Unity.
- Build and test the final application as an Android APK.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Unity | AR application development and 3D scene integration |
| Vuforia | AR camera and target recognition |
| Blender | 3D model processing, optimization and animation |
| C# | Unity scripting |
| Android | Mobile application deployment |
| 3D Models | Industrial plant and machine visualization |
| QR / Reference Target | AR reference for target recognition |

## ⚙️ Implementation Workflow

### 1. QR Code and Camera Initialization

The mobile camera is used to scan the required QR/reference target. After recognition, the Unity application opens the required AR environment using Vuforia.

### 2. 3D Model Display

The recognized target acts as the reference for placing the corresponding 3D plant model and machine visualization in the real environment.

### 3. Industrial Plant Environment

The required machines and plant components are positioned according to the intended industrial plant arrangement.

### 4. Machine Animation

Animation parameters are added to represent machine movements and operating conditions.

### 5. Large 3D Model Management

The original industrial 3D model was approximately **5 GB**, which created difficulties during import and execution. The model was therefore optimized and compressed before Unity integration.

### 6. Blender Processing

Blender was used to process and reduce the model size. The optimized model was then imported into Unity, with scaling adjusted for the AR environment.

### 7. Colouring

Required colours were applied to machines and plant components to improve identification and clarity in the AR visualization.

### 8. Conveyor and Smart Pouring Machine Animation

Animation work was performed for the conveyor and smart pouring machine. The smart pouring machine position was adjusted according to the plant arrangement and the conveyor was extended as required.

### 9. Blender → Unity Animation Integration

The completed animation was imported into Unity and checked to verify that machine movements were transferred correctly.

### 10. Android APK

The completed Unity project was converted into an Android APK and tested on a mobile device for AR camera operation, target recognition and 3D plant visualization.

## 🧩 System Architecture

```text
                  ┌──────────────────────┐
                  │ QR / Reference Target│
                  └──────────┬───────────┘
                             ↓
                  ┌──────────────────────┐
                  │    Mobile Camera     │
                  └──────────┬───────────┘
                             ↓
                  ┌──────────────────────┐
                  │       Vuforia        │
                  │  Target Recognition  │
                  └──────────┬───────────┘
                             ↓
                  ┌──────────────────────┐
                  │       Unity          │
                  │    AR Environment    │
                  └──────────┬───────────┘
                             ↓
              ┌──────────────┴──────────────┐
              ↓                             ↓
       ┌──────────────┐              ┌──────────────┐
       │ 3D Plant     │              │   Machine    │
       │ Model        │              │  Animation   │
       └──────────────┘              └──────────────┘
              │                             │
              └──────────────┬──────────────┘
                             ↓
                  ┌──────────────────────┐
                  │ Android AR Application│
                  └──────────────────────┘
```

## 🧊 3D Model Optimization

The project encountered a large 3D model of approximately **5 GB**. This affected import and application execution.

The model was processed using Blender before Unity integration:

```text
Large Industrial 3D Model
          ↓
      Blender
          ↓
 Model Optimization
          ↓
 Scaling Adjustment
          ↓
      Unity Import
          ↓
       AR Testing
```

## 🎞️ Animation Workflow

```text
Industrial Model
       ↓
Blender Animation
       ↓
Animation Modification
       ↓
Unity Import
       ↓
Animation Verification
       ↓
AR Integration
```

## 📸 Project Screenshots

Place the project screenshots in the `Screenshots/` directory.

### Final AR Visualization

![Final AR Visualization](Screenshots/final-ar-visualization.jpg)

### Unity Development Environment

![Unity Development](Screenshots/unity-development.jpg)

### Industrial Plant Top View

![Industrial Plant Top View](Screenshots/plant-top-view.jpg)

### AR Reference Target

![AR Reference Target](Screenshots/ar-target.jpg)

### Machine Animation

![Machine Animation](Screenshots/machine-animation.jpg)

## 📱 Android Application

The final Unity application was prepared as an Android APK and tested on a mobile device.

Testing covered:

- AR camera operation
- Target recognition
- 3D plant visualization
- Machine visualization
- Machine animation
- Integrated AR workflow

The APK/demo should be shared through the project's release or external demo link rather than committing unnecessarily large binary files to the repository.

## 🎥 Demo

Add the project demonstration video link here:

**Demo:** `ADD_YOUR_DEMO_LINK_HERE`

## 📂 Repository Structure

```text
AR-Smart-Machine-Monitoring-System/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.md
│
├── UnityProject/
│   ├── Assets/
│   │   ├── Scenes/
│   │   ├── Scripts/
│   │   ├── Models/
│   │   ├── Animations/
│   │   ├── Materials/
│   │   ├── Textures/
│   │   └── Vuforia/
│   ├── Packages/
│   └── ProjectSettings/
│
├── Blender/
│   ├── Models/
│   └── Animations/
│
├── Screenshots/
│   ├── final-ar-visualization.jpg
│   ├── unity-development.jpg
│   ├── plant-top-view.jpg
│   ├── ar-target.jpg
│   └── machine-animation.jpg
│
├── Documentation/
│   ├── Project-Report.pdf
│   └── Project-Presentation.pdf
│
└── Demo/
    └── README.md
```

## 👥 Project Team

| Member | Role |
|---|---|
| Ashai. P | Team Member |
| Bharathi. B | Team Member |
| Nisha. S | Team Member |
| Suryaprakash. K | Team Member |

### Guide

**Kaviya A.**  
Assistant HOD

## 🎓 Project Information

**Project Type:** IIC Project  
**Domain:** Augmented Reality / Industrial Visualization  
**Platform:** Android  
**Primary Development Environment:** Unity

## 🚀 Future Scope

The current project documentation does not specify a detailed future-work list. Potential extensions should therefore be added only after they are implemented or formally included in the project documentation.

## 📄 License

This repository is intended for academic and educational project documentation.

Before redistributing project assets, 3D models, Vuforia-related assets, or other third-party/proprietary material, verify that you have the necessary permission or license.

---

**Developed as an academic IIC project.**
