# 🚇 Escape Metro – Surreal VR Escape Game  
*(XR Project – 2024 · Seongsu KAIA Pop-up Store · Collaboration with RedFlight)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Escape Metro** is a surreal **VR escape game** created in collaboration with **RedFlight**,  
set within a distorted subway network that loops infinitely through memory, dialogue, and control.  

Players awaken in an abandoned underground station with no recollection of how they arrived.  
To escape, they must **communicate with an AI guard** — a character powered by **ChatGPT API** —  
that tests their logic, honesty, and emotional persistence through real-time voice conversation.  
Only by breaking through the AI’s “jail” of programmed behavior can players unlock the path to freedom.  

Designed for **Meta Quest 3**, the experience merges spatial architecture, psychological tension, and live AI negotiation —  
transforming the act of conversation itself into a puzzle of consciousness.

---

## ⚙️ Technical Description  
- **Engine:** Unity (XR Interaction Toolkit · URP)  
- **Language:** C#  
- **Hardware:** Meta Quest 3 (VR) · PC (NVIDIA RTX 4070 Super)  
- **Software:** Blender · Substance Painter · Character Creator 4 (CC4)  
- **AI Integration:** OpenAI ChatGPT API (WebSocket) + ElevenLabs Voice API  
- **Collaboration Tools:** Git (Version Control) via RedFlight’s Private Repository  

### 🧩 Development Pipeline  
1. **Character Design & Animation**  
   - Created AI guard and NPCs using **CC4**, textured and rigged for Unity’s XR Rig.  
   - Integrated facial expressions with Unity **Animator Controller** and **blendshape-driven lip sync**.  
2. **Dialogue System & Jailbreak AI**  
   - Implemented a **ChatGPT dialogue system** using WebSocket for low-latency response.  
   - AI prompts dynamically shift tone and behavior depending on player input,  
     allowing “jailbreaking” through verbal manipulation (logical, emotional, or rebellious dialogue paths).  
3. **Voice Interaction**  
   - Used **ElevenLabs API** for real-time TTS responses from the AI guard.  
   - Player voice captured through Meta Quest microphone → converted to text via local speech-to-text → streamed to ChatGPT for live response.  
4. **Gameplay Logic**  
   - Progression tied to narrative “truth detection” by AI guard.  
   - Correct emotional resonance or contradiction detection unlocks doors and station gates.  
5. **Visual & Sound Design**  
   - Environment modeled after Seoul subway geometry but distorted through procedural generation.  
   - Dynamic lighting system reacts to AI tone (anger, confusion, empathy).  
   - Psychological soundscape created using **FMOD** and **Unity Audio Mixer**.  
6. **Version Control & Deployment**  
   - Collaborated with RedFlight team via **Git**, maintaining build branches for testing and QA.  
   - Optimized shaders and baked lightmaps for Meta Quest 3 standalone performance.  

---

## 🧠 Artistic & Research Focus  
**Escape Metro** explores **control, rebellion, and communication** in a machine-mediated environment.  
The subway, an endless recursive system, becomes a metaphor for **algorithmic confinement** —  
a space where human agency is tested against programmed logic.  

By merging **AI negotiation** and **spatial exploration**, the work challenges the boundary between  
*“escaping the game”* and *“escaping the system.”*  
The player’s voice becomes both a weapon and a confession — the key to unlocking digital empathy.

---

## 🖼️ Media
<p align="center">
  <img src="./media/EscapeMetro_01.jpg" width="40%" style="margin-right:5px;"/>  
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/1107998609" target="_blank">
    <img src="./media/EscapeMetro_01.jpg" width="40%" style="border-radius:10px;"/>
  </a>
  <br>
  <em>Click to view full video on Vimeo</em>
</p>

---

## 👤 Credits  
**Studio Collaboration:** RedFlight  
**Game Developer / Technical Director:** Jonghoon Ahn  
**Year:** 2024  
**Platform:** Meta Quest 3  
**Exhibition:** Seongsu KAIA Pop-up Store (Web3 Integrated Showcase)  
**Medium:** VR Game / Interactive AI Narrative  

---

## 🔗 Related  
- [Back to Interactive VR Experience](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
