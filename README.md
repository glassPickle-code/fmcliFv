# Felpudo Mesh CLI FreeV

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Version](https://img.shields.io/badge/Release-PreJarred-orange)
![Copyright](https://img.shields.io/badge/Copyright-%C2%A9%20GlassPickle%202026--2027-purple)

**Felpudo Mesh CLI FreeV** is a specialized, lightweight command-line utility designed to bridge 3D computer-aided design models in **STL format** into high-quality computational mesh files compatible with **SU2**, a widely used open-source CFD (Computational Fluid Dynamics) simulation framework[cite: 1].

---

## 🚀 What It Is & How It Can Help

When setting up simulations, converting complex geometries can often become a tedious roadblock. Felpudo Mesh CLI FreeV streamlines this workflow directly from your desktop:

* **Seamless STL-to-SU2 Conversion:** Quickly translates your 3D CAD data into ready-to-use CFD mesh formats without manual mesh debugging[cite: 1].
* **Surface Meshing Mode (Mode 1):** Automatically ingests your STL geometry, generates a clean 2D surface mesh, and correctly assigns the boundary surfaces as `WALL`[cite: 1].
* **Intelligent Command-Line UI:** Features an interactive interface with built-in file detection in your working directory, custom mesh size scaling, bounding box checks, and structured error handling[cite: 1].
* **Gmsh Powered Engine:** Relies on robust underlying meshing and optimization libraries to guarantee quality elements[cite: 1].

---

## 📥 Download the PreJarred Windows Release

Get the latest compiled Windows executable right here:

👉 **[Download Felpudo Mesh CLI FreeV (PreJarred Release)](https://github.com/glassPickle-code/fmcliFv/releases/tag/PreJarred)**

### Getting Started on Windows
1. Download the executable from the release link above.
2. Place your target `.stl` files in the exact same folder as the application[cite: 1].
3. Run the compiled Windows binary and follow the friendly interactive prompts to generate your `.su2` output[cite: 1].

---

## 📜 License & Distribution Notice

**Felpudo Mesh CLI FreeV** is proudly created and distributed under copyright by **© GlassPickle (2026–2027)**[cite: 1]. 

Please note that this repository and its releases contain **compiled Windows binaries only**. To keep things streamlined, secure, and ready for deployment, the underlying source code remains private, and only the packaged executable is provided.

### A Note on Our "PreJarred" Release
You'll notice this build is marked as a **PreJarred** version. Don't worry—while tech circles typically use labels like "beta," we like to think of *PreJarred* like freshly preserved goods: everything is carefully packed, sealed, and ready to use right out of the box, even if we are still adding fresh touches as we grow. 

If you run into any quirks or want to share your feedback as you test out the binary, we're right here with you on the journey. Enjoy exploring the tool, and thank you for supporting GlassPickle! 
