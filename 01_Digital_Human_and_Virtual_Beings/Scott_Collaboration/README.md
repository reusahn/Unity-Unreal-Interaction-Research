# 🕯️ Scott Collaboration – Digital Memory Sculpture  
*(Interactive AI Installation – 2025 · Phase Gallery, Los Angeles)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Scott Collaboration** is an interactive media installation created with **Scott**,  
who sought to memorialize his late mother and a close friend through digital preservation and AI-based reanimation.  
The work transforms deteriorated photographs into **3D sculptural portraits**, blending stone-like stillness with AI-generated motion.  

When viewers approach, the static sculptures awaken—  
their surfaces dissolving into **particle-based video projections** that reveal faintly living presences within.  
Through this transformation, the project questions how **memory, loss, and recognition** manifest in an age when even grief becomes computationally encoded.

---

## ⚙️ Technical Description  
- **Engine:** Unity (HDRP)  
- **Software:** Maya · Blender · Topaz Labs · Meshy AI · VEO 3  
- **Language:** C# · Python  
- **AI Tools:** VEO 3 (Generative Motion Loop) · Meshy AI (3D Reconstruction)  
- **Hardware:** PC (NVIDIA RTX 4070 Super) · Webcam · Projection System  
- **Pipeline:**  
  1. **Image Restoration:**  
     Original low-resolution portraits of Scott’s mother and friend were restored using **Topaz Labs AI** for super-resolution and artifact removal.  
  2. **3D Reconstruction:**  
     The enhanced images were processed through **Meshy AI** to generate 3D geometry and depth maps.  
     The resulting models were refined in **Blender**, textured with concrete-like materials, and sculpted to evoke **memorial statues**.  
  3. **AI Motion Generation:**  
     Using **VEO 3**, looping “idle” motion sequences were generated from the original still images,  
     producing subtle movements such as breathing, blinking, and tilting—simulating life through noise.  
  4. **Unity Integration:**  
     The 3D sculptures and AI-generated videos were imported into **Unity HDRP** and combined using the **Visual Effect Graph**.  
     Luminance-driven particle systems mapped video pixels to 3D space,  
     making brighter regions project outward as depth particles to create the illusion of floating light.  
  5. **Facial Detection & Interaction:**  
     **OpenCV** was implemented for real-time face recognition.  
     When a viewer’s face entered the camera’s frame and reached a certain proximity,  
     the corresponding sculpture transitioned from static stone to **AI-animated particle form**, symbolizing reawakening.  
  6. **Lighting & Spatial Composition:**  
     Subtle volumetric lighting and soft shadows were synchronized with particle brightness,  
     generating a quiet, contemplative atmosphere between the viewer and the digital memorials.  

---

## 🧠 Artistic & Research Focus  
The project investigates **grief as an interactive process**—where technology mediates remembrance and emotional continuity.  
It redefines portraiture as an evolving, responsive entity,  
asking whether **a digital memory can still feel human** when rendered through algorithms of light, noise, and distance.  

Through the collaboration with Scott, this work becomes not only an artwork but also a **ritual of digital empathy**,  
where code and memory intersect to create a moment of recognition between the living and the departed.

---

## 🖼️ Media
<p align="center">
  <img src="./media/Scott_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/Scott_02.jpg" width="40%" style="margin-right:5px;"/>
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/your-video-link-here" target="_blank">
    <img src="./media/Scott_Thumb.jpg" width="40%" style="border-radius:10px;"/>
  </a>
  <br>
  <em>Click to view full video on Vimeo</em>
</p>

---

## 👤 Credits  
**Collaborating Artist:** Scott  
**Technical Director:** Jonghoon Ahn  
**Year:** 2025  
**Exhibition:** Phase Gallery, Los Angeles  
**Medium:** Interactive AI Installation · Digital Sculpture  

---

## 🔗 Related  
- [Back to Digital Human & Virtual Beings](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
