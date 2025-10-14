# 🎤 Choi Jung-hoon AI Human Research Project  
*(JANNABI AI Digital Human)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧠 Overview  
This research-based installation reconstructs **Choi Jung-hoon**, the lead vocalist of the Korean band **JANNABI**, as an AI-generated digital human.  
The project examines how identity, emotion, and authorship can be simulated through generative AI systems.  
A virtual Choi Jung-hoon engages in live conversation with viewers, responding in real time with his synthesized voice and mannerisms.  
It explores the emotional boundaries between admiration, replication, and authenticity within human–machine relationships.

---

## ⚙️ Technical Description  
- **Engine:** Unity  
- **Software:** Character Creator 4 (CC4), Headshot Plugin, ZBrush, Maya, Blender  
- **Language:** C#, Python  
- **AI Models:** OpenAI GPT (chat-based persona), ElevenLabs Voice Cloning API, diffusion-based texture synthesis  
- **Hardware:** Microphone, Azure Kinect, PC (NVIDIA RTX 4070 Super)  

### 🧩 Pipeline  

1. **Digital Human Creation (CC4 + ZBrush + Maya):**  
   A high-resolution portrait of Choi Jung-hoon was imported into *Character Creator 4 Headshot Plugin* to generate a 3D likeness.  
   The model was refined in **ZBrush** for anatomical accuracy, while **Maya** was used for **UV unwrapping, skin weighting, and rigging**.  
   Hair was designed using **CC4 Hair Builder**, and a wardrobe resembling his actual stage outfit was applied.  
   The completed rig—with textures, hair cards, and animations—was then exported to Unity.

2. **Voice Cloning (ElevenLabs):**  
   The artist’s voice was cloned using **ElevenLabs Instant Voice Cloning**, trained from his interview and performance audio.  
   Through the **ElevenLabs API**, the cloned voice dynamically generated speech responses inside Unity.

3. **Conversational AI Integration (ChatGPT API):**  
   **ChatGPT API** was embedded within Unity.  
   Audience speech—detected from the microphone—was converted into text input whenever its **decibel threshold** exceeded a set level.  
   This text was sent to the GPT model, which returned a real-time reply as text, immediately converted back into speech via ElevenLabs.  
   The resulting audio file was synchronized through Unity’s **lip-sync system**, creating the illusion of natural, responsive conversation.

4. **Sensor-Based Interaction (Azure Kinect):**  
   Using **Azure Kinect’s depth and skeleton tracking**, the AI human could detect and mimic the viewer’s physical gestures.  
   The system also rendered a **point cloud visualization** of the audience’s form, representing how the AI perceives human bodies as spatial data.

5. **Real-Time Rendering and Performance:**  
   All components—LLM interaction, voice synthesis, body tracking, and animation—were unified in **Unity’s real-time environment**,  
   producing a fully interactive digital persona capable of perceiving, responding, and performing.

---

## 🧩 Artistic & Research Focus  
The work reflects on **how AI and fans co-create identity**, transforming admiration into algorithmic embodiment.  
It questions whether a digital persona can express emotion, memory, or performance beyond imitation.  
By merging real-time AI conversation, motion sensing, and emotional mimicry, the project investigates **what it means to “meet” a synthetic human**—  
a reflection on connection, authorship, and affect in posthuman media.

---

## 🖼️ Media
<p align="center">
  <img src="./media/ChoiJungHoon_AI_01.jpg" width="20%" style="margin-right:5px;"/>
  <img src="./media/ChoiJungHoon_AI_02.jpg" width="20%" style="margin-right:5px;"/>
<!--  <img src="./media/ChoiJungHoon_AI_03.jpg" width="20%" style="margin-right:5px;"/>
  <img src="./media/ChoiJungHoon_AI_04.jpg" width="20%"/>-->
</p>

---

## 🎥 Video Documentation  

<!-- ✅ Vimeo Embed (for GitHub Pages or local preview) -->
<p align="center">
  <iframe src="https://player.vimeo.com/video/933305770?h=b3cef8f513" 
          width="640" height="360" frameborder="0" 
          allow="autoplay; fullscreen; picture-in-picture" 
          allowfullscreen 
          style="border-radius:10px;">
  </iframe>
</p>

<!-- ✅ Fallback Thumbnail (for GitHub site view) -->
<p align="center">
  <a href="https://vimeo.com/933305770/b3cef8f513" target="_blank">
    <img src="./media/ChoiJungHoon_Thumb.jpg" width="40%" style="border-radius:10px;"/>
  </a>
  <br>
  <em>Click to view full video on Vimeo</em>
</p>

---

## 👤 Credits  
**Technical Director:** Jonghoon Ahn  
**Year:** 2024  
**Institution:** California Institute of the Arts  
**Medium:** Interactive Media Installation  

---

## 🔗 Related  
- [Back to Digital Human & Virtual Beings](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
