# 🎨 Graffiti Freedom – VR Street Art Experience  
*(XR Project – 2019 · VR Game)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Graffiti Freedom** is an experimental **VR experience** that lets players freely spray graffiti inside a virtual subway station—  
reclaiming urban public space **without violating real-world laws**.  

The project merges **street art aesthetics** with **immersive technology**, turning an underground environment into a canvas for rebellion and personal expression.  
Inside the simulation, players use a **virtual spray can** to paint their thoughts and identities across the walls,  
challenging the boundaries between **legality and creativity** in both real and digital worlds.  

---

## ⚙️ Technical Description  
- **Engine:** Unity (SteamVR / OpenXR)  
- **Language:** C#  
- **Rendering Pipeline:** Built-in  
- **Hardware:** HTC Vive / Oculus Rift  
- **Software:** Blender · Substance Painter  
- **Pipeline:**  
  1. **Environment Construction**  
     - Subway-station interior modeled and textured with **PBR workflow** in Blender + Substance Painter.  
     - Lighting baked for moody, nocturnal realism.  
  2. **Spray Interaction System**  
     - Vive controller **trigger** mapped to spray emission intensity.  
     - Implemented **particle-based spray simulation** using Unity’s Particle System.  
     - When paint particles collide with wall colliders, their **UV coordinates are sampled**,  
       updating a **dynamic render texture** linked to the wall’s shader.  
  3. **Material Shader Logic**  
     - Custom shader writes color values from collision points directly into the surface’s paint mask.  
     - Layer blending supports **opacity, diffusion, and drip simulation** for natural spray behavior.  
  4. **Performance & Layer Control**  
     - Dynamic texture buffer optimized with GPU-side blitting for real-time drawing.  
     - Added **save/clear layer system** to preserve user graffiti between sessions.  
  5. **Immersive Environment**  
     - Sound design synchronized with motion intensity (spray distance and speed).  
     - Ambient reverb reflects the echo of an empty station, heightening the act of expression.  

---

## 🧠 Artistic & Research Focus  
**Graffiti Freedom** redefines what it means to *mark a surface*.  
In a world where public space is constantly surveilled and regulated, the project offers a **virtual site of liberation**,  
where rebellion and creativity coexist safely in digital form.  

The subway—a historically contested space of anonymity, escape, and defiance—becomes a poetic metaphor for  
**freedom reclaimed through simulation**.  
It invites players to question how technology can both **restrict and expand artistic autonomy**.  

---

## 🖼️ Media
<p align="center">
  <img src="./media/GraffitiFreedom_01.jpg" width="40%" style="margin-right:5px;"/>  
<!--  <img src="./media/GraffitiFreedom_02.jpg" width="40%" style="margin-right:5px;"/>-->
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/1108000765">
    <img src="./media/GraffitiFreedom_01.jpg" width="40%" style="border-radius:10px;"/>
  </a>
</p>

---

## 👤 Credits  
**Artist / Developer:** Jonghoon Ahn  
**Year:** 2019  
**Hardware:** HTC Vive  
**Medium:** VR Game / Immersive Art Experience  

---

## 🔗 Related  
- [Back to Interactive VR Experience](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
