# ⚙️ [Tên Engine của bạn] Engine 

![C++](https://img.shields.io/badge/C++-17%2B-blue.svg?style=for-the-badge&logo=c%2B%2B)
![OpenGL](https://img.shields.io/badge/OpenGL-3.3%2B-5586A4.svg?style=for-the-badge&logo=opengl)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgray.svg?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

> A custom, high-performance Game Engine built from scratch in C++, focusing on low-level architecture, custom mathematical foundations, and an optimized graphics pipeline.

## 🧠 About The Project

Được phát triển bởi một lập trình viên có nền tảng thuật toán thi đấu (Competitive Programming), Engine này không sử dụng các high-level abstractions có sẵn mà đi sâu vào bản chất toán học và hệ thống. 

Mục tiêu cốt lõi của project là kiểm soát 100% vòng đời của dữ liệu từ CPU xuống GPU, tự xây dựng thư viện Toán học (Linear Algebra) và tối ưu hóa Render Pipeline.

### ✨ Highlighted Features
- **Custom Math Library:** Tự xây dựng cấu trúc `Mat4`, `Vec3`, xử lý trơn tru ma trận Model-View-Projection (MVP) và Orthographic/Perspective Projection mà không phụ thuộc GLM.
- **Optimized 2D/3D Batch Rendering:** Thuật toán gom nhóm dữ liệu (Batching) giúp giảm thiểu tối đa số lượng Draw Calls, tối ưu hóa băng thông CPU-GPU.
- **Immediate Mode GUI Editor:** Tích hợp **Dear ImGui** để tạo môi trường Debug thời gian thực, điều khiển Camera và Inspector trực quan.
- **Algorithm-Driven Architecture:** Áp dụng các cấu trúc dữ liệu và thuật toán tối ưu từ Competitive Programming vào quản lý bộ nhớ và vòng lặp Game (Game Loop).

## 🛠️ Architecture & Tech Stack
- **Core Language:** `C++` (Modern C++)
- **Graphics API:** `OpenGL`
- **Windowing & Input:** `GLFW`
- **UI / Editor:** `Dear ImGui`

## 🚀 Getting Started

### Prerequisites
- C++17 Compiler (MSVC, GCC, or Clang)
- CMake (3.15+) hoặc Premake

### Building the Engine
```bash
# Clone the repository and submodules
git clone --recursive [https://github.com/yourusername/YourEngineName.git](https://github.com/yourusername/YourEngineName.git)

# Generate project files and build
cd YourEngineName
# (Thêm lệnh build của bạn vào đây, ví dụ: vendor\bin\premake\premake5.exe vs2022)
