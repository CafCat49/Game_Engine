# Game Engine (OpenGL)

A custom game engine built in **C++ using OpenGL**.  
This project explores the fundamentals of real-time graphics programming, rendering pipelines, and engine architecture.

The goal of the project is to better understand how modern game engines work internally by implementing core graphics systems from scratch.

---

## Features

- OpenGL based rendering pipeline
- Shader system for GPU programs
- Vertex buffer and vertex array management
- Window and graphics context creation
- Basic rendering loop
- Transformations and scene rendering

---

## Tech Stack

**Language**
- C++

**Graphics**
- OpenGL

**Libraries**
- GLFW (window/context management)
- GLAD (OpenGL loader)
- GLM (math library)
- OpenAL (sound library)

---

## How It Works

The engine initializes a window and OpenGL context, loads shaders, and enters a rendering loop.

Typical flow:

1. Create window and graphics context
2. Load shaders
3. Create vertex buffers
4. Send data to GPU
5. Render objects each frame

---

## Learning Goals

This project was built to explore:

- real-time graphics programming
- OpenGL rendering pipelines
- GPU data transfer
- shader programming
- engine architecture fundamentals

---

## Building the Project

Clone the repository, and build using your preferred C++ build system or IDE.
I used QTCreator.

Requirements:

- C++17 or newer
- OpenGL
- GLFW
- GLAD
- GLM
- OpenAL

---

## About

Created by **Christina Andaloro Håpnes**.

This project is part of my exploration into **graphics programming and game engine development**.
