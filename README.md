<div align="center">

# Unity 6 VR Interactive Sandbox & Medieval Knight Showcase 🛡️🥽

### **VR Locomotion, Grab Physics & 3D Character Animation in Unity 6 (XR Interaction Toolkit 3.3)**

[![Unity 6](https://img.shields.io/badge/Unity-6000.0_LTS-000000?style=for-the-badge&logo=unity&logoColor=white)](https://unity.com/)
[![XR Interaction Toolkit](https://img.shields.io/badge/XR_Interaction_Toolkit-3.3.1-FF6B6B?style=for-the-badge)](#)
[![OpenXR](https://img.shields.io/badge/OpenXR-VR_Standard-00599C?style=for-the-badge)](#)

*An introductory Virtual Reality interactive environment built in Unity 6 demonstrating 6DoF hand presence, physics-based object manipulation, locomotion rigs, and custom textured 3D medieval knight animations.*

</div>

---

## ✨ Overview & Highlights

- 🥽 **Complete XR Origin & Locomotion Setup:** Configured with Unity 6's **XR Interaction Toolkit 3.3.1** Starter Assets, supporting continuous move, teleportation anchors, climb interactables, and poke/gaze UI interactions.
- ⚔️ **Textured 3D Medieval Knight Assets & Skeletal Animations:** Integrates custom AI-generated 3D character meshes (`Meshy_AI` medieval knight OBJ/FBX models) rigged with combat and death animation states.
- 🖥️ **In-Editor XR Device Simulator:** Configured for immediate keyboard-and-mouse VR simulation inside the Unity Editor as well as standalone Meta Quest / OpenXR headset deployment.

---

## 📂 Repository Structure

```text
├── Assets/                 # VR scenes, XR Interaction Toolkit 3.3.1 samples & 3D knight assets
├── Packages/               # Unity 6 package manifest & lockfile
├── ProjectSettings/        # OpenXR & XR Plug-in Management configuration
└── docs/                   # Unity 6 VR task specification PDF
```

---

## 🚀 Running the Project

1. Open **Unity Hub** and add this project directory (`Unity 6000.0.x`).
2. Open the sample VR scene in `Assets/` and press **Play** to test interactions with the **XR Device Simulator** (or a connected OpenXR headset).
