---
layout: project
title:  "Advanced Technologies Projects"
date:   2023-02-24 16:54:46
author: Matthew Cheung
categories:
- project
img: AT.png
thumb: AT.png
carousel:
- collision.png
- raytracer.png
- skeletal-animation.png
tagged: Developement, Rendering, Collision, Animation, Skeletal Mesh, Ray Tracing, OpenGL
client: University Project
published: true
---
#### Advanced Technologies Project

These are projects created during my third year at university called Advanced Technologies. This module puts a focue
on studying and implementing low-level technologies in games.

#### Collision System

In this project, I wrote a collision detection system alongside a basic OpenGL rendering pipeline.

The collision system using Separating Axis Theorem(SAH) to calculate collisions between cubes. Have also implemented
a basic Bounding Volume Hierarchy to decrease the amount of collision calculations.

Technologies used:
- OpenGL
- Win32
- C++
- Separating Axis Theorem
- Collision Detection
- Bounding Volume Hierarchy

### Ray Tracer

In this project, I implemented a basic ray-tracer in C++. I used a Bounding Volume Hierarchy to optimise the
amount of ray-geometry intersection checks. Which improved the performance of the application. Multi-threading
has also been added to application too.

Technologies used:
- C++
- Bounding Volume Hierarchy
- Ray-geometry intersections
- Multi-threading

### Skeletal Animations

In this project, I implemented a skeletal animation system. I used Assimp to load the meshes, textures
and animation data into the scene. I've also added interpolation to achieve a smoother look to animation between
key frames.

Technologies used:
- OpenGL
- Win32
- C++
- Assimp
- Animation interpolation
- Skeletal Animation
- Skinned Meshes

### Git Repositories
- [Collision System][collision]
- [Ray Tracer][raytracer]
- [Skeletal Animation][animation]

[Watch the demo reel][demo]

[demo]:https://drive.google.com/file/d/164-ffS5rPAAIDCRsbX7ALMpj2qgmdA8r/view?usp=share_link
[collision]:https://github.com/matthew-cheung-dev/AdvancedTechnologiesProject1
[raytracer]:https://github.com/matthew-cheung-dev/AdvancedTechnologiesProject2
[animation]:https://github.com/matthew-cheung-dev/AdvancedTechnologiesProject3