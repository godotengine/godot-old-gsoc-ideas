

### 3D Rendering Features
* LightMapper	https://github.com/Microsoft/UVAtlas			
* Clustered Rendering				
* Particle Collision				
* Particle Attractors (2D and 3D)				
* Particle volumes (2D and 3D)				
* Real Particle Trails				
* Baked top-down GI				
* VR Support				
* Decals				
* Render Layers and configurable render passes				
* Volumetric Lighting				
* Support skeleton deform in particles				
* texture and mesh streaming				
* Scene Shaders
* clustered fog	use clustered information to render fog to a 3D texture, then put it back as post process			
* occlusion in real-time
* Shader caching				
* fix SSAO depth discontinuities using better depth aware blur				
* make GI probes real time				
* Bring back portals and rooms using areas, support sound too				
* octree color and decal painting				
* panini projection (yum)				
* properly expose texture arrays and 3D textures. Make array importer?				

### 2D Rendering Features
* Skeletons for 2D				
* Meshes for 2D				
* Paintable textures				
* Animated textures				
* Directional 2D shadows				

### Animation	Features 
* Transition graph				
* Bezier curve support				
* Cinematic stuff (check cinemachine)				
* onion skinning	https://github.com/godotengine/godot/issues/10425#issuecomment-323503064			

### Navmesh Features
* Implement Recast support	generate both from 3D and physics engine. Ability to generate in real-time too.			
* Local obstacle avoidance				
* path margins after string pulling				

### Physics				
* Rework/speed up collision code				
* convex decomposition for trimesh				
* Better ragdoll support (easier to configure)				
* IK Support for skeletons				

### GDScript				
* JIT Optimization				
* Optional Typing				
* Multithread support in debugger				
				
### Export				
* Easier template builder for iOS/Android				
* Godot export plugin for Blender				
* FBX -> Godot via separate binary				
* OpenGEX?

### Debugger				
* Improve debugger (exploring data)				
* Ability to copy editing camera to in-game to explore level separately
* Put real controls in the property editor, instead of actual Tree. Convert most editors to that format				
