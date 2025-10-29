
---

# 🚀 **Three.js Learning Journey – 30-Day Roadmap (Nov 1 – Nov 30)**

---

## 🧮 **Phase 1 – Math for 3D (Nov 1 – 14)**

| 📅 Day     | 🎯 Focus                    | 📘 Concept                        | 💡 Practice                                |
| :--------- | :-------------------------- | :-------------------------------- | :----------------------------------------- |
| **Nov 1**  | 2D vs 3D Coordinate Systems | X, Y, Z axes, origin, directions  | Draw a 3D axis on paper or Desmos 3D       |
| **Nov 2**  | Points & Distance           | Euclidean distance formula        | Write a JS function to compute 3D distance |
| **Nov 3**  | Vector Basics               | Vector as direction + magnitude   | Create and add/subtract vectors in JS      |
| **Nov 4**  | Vector Operations           | Dot product and angle similarity  | Compute dot (1,0,0) · (0,1,0)              |
| **Nov 5**  | Cross Product               | Find a perpendicular vector       | Practice right-hand rule examples          |
| **Nov 6**  | Normalization               | Unit vectors and why they matter  | Normalize (3, 4, 0) manually + in code     |
| **Nov 7**  | Angles & Rotation           | Degrees ↔ Radians, sin/cos basics | Animate circular motion in JS canvas       |
| **Nov 8**  | Matrix Basics               | 2×2 & 3×3 transformations         | Demo scaling and rotation matrix           |
| **Nov 9**  | Transformations             | Translation, Rotation, Scaling    | Visualize how a matrix affects a point     |
| **Nov 10** | Perspective                 | Vanishing point, field of view    | Sketch perspective lines by hand           |
| **Nov 11** | Camera Math                 | Eye, LookAt, Up vectors           | Learn how a camera views a scene           |
| **Nov 12** | Lighting Math               | Using dot product for lighting    | Compute light intensity by angle           |
| **Nov 13** | Projection Math             | Orthographic vs Perspective       | Visualize both projections                 |
| **Nov 14** | Revision Day                | Review all formulas + mini quiz   | Create a math cheat sheet                  |

🧠 **Tip:**
This phase is about **understanding**, not coding speed.
Create a file called `math_playground.js` and experiment with each concept there.

---

## 🌍 **Phase 2 – Three.js Core (Nov 15 – 30)**

| 📅 Day     | 🎯 Focus                | 💻 Task                                  | 💡 Tip                                  |
| :--------- | :---------------------- | :--------------------------------------- | :-------------------------------------- |
| **Nov 15** | Setup + Scene           | Install Three.js and create a basic cube | Use Vite or CDN for quick setup         |
| **Nov 16** | Scene, Camera, Renderer | Understand the render loop               | Draw a wireframe cube                   |
| **Nov 17** | Geometry & Material     | Try BoxGeometry, SphereGeometry          | Change materials dynamically            |
| **Nov 18** | Lighting                | Add Ambient + Directional lights         | Rotate lights to see shadows change     |
| **Nov 19** | Camera Controls         | Use OrbitControls                        | Zoom and rotate the scene interactively |
| **Nov 20** | Animation Loop          | Move a cube using `sin()`                | Connect math with visuals               |
| **Nov 21** | Shadows                 | Enable shadows properly                  | Configure renderer, light, and objects  |
| **Nov 22** | Textures                | Add image textures to a cube             | Use `TextureLoader`                     |
| **Nov 23** | Import 3D Models        | Load `.glb` / `.gltf` files              | Try a model from Sketchfab              |
| **Nov 24** | GUI Controls            | Add dat.GUI for tweaks                   | Add color and slider controls           |
| **Nov 25** | Multiple Objects        | Add several meshes in one scene          | Create a mini environment               |
| **Nov 26** | Camera Animation        | Animate camera movement                  | Fly around the scene                    |
| **Nov 27** | Physics Intro           | Use GSAP for smooth motion               | Make a bounce or spin effect            |
| **Nov 28** | Particle System         | Use `PointsMaterial` and particles       | Create stars or rain effect             |
| **Nov 29** | Mini Project            | Combine all concepts                     | Build a Solar System or 3D Room         |
| **Nov 30** | Showcase + Review       | Record a short demo video                | Deploy on Vercel and share on GitHub    |

---

## 🧭 **Extra Resources**

* 📘 Docs: [https://threejs.org/docs/](https://threejs.org/docs/)
* 🧑‍💻 Playground: [https://threejs.org/editor/](https://threejs.org/editor/)
* 📺 YouTube: **Simon Dev – Three.js Math & Shaders**

---

## 🧠 **Summary**

| Phase                  | Duration    | Focus                               |
| :--------------------- | :---------- | :---------------------------------- |
| **Math for 3D Basics** | Nov 1 – 14  | Build your mental 3D map & formulas |
| **Three.js Core**      | Nov 15 – 30 | Bring that math to life in code     |

---
