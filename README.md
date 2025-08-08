# CS330 - Computer Graphics (OpenGL)

This project demonstrates 3D graphics programming using OpenGL to recreate a realistic environment based on physical objects. The scene showcases various computer graphics techniques including realistic lighting, texture mapping, and interactive camera controls.

## Screenshot

<img width="997" height="828" alt="3D Scene Recreation" src="https://github.com/user-attachments/assets/9e6e969c-cc8f-4e18-b9b4-aa7768a5b4d0" />

## Features Implemented

### Core 3D Graphics
- **3D Transformations**: Model, view, and projection matrices for proper 3D rendering
- **Interactive Camera System**: First-person camera with keyboard and mouse controls

### Lighting & Shading
- **Multiple Light Sources**: Dynamic lighting from various positions
- **Material Properties**: Realistic surface materials with varying properties

### Texturing
- **2D Texture Mapping**: Applied to all 3D objects for realistic surface appearance
- **Texture Filtering**: Optimized visual quality through proper filtering
- **Texture Coordinates**: Precise UV mapping for seamless texture application

### Advanced Features
- **Depth Testing**: Z-buffer implementation ensuring correct object occlusion
- **Alpha Transparency**: Support for translucent objects and realistic glass effects

## Technologies Used

- **OpenGL** - 3D graphics rendering
- **GLFW** - Window management and input handling
- **GLAD** - OpenGL function loading
- **GLM** - Mathematics library for graphics
- **stb_image** - Texture loading
- **C++** - Primary programming language
- **Visual Studio** - Integrated development environment

## Setup Instructions

### Prerequisites
- Visual Studio 2019 or later (Windows)
- OpenGL 3.3+ compatible graphics card
- Git for repository cloning

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Vexatious-777/CS330.git
   cd CS330
   ```

2. **Open the project:**
   - Launch Visual Studio
   - Open the `.sln` solution file
   - Ensure the project is set to x86 configuration

3. **Build and run:**
   - Build the solution (`Ctrl+Shift+B`)
   - Run the project (`F5`)

### Dependencies
All required libraries are included in the project.

## Controls

| Input | Action |
|-------|--------|
| `W, A, S, D` | Move camera forward, left, backward, right |
| `Mouse Movement` | Look around (first-person view) |
| `Scroll Wheel` | Zoom in/out |
| `P` | Toggle between perspective and orthographic projection |
| `Esc` | Exit application |

## Development Process

This project was developed as part of the CS330 Computer Graphics course. The development approach focused on:

- **Incremental Learning**: Starting with basic OpenGL concepts and progressively adding complexity
- **Modular Design**: Creating reusable components for shaders, textures, and geometric primitives
- **Iterative Refinement**: Continuously improving visual quality and performance

### Key Challenges Overcome

- **Lighting Calculations**: Implementing proper Phong shading with multiple light sources
- **Texture Coordination**: Ensuring seamless texture mapping across complex 3D objects
- **Camera Mathematics**: Developing smooth, intuitive camera controls using quaternions/matrices
- **Performance Optimization**: Efficient rendering of complex scenes with multiple objects

## Learning Outcomes

Through this project, I developed proficiency in:
- Modern OpenGL rendering pipeline and shader programming
- 3D mathematics and coordinate system transformations
- Real-time graphics optimization techniques
- Computer graphics theory and practical application

## Course Information

**Course**: CS330 Computer Graphics  
**Institution**: Southern New Hampshire University (SNHU)

## License

This project is created for educational purposes as part of CS330 coursework at SNHU.
