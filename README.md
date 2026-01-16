Hi there!

# WebGL Spritesheet Animation

A minimal **WebGL2 spritesheet animation demo** that renders and animates a spritesheet entirely on the GPU using GLSL shaders.

This project demonstrates how to:
- Load a spritesheet texture in WebGL
- Select animation frames in a fragment shader
- Animate sprites at a fixed FPS
- Render with alpha blending
- Display real-time FPS via a HUD

# Demo Overview

- WebGL2 context
- Single quad rendered in clip space
- Frame selection done in the fragment shader using UV math
- Nearest-neighbor sampling for pixel-perfect sprites
- Lightweight, no external libraries