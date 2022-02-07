# Compute Shader Mesh Path Tracing
Path tracing engine to raytrace meshes from Unity gameObjects. Implemented using HLSL compute shaders in Unity3D.

**Currently implemented:**
- Pathtracing for perfect planes and spheres.
- Pathtracing for meshes from Unity GameObjects.
- Phong specular reflections.
- Variable surface roughness for specular reflections.
- Lambert diffuse relections.
- Importance sampling to speed-up convergence.
- Support for normal interpolation using barycentric coordinates.
- Anti-Aliasing by offset resampling.

**Possible extensions:**
- Non-opaque materials.
- Directional lights + multi-importance sampling.
- Some form of ray-collision-detection optimization (e.g. BVH/kD tree/etc.)

# Screenshots

<img src="https://raw.github.com/akoreman/Compute-Shader-Mesh-Ray-Tracing/main/images/SpecReflections.PNG" width="400">  

<img src="https://raw.github.com/akoreman/Compute-Shader-Mesh-Ray-Tracing/main/images/RayScene.png" width="400">  

**Normal interpolation visualised by interpolating vertex colors.**


<img src="https://raw.github.com/akoreman/Compute-Shader-Mesh-Ray-Tracing/main/images/Interpolation.png" width="400">  
