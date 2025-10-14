# 🪞 NARCI / Be NARCI – Dual VR Experience on Narcissism  
*(XR Projects – 2023 · The Cave Seoul)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**NARCI** and **Be NARCI** form a dual VR installation exploring the psychological and emotional mechanics of **narcissism** through two opposing perspectives —  
the **victim** and the **perpetrator**.  

In **NARCI**, participants sit in a confined elevator-like space within **Meta Quest Pro**, surrounded by reflective surfaces that distort and multiply their image.  
Without controllers, they interact using natural hand tracking—touching virtual buttons and reaching toward fragmented reflections.  
The experience unfolds as a **cinematic narrative VR film**, combining slow-breathing spatial storytelling and AI-assisted voice design.  
Gaslighting dialogues and distorted self-images gradually dissolve the viewer’s identity until they face a final mirror, where healing begins.  

In **Be NARCI**, the participant stands and navigates freely through an open digital environment.  
Here, hand gestures allow users to **touch, control, or freeze** graceful human-like beings—transforming them into cold statues or metallic debris.  
Each act of domination triggers subtle environmental shifts: sounds distort, light fades, and empathy evaporates.  
Through this reversal, the player becomes both **creator and destroyer**, confronting the addictive power of control.  

Together, the two experiences expose **narcissism’s dual nature**—a cycle of manipulation and dependence, empathy and ego, victimhood and dominance.

---

## ⚙️ Technical Description  
- **Engine:** Unity (XR Interaction Toolkit · Hand Tracking)  
- **Language:** C#  
- **Rendering Pipeline:** URP  
- **Hardware:** Meta Quest Pro (Standalone + PCVR Mode)  
- **Software:** Blender · ZBrush · Substance Painter · Adobe Audition  
- **AI Tools:** ChatGPT API (narrative co-writing), ElevenLabs (AI voice synthesis)  
- **Pipeline:**  
  1. **Character and Environment**  
     - Modeled in **ZBrush** and **Blender**, textured in **Substance Painter**.  
     - Real-time reflections built using **Screen Space Reflection (SSR)** and custom mirror shaders.  
  2. **Interaction System (Hand Tracking)**  
     - No controllers; used **Meta Quest Pro’s hand-tracking API** for touch, pinch, and grab recognition.  
     - Player input mapped to Unity **XR Interaction Toolkit** custom gestures.  
  3. **Narrative Flow**  
     - Dialogue progression handled via **custom state machine** triggered by spatial zones.  
     - Integrated **AI-generated dialogue lines** from ChatGPT and ElevenLabs voices.  
  4. **Be NARCI Mechanics**  
     - Dynamic material transitions (skin → metal → stone) controlled via vertex shader blending.  
     - Physics state change system (rigid ↔ static) activated by hand collision triggers.  
  5. **Cinematic Lighting & Sound**  
     - Real-time lighting synchronization with ambient audio cues in **FMOD**.  
     - Elevator ambience designed for **spatial sound immersion** via Audition + FMOD integration.  
  6. **Dual Experience Integration**  
     - Both projects built within one repository branch under separate Unity scenes.  
     - Shared shader and voice assets managed via **Git version control** for collaborative updates.  

---

## 🧠 Artistic & Research Focus  
The **NARCI series** investigates how **narcissism manifests as both trauma and desire** in the digital age.  
By immersing the audience in both perspectives—the **manipulated** and the **manipulator**—the project turns  
psychological violence into an **embodied and spatial narrative**.  

It questions how **power, empathy, and identity** collapse when digital reflection replaces genuine emotion.  
Through silence, gaze, and mirrored interaction, *NARCI / Be NARCI* proposes that **healing begins not through dominance, but through recognition**.

---

## 🖼️ Media
<p align="center">
  <img src="./media/NARCI_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/NARCI_02.jpg" width="40%" style="margin-right:5px;"/>  
 <!-- <img src="./media/BeNARCI_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/BeNARCI_02.jpg" width="40%" style="margin-right:5px;"/>-->
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/1011881596/2770ac3b29">
    <img src="./media/NARCI_01.jpg" width="40%" style="border-radius:10px;"/>
  </a>
    <a href="https://vimeo.com/1107996077">
    <img src="./media/NARCI_02.jpg" width="40%" style="border-radius:10px;"/>
  </a>
</p>

---

## 👤 Credits  
**Artist / Developer:** Jonghoon Ahn  
**Year:** 2023  
**Exhibition:** The Cave Seoul  
**Platform:** Meta Quest Pro  
**Medium:** Dual VR Experience / Interactive Psychological Installation  

---

## 🔗 Related  
- [Back to Interactive VR Experience](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
