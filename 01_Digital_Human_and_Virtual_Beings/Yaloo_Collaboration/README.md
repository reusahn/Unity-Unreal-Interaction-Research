# 🌿 Yaloo_Collaboration  
*(Posthuman Media Art Collaboration – 2024 · Gyeonggi Museum of Modern Art)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Yaloo_Collaboration** is a posthuman media art project created in collaboration with artist **Yaloo**, exploring identity, transformation, and digital ecology.  
The work reimagines Yaloo as a **hybrid being merging human and seaweed**, symbolizing ecological coexistence and digital rebirth.  

Exhibited at the **Gyeonggi Museum of Modern Art**, the piece visualizes a continuous transformation between a child, an adult, and an elder—each representing different stages of human and marine evolution.  
Through real-time metamorphosis, the work examines how digital organisms can embody the emotional and biological rhythm of nature within computational space.

---

## ⚙️ Technical Description  
- **Engines:** Unreal Engine 5 · Unity  
- **Software:** MetaHuman Creator · Character Creator 4 (CC4) · Blender · Maya · Marvelous Designer  
- **Language:** Python · C#  
- **Hardware:** PC (NVIDIA RTX 4070 Super) · VR Headset  
- **Pipeline:**  
  1. **Facial Capture & MetaHuman Creation:**  
     A facial video of artist **Yaloo** was converted into a 3D mesh and processed through **MetaHuman Creator**, resulting in a lifelike head model retaining her key facial features.  
  2. **Hybrid Body Design:**  
     A **child’s body** was generated using **Character Creator 4 (CC4)**.  
     The head from MetaHuman and the CC4 body—each with different rigs—were merged inside **Unreal Engine**, achieving a unified hybrid rig through custom retargeting.  
  3. **Hair & Material Design:**  
     The hair was sculpted in **Blender**, stylized to resemble **seaweed**, and imported as an **Alembic (ABC)** file for dynamic simulation inside Unreal.  
     Custom shaders created the translucent, organic surface texture resembling underwater organisms.  
  4. **Motion Capture Integration:**  
     - **Facial mocap:** Captured via **Apple ARKit** and imported as CSV animation curves into Unreal’s Sequencer.  
     - **Body mocap:** Extracted from 2D video data using **Move.ai**, converted to skeletal animation, and applied to the hybrid rig.  
  5. **Environmental Design:**  
     Real-time water caustics, particle fog, and low-frequency lighting simulate an underwater breathing effect within Unreal Engine’s Niagara system.  

---

## 🧠 Artistic & Research Focus  
This collaboration investigates **posthuman identity** and **digital–organic symbiosis** through hybrid digital human construction.  
The merging of tools from different ecosystems—**MetaHuman**, **CC4**, **Blender**, and **Move.ai**—becomes a metaphor for **biological and technological interdependence**.  

The work proposes a posthuman body that transcends gender, age, and material boundaries, representing an **ecosystemic empathy between human and environment**.

---

## 🖼️ Media
<p align="center">
  <img src="./media/Yaloo_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/Yaloo_02.jpg" width="40%" style="margin-right:5px;"/>
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/your-video-link-here" target="_blank">
    <img src="./media/Yaloo_Thumb.jpg" width="40%" style="border-radius:10px;"/>
  </a>
  <br>
  <em>Click to view full video on Vimeo</em>
</p>

---

## 👤 Credits  
**Collaborating Artist:** Yaloo  
**Technical Director:** Jonghoon Ahn  
**Year:** 2024  
**Exhibition:** Gyeonggi Museum of Modern Art  
**Medium:** Digital Human · Interactive Media Installation  

---

## 🔗 Related  
- [Back to Digital Human & Virtual Beings](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
