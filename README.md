## CS330 - Computer Graphics (OpenGL)

#Project Overview

This project demonstrates 3D graphics programming using OpenGL to recreate a realistic environment based off of physical objects.
The scene showcases various computer graphics techniques including realisitic lighting, texture mapping, and interactive camera controls.
---
## Screenshot

<img width="997" height="828" alt="Screenshot 2024-12-22 220523" src="https://github.com/user-attachments/assets/9e6e969c-cc8f-4e18-b9b4-aa7768a5b4d0" />
---
## Features Include

- 3D Transformations: Model, View, and projection matrices for proper 3D rendering
- Camera Systems: Interactive first-person camera with keyboard and mouse controls

---
## Lighting & Shading

- Multiple Light Sources
- Material Properties
---
## Texturing

- 2D Texture Mapping: Applied to all 3D objects for realistic surface apperance
- Texture Filtering
- Texture Coordinates
---
## Advanced Features

- Depth Testing to ensure that the z-buffer correctly allows object occlusion
- Alpha transparency used to enable translucent objects
---
## Technology Used

- OpenGL
- GLFW: Window Management and input handling
- GLAD: OpenGL function loading
- GLM: Mathematics library for graphical use
- stb_image: Texture loading
- C++: Primary Language Used
- Visual Studio: IDE
---
## Setup Instructions

Visual Studio 2019 or later (Windows)
OpenGL 3.3+ compatible graphics card
Git for cloning the repository

Installation

Clone the repository:
bashgit clone https://github.com/Vexatious-777/CS330.git
cd CS330

Open the project:

Launch Visual Studio
Open the .sln solution file
Ensure the project is set to x86 configuration


Build and run:

Build the solution (Ctrl+Shift+B)
Run the project (F5)



Dependencies
All required libraries are included in the project:


Controls

W, A, S, D: Move camera forward, left, backward, right
Mouse Movement: Look around (first-person view)
Scroll Wheel: Zoom in/out
P: Toggle between perspective and orthographic projection
Esc: Exit application
---
## Development Process
This project was developed as part of CS330 Computer Graphics course. The development approach focused on:

Incremental Learning: Starting with basic OpenGL concepts and progressively adding complexity
Modular Design: Creating reusable components for shaders, textures, and geometric primitives
Iterative Refinement: Continuously improving visual quality and performance
---
Key Challenges during development

Lighting Calculations: Implementing proper Phong shading with multiple light sources
Texture Coordination: Ensuring seamless texture mapping across complex 3D objects
Camera Mathematics: Developing smooth, intuitive camera controls using quaternions/matrices
Performance Optimization: Efficient rendering of complex scenes with multiple objects
---
License
This project is created for educational purposes as part of CS330 coursework at SNHU.
