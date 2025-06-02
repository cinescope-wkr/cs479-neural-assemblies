# Neural Assemblies  
**Jinwoo Lee**  
KAIST School of Computing  (cinescope@kaist.ac.kr)

---

## Project Overview

**Neural Assemblies** is a stylized 3D visual experience that reimagines foundational artifacts and figures from the history of computer graphics through the modular language of LEGO®. By combining generative AI pipelines with manual 3D modeling, the project produces a coherent, educational, and visually compelling scene rendered through a neural graphics pipeline.

![Teaser](./asset/teaser.png)
_Teaser: LEGO-based reconstruction of CG milestones in a neural-rendered garden._

---

## Key Contributions

- A 3D scene composed of iconic CG artifacts including:
  - Stanford Bunny, Utah Teapot, Cornell Box, Lena, Suzanne (Blender), Luxo Jr. lamp, Mitsuba Clover
  - Stylized depictions of Edwin Catmull and Steve Jobs
- Integration of **DreamGaussian** to synthesize candidate 3D geometry
- Manual refinement and stylization in **Blender** and **LEGO Studio**
- Final rendering pipeline combining neural representations and stylized shading

---

## Methodology

The project follows a hybrid pipeline involving:

- **Generative Phase**: Asset priors generated using DreamGaussian and processed to fit modular LEGO-style constraints.
- **Manual Modeling Phase**: Human-in-the-loop asset refinement and snapping-based LEGO assembly using Blender and LEGO Studio libraries.
- **Rendering Phase**: Stylized rendering using a neural volume representation engine, with attention to inter-object illumination and LEGO material properties.

---

## Design Principles

- **Modularity**: All 3D assets are composed of discrete LEGO-compatible units
- **Stylistic Consistency**: A unified visual language informed by real-world LEGO kits
- **Pedagogical Intent**: Scenes curated to reflect landmark moments in CG, enabling reflection and education

---

## Technical Stack

- DreamGaussian (3D priors)
- Blender (manual modeling, scene layout)
- LEGO Studio (real-world brick compatibility)
- Custom NeRF-style renderer
- GitHub Pages + Three.js (for optional interactive deployment)

---

## Live Demo

View the hosted version of this project:  
**[https://cinescope-wkr.github.io/neural-assemblies](https://cinescope-wkr.github.io/neural-assemblies)**

---

## Acknowledgements

This project was created as part of the CS479 Rendering Contest (Spring 2025), inspired by the intersection of neural graphics and artistic reconstruction.  
Special thanks to open-source contributors to DreamGaussian, Blender, and LEGO Studio.
