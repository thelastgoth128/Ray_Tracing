# Ray Tracing in C++

A lightweight exploration of ray tracing fundamentals, built while following a small GitHub course.  
This repository documents my journey into computer graphics using modern C++, focusing on rays, intersections, shading, and rendering pipelines.

---

## 📖 Overview
Ray tracing is a rendering technique that simulates how light interacts with objects in a scene.  
Instead of rasterizing triangles, rays are cast from the camera into the scene, and their intersections with geometry determine pixel colors.  
This approach naturally produces realistic effects like **shadows, reflections, and refractions**.

This repo starts with the basics—casting rays into a scene and detecting sphere intersections—and gradually evolves into a more complete renderer with shading, multiple objects, and anti‑aliasing.

---

## 🛠 Features
- Ray–sphere intersection
- Surface normals and basic shading
- Multiple objects in a scene
- Diffuse lighting
- Reflections and recursive rays
- Anti‑aliasing for smoother images
- Modular C++ design for clarity and extensibility

---

## 🚀 Getting Started

### Prerequisites
- A C++17 (or later) compiler
- Basic knowledge of C++ and linear algebra
- Familiarity with Git for cloning and version control

### Build Instructions
```bash
# Clone the repository
git clone https://github.com/your-username/ray-tracing-cpp.git
cd ray-tracing-cpp

# Compile (example using g++)
g++ -std=c++17 -O2 main.cpp -o raytracer

# Run
./raytracer
