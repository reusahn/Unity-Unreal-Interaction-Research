# 🌈 Erin Collaboration – Real-Time AR Style Filter  
*(Interactive AI Photo Studio – 2024)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Erin Collaboration** is an interactive photo installation that recreates the distinctive **animation style of artist Erin** as a real-time AR filter within **Unity**.  
The system detects the human subject through segmentation and transforms only the person into Erin’s visual style, while preserving the **real-world background** as is.  
This hybrid rendering technique creates a striking contrast between **stylized character and realistic environment**, blurring the boundary between animation and reality.  

Visitors can instantly print their transformed portraits within the installation, turning the space into a **live AI photo studio** where technology, illustration, and human presence coexist.  

---

## ⚙️ Technical Description  
- **Engine:** Unity  
- **Framework:** AR Foundation  
- **Software:** Blender · Photoshop  
- **Language:** C# · Python  
- **AI Model:** Neural Style Transfer (TensorFlow-trained, exported as ONNX, Unity Barracuda runtime)  
- **Hardware:** PC (NVIDIA RTX 4090), DSLR Camera, Photo Printer  
- **Pipeline:**  
  1. Collect and preprocess Erin’s animation-style dataset  
  2. Train neural style transfer model in TensorFlow and export to ONNX  
  3. Integrate ONNX model into Unity via **Barracuda** for real-time inference  
  4. Perform background segmentation using AR Foundation human stencil buffer  
  5. Apply stylization only to segmented human regions while maintaining real-world background  
  6. Generate high-resolution frames and automatically print portraits upon capture  

---

## 🧠 Artistic & Research Focus  
The project investigates how **AI can extend an artist’s visual identity** through real-time computation.  
By transforming the human subject into Erin’s animated aesthetic, the installation redefines portraiture as **a shared act between human and algorithmic authorship**.  

It reflects on how **style becomes a living, generative filter**, allowing viewers to witness themselves through the language of another artist—  
revealing the emotional resonance that emerges when **artistic authorship meets machine perception**.  

---

## 🖼️ Media
<p align="center">
  <img src="./media/Erin_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/Erin_02.jpg" width="40%" style="margin-right:5px;"/>
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/your-video-link-here">
    <img src="./media/Erin_Thumb.jpg" width="40%" style="border-radius:10px;"/>
  </a>
</p>

---

## 💻 Implementation Notes  
- **Segmentation:** AR Foundation Human Stencil Buffer  
- **Model Runtime:** Unity Barracuda (ONNX model inference)  
- **Optimization:** Half-precision GPU inference for mobile and real-time AR performance  
- **Output:** 1080p stylized portrait stream with automatic print integration  

---

## 👤 Credits  
**Collaborating Artist:** Erin  
**Technical Director:** Jonghoon Ahn  
**Year:** 2024  
**Institution:** California Institute of the Arts  
**Medium:** Interactive AI Photo Installation  

---

## 🔗 Related  
- [Back to AR-based Style Transfer](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

