<div align="center">

<!-- Hiệu ứng gõ chữ động (Typing Effect) -->
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&pause=1000&color=00FF99&center=true&vCenter=true&width=600&lines=My+Custom+C%2B%2B+Game+Engine;Algorithm-Driven+Architecture;Built+from+Scratch!" alt="Typing SVG" />

**A low-level, math-focused Game Engine built for learning and experimenting.**

<!-- Huy hiệu màu sắc (Badges) -->
![C++](https://img.shields.io/badge/C++17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white)
![GLFW](https://img.shields.io/badge/GLFW-Windows_/_Linux-orange?style=for-the-badge)
![ImGui](https://img.shields.io/badge/UI-Dear_ImGui-FF69B4?style=for-the-badge)

<br>

<!-- Demo GIF (Phong cách Sigma/Dark-mode Low-level Rendering) -->
<a href="#">
  <img src="https://i.pinimg.com/originals/c7/ab/35/c7ab35cb8dc2b2d650b2986427d110cf.gif" alt="Engine Core Visualization" width="800" style="border-radius: 10px; border: 1px solid #333; box-shadow: 0 0 20px rgba(0, 255, 153, 0.2);"/>
</a>

</div>

---

## 💡 The Vision (Learning Project)
> *"Understanding the roots, not just using the tools."*

Hi! I have a background in **Competitive Programming (Algorithms & Data Structures)**. I started this project to transition from solving algorithmic puzzles to building real-time, low-level systems. 

Instead of jumping straight into commercial engines like Unity or Unreal, I wanted to understand exactly what happens between the CPU and GPU. Everything here—from linear algebra to the rendering pipeline—is built from scratch to deeply understand the **"Why"** and **"How"**.

## 🚀 Highlighted Tech & Features

### 📐 1. Custom Math Foundation
No external math libraries (like GLM). I wrote my own custom math headers:
- `Mat4`, `Vec3`, `Vec4` implementations.
- Model-View-Projection (MVP) matrix calculations.
- Deep focus on **Linear Transformations** & **Homogeneous Coordinates**.

### 🎨 2. Rendering Pipeline
- **Batch Rendering:** Optimizing draw calls by packing multiple quads into a single Vertex Buffer.
- **Index/Vertex Buffers:** Manual memory layout and stride calculations.
- **Orthographic Projection:** Currently set up for 2D UI/World rendering (Perspective 3D coming next).

### 🛠️ 3. Immediate Mode Editor
- Integrated **Dear ImGui** to build an in-engine toolset.
- Real-time manipulation of Camera, Transformations, and Shader Uniforms without recompiling.

## 🗺️ Progress & Roadmap

- [x] **Phase 1:** Windowing & Context (`GLFW`, `GLEW`).
- [x] **Phase 2:** Shaders & Uniforms setup.
- [x] **Phase 3:** Textures & Alpha Blending.
- [x] **Phase 4:** Mathematics (Vectors, Matrices, Projections).
- [ ] **Phase 5:** Framebuffers & Post-Processing (Bloom, Blur).
- [ ] **Phase 6:** 3D Perspective Camera & Lighting.
- [ ] **Phase 7:** Algorithmic Physics & Collision Detection (AABB, Quadtrees).

## ⚙️ How to Build
*(Instructions will be added soon. The project uses standard C++17 and CMake/Premake build systems).*

---
<div align="center">
  <i>Developed with ❤️ and C++ by a Competitive Programmer diving into Graphics.</i>
</div>
