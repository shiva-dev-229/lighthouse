# Lighthouse — Low-Poly 3D Scene

> A low-poly nighttime scene modeled and rendered in **Blender**: a glowing lighthouse standing watch over a small island village, with still water reflecting the beacon. A 3D-art study in modeling, materials, lighting, and atmosphere.

---

## About

This is a low-poly stylized scene built in Blender. The focus of the project was the full beginner-to-finish 3D pipeline:

- **Modeling** the lighthouse, the rocky island, and the cluster of low-poly houses.
- **Materials & color** — the red-and-white banded tower, warm-lit windows, and dark rock.
- **Lighting & atmosphere** — the glowing beacon as the key light, the cool night sky, and the soft bloom around the lamp.
- **Rendering** the final 1920×1080 image and exporting the geometry to STL.

---

## Repository contents

```
lighthouse/
├── 18 - lighting and atmosphere 2.blend   # Final Blender project file
├── 18 - lighting and atmosphere.stl       # Geometry exported for 3D printing
├── Final Image.png                        # The rendered scene (1920×1080)
├── Rough/                                  # Earlier working files
│   ├── LightHouse.blend
│   └── light.blend
└── README.md
```

The `Rough/` folder holds the in-progress versions from earlier in the build. (Blender's `.blend1` files are automatic backups and can be ignored.)

---

## Opening the project

1. Install [Blender](https://www.blender.org/download/) (free).
2. Open `18 - lighting and atmosphere 2.blend`.
3. Press `F12` to render, or scrub the viewport to explore the scene.

The `.stl` file can be opened in any slicer (Cura, PrusaSlicer, etc.) if you want to 3D-print the geometry.

---

## Tools

- **Blender** — modeling, materials, lighting, and rendering.

---

## Credit

Scene built by following Grant Abbitt's low-poly Blender tutorial series. The tutorial concept, scene design, and techniques are his; this repository is my hands-on build of the project as a way to learn the Blender workflow.
