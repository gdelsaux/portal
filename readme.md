# Three Js portal scene
index.html only contains 1 element (canvas) which is used to "draw" the 3D model.

note:
- The scene has no lights, all lights and colors are from the baked image in ```/static/baked.jpg```
- The model has been made in blender from scratch and can be found in ```/static/portal.glb```
- I have used ```Draco``` to compress the model and improve performances.

#### Tech Stack
- Draco
- ThreeJs

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```
