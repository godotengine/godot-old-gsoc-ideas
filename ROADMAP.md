

### 3D Rendering Features
* LightMapp, rewrite using GPU and BVH. Also add a denoiser.
* Clustered Rendering [3.2]
* Particle Collision (may be doable using physics engine in CPUParticles)
* Particle Attractors (2D and 3D)				
* Particle volumes (2D and 3D)				
* Real Particle Trails				
* Baked top-down GI				
* Decals				
* Render Layers and configurable render passes	
* Volumetric Lighting				
* Support skeleton deform in particles				
* texture and mesh streaming				
* Scene Shaders (needs more research)
* clustered fog	use clustered information to render fog to a 3D texture, then put it back as post process			
* occlusion in real-time
* Shader caching (for Vulkan)				
* make GI probes real time				
* Bring back portals and rooms using areas, support sound too				
* octree color and decal painting				
* panini projection (yum)				

### 2D Rendering Features
* Paintable textures (this needs a proposal)
* Directional 2D shadows				

### Navmesh Features
* Implement Recast support	generate both from 3D and physics engine. Ability to generate in real-time too.			
* Local obstacle avoidance				
* Maybe better to move to a NavigationServer
* path margins after string pulling	
* support multithreading

### Physics				
* Rework/speed up collision code for 2D physics and maybe Godot 3D
* convex decomposition for trimesh				

### GDScript				
* Typed instructiosn (first speed up)
* JIT Optimization (second speed up)	
* Multithread support in debugger				
				
### Export				
* Easier template builder for iOS/Android				

### Debugger				
* Improve debugger (exploring data)
* Ability to copy editing camera to in-game to explore level separately
* Put real controls in the property editor, instead of actual Tree. Convert most editors to that format			
* optionally put the game window int the editor (this is pretty difficult to do.. maybe impossible)

