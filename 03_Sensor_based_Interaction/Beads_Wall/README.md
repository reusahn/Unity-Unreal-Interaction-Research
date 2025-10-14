# 🟣 Beads Wall – Motion-Driven Interactive Installation  
*(Media Installation – 2025 · California Institute of the Arts)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Beads Wall** is a large-scale media installation that transforms **human motion into abstract visual compositions** made of colorful, shimmering beads—rendered in real time across four aligned 65-inch displays.  
As viewers walk past the piece, **OpenCV-based motion tracking** detects their silhouettes and reinterprets them as **pointillist formations of small digital spheres**.  
Each bead represents a pixel of movement, continuously regenerating and dissolving as the viewer shifts position, turning the act of passing by into a living performance of light and form.  

A **translucent gel diffusion layer** placed in front of the screens adds a physical, tactile dimension, allowing HDRP-rendered light to scatter softly through the material surface.  
Through motion, reflection, and embodied data visualization, **Beads Wall** reimagines human presence as a **kinetic digital painting**.

---

## ⚙️ Technical Description  
- **Engine:** Unity (HDRP)  
- **Language:** C#  
- **Libraries:** OpenCV for Unity  
- **Tools:** VFX Graph · Shader Graph  
- **Hardware:** 4×65" Displays · PC (NVIDIA RTX 4090) · Azure Kinect / High-Resolution Webcam  
- **Pipeline:**  
  1. **Motion Detection**  
     - Captured live RGB feed through **OpenCV for Unity**.  
     - Applied **background subtraction + frame differencing** to isolate moving regions.  
     - Used **contour extraction** and **binary masking** to obtain viewer silhouettes in real time.  
  2. **Pixel-to-Bead Mapping**  
     - Each detected pixel of the silhouette is converted into a **3D bead emitter**.  
     - The bead’s color, brightness, and emission intensity are dynamically linked to **motion velocity and luminance** values.  
     - The system can track multiple participants simultaneously, generating layered silhouettes of light.  
  3. **Particle Rendering**  
     - Implemented in **Unity HDRP + VFX Graph** for physically accurate light scattering and specular reflection.  
     - Motion data drives parameters like bead size, flow turbulence, and emissive color variation.  
  4. **Multi-Screen Synchronization**  
     - Four displays are linked via **synchronized camera arrays**, ensuring seamless panoramic motion continuity.  
     - Each screen renders a segment of the scene space while sharing global particle simulation data.  
  5. **Material Diffusion Layer**  
     - Installed a semi-transparent **gel diffusion membrane** in front of all displays.  
     - The membrane softens HDRP light scattering, adding real-world texture and depth to the digital surface.  

---

## 🧠 Artistic & Research Focus  
**Beads Wall** investigates how **motion data and light** can merge to express emotion and presence.  
It translates **the human body into a network of luminous particles**, exploring the coexistence of digital abstraction and physical tactility.  
By merging **computer vision, real-time rendering, and embodied interaction**, the work transforms data into empathy—  
revealing how even a passing movement can become a visual echo of existence.  

---

## 🖼️ Media
<p align="center">
  <img src="./media/BeadsWall_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/BeadsWall_02.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/BeadsWall_03.jpg" width="40%" style="margin-right:5px;"/>  
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/1055793366/92b0f81f7f" target="_blank">
    <img src="./media/BeadsWall_01.jpg" width="40%" style="border-radius:10px;"/>
  </a>
  <br>
  <em>Click to view full video on Vimeo</em>
</p>

---

## 👤 Credits  
**Artist / Developer:** Jonghoon Ahn  
**Year:** 2025  
**Exhibition:** California Institute of the Arts  
**Medium:** Interactive Media Installation (Unity HDRP, OpenCV, VFX Graph)  

---

## 🔗 Related  
- [Back to Sensor-based Interaction (Azure Kinect)](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
