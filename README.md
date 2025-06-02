# Neural Assemblies  
**Jinwoo Lee**  
KAIST School of Computing  (cinescope@kaist.ac.kr)

---

## Project Overview

<p align="center">
  <img src="https://github.com/user-attachments/assets/c3b66d4a-cab6-4098-99fa-44de22fba5ca" alt="Teaser Image" width="80%">
  <br>
  <em>Teaser: LEGO-based reconstruction of CG milestones in a neural-rendered garden.</em>
</p>


**Neural Assemblies** is a computationally driven 3D visual composition that synthesizes historical artifacts and figures from the canon of computer graphics through a structured, modular reconstruction using LEGO®-inspired primitives. The project integrates **generative neural pipelines**, notably **DreamGaussian** with **manual modeling and assembly in Blender and LEGO Studio**, resulting in a geometrically coherent and semantically meaningful visual tableau. 

Rather than only pursuing photorealism, we adopt a **symbolic abstraction framework**, where each component is designed to reflect its cultural and technical significance in CG history, including reconstructed icons such as the Stanford Bunny, Utah Teapot, Cornell Box, and Suzanne. Our approach bridges neural scene representations with structured artistic grammar, demonstrating how **modern neural volume rendering can support pedagogically grounded, historically reflective, and formally consistent visual storytelling**.

Demo of this project:  
**[https://cinescope-wkr.github.io/neural-assemblies](https://cinescope-wkr.github.io/cs479-neural-assemblies)**  

---

## Key Contributions

- A 3D scene composed of iconic CG artifacts including:
  - Stanford Bunny, Utah Teapot, Cornell Box, Lena, Suzanne (Blender), Luxo Jr. lamp, Mitsuba Clover
  - Stylized depictions of LEGO® figurine of Edwin Catmull and Steve Jobs... and more 
- Integration of **[DreamGaussian](https://dreamgaussian.github.io)**to synthesize candidate 3D geometry
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
**[https://cinescope-wkr.github.io/neural-assemblies](https://cinescope-wkr.github.io/cs479-neural-assemblies)**

---

## Acknowledgements

This project was created as part of the CS479 Rendering Contest (Spring 2025), inspired by the intersection of neural graphics and artistic reconstruction.  
Special thanks to open-source contributors to DreamGaussian, Blender, and LEGO Studio.
