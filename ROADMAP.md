# Roadmap

## 3D rendering features

* Vulkan support
* Lightmaps, rewrite using GPU and BVH; also add a denoiser
* Clustered rendering (3.2)
* Particle collision (may be doable using the physics engine in CPUParticles)
* Particle attractors (2D and 3D)
* Particle volumes (2D and 3D)
* Real particle trails
* Baked top-down GI
* Decals
* Render layers and configurable render passes
* Volumetric lighting
* Support for skeleton deforms in particles
* Texture and mesh streaming
* Scene shaders (needs more research)
* Clustered fog (use clustered information to render fog to a 3D texture, then put it back as post-process)
* Occlusion in real-time
* Shader caching (for Vulkan)
* Make GI probes real-time
* Bring back portals and rooms using areas, support sound too
* Octree color and decal painting
* Panini projection (yum)

## 2D rendering features

* Paintable textures (this needs a proposal)
* Directional 2D shadows
* Import SVGs as meshes
* Internal vertices for Polygon2D/Skeleton2D deform

## Compute buffers

* API to create compute buffers, draw to them, etc.

## Navmesh features

* Implement Recast support, generate both from 3D and physics engine; ability to generate in real-time too
* Local obstacle avoidance
* Maybe better to move to a NavigationServer
* Path margins after string pulling
* Support multithreading

## Physics

* Rework/speed up collision code for 2D physics and maybe Godot 3D
* Convex decomposition for triangle meshes

### GDScript

* Typed instructions (first speedup)
* JIT Optimization (second speedup)
* Multithreading support in debugger

### Export

* Easier template builder for iOS/Android
* Stripped export for dedicated server (no textures or geometry, maybe no animation?)

### Debugger

* Improve debugger (exploring data)
* Ability to copy editing camera to in-game to explore level separately
* Put real controls in the property editor, instead of a Tree; convert most editors to that format
* Optionally put the game window in the editor (difficult to do, maybe impossible)

### Audio

* Analysis effects for audio buses with info that can be read from GDScript (Decibels, Fourier frequencies, BPM detection,  Pitch detection, etc).
* Polyphonic AudioStream (play same stream more than once without having to create multiple nodes)
* Reactive music (similar to how WWise works)
* Audio Graph AudioStream (so sound engineers can create complex setups connecting streams and effect nodes)

### Networking

* Add helper node that simplifies synchronization (NetworkSync), so you can specify different properties to track and how to synchronize them (reliable, unreliable, discrete, continuous, interpolation modes, etc). Even replication (synchronize when instantiated).
* Add API in base networking to make it easier to do replication using the above node (needs to be whitelisted).


