# 🎨 Picasso – AR Self-Portrait Experiment  
*(AR-based Style Transfer Project – 2021)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Picasso** is an augmented reality experiment that reinterprets the human face through **neural style transfer** inspired by the paintings of **Pablo Picasso**.  
The project transforms the viewer’s live self-portrait into a **cubist and fragmented abstraction**, allowing users to experience how identity and artistic style interact in real time.  

By combining AI-driven image synthesis with AR visualization, the work examines how technology can reconstruct self-perception—  
turning the camera into both a mirror and a painter’s brush.

---

## ⚙️ Technical Description  
- **Engine:** Unity  
- **Framework:** AR Foundation  
- **Software:** Blender · Photoshop (for dataset preparation)  
- **Language:** C# · Python  
- **AI Model:** Neural Style Transfer (TensorFlow-trained, Unity Barracuda runtime)  
- **Hardware:** iPhone 12 (ARKit)  
- **Pipeline:**  
  1. Train a neural style transfer model on Picasso’s painting dataset using TensorFlow  
  2. Convert the trained model into **ONNX** format and import via **Unity Barracuda**  
  3. Capture real-time facial input through AR Foundation (WebCamTexture → RenderTexture)  
  4. Apply style transformation in real time using GPU inference  
  5. Render stylized output as an AR overlay with gesture-based intensity control  

---

## 🧠 Artistic & Research Focus  
The project explores **the boundaries between identity, authorship, and perception** in the context of real-time AI.  
By transforming one’s own face through cubist abstraction, **Picasso** questions how artistic style can reshape self-image and extend the idea of portraiture into computational form.  
It transforms the act of seeing into an act of painting—performed collaboratively between human and machine.  

---

## 🖼️ Media
<p align="center">
  <img src="./media/Picasso_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/Picasso_02.jpg" width="40%" style="margin-right:5px;"/>
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/your-video-link-here">
    <img src="./media/Picasso_Thumb.jpg" width="40%" style="border-radius:10px;"/>
  </a>
</p>

---

## 💻 Implementation Notes  
- **Model:** Fast Neural Style Transfer (Johnson et al.)  
- **Barracuda Execution:** GPU inference using Compute Shader backend  
- **Optimization:** Half-precision texture for mobile performance  
- **Latency:** ~18–22ms/frame on iPhone 12 (ARKit pipeline)  
- **Output:** Real-time stylized self-portrait overlay with dynamic line and color adaptation  

---

## 👤 Credits  
**Artist / Developer:** Jonghoon Ahn  
**Year:** 2021  
**Institution:** Kookmin University  
**Medium:** AR-based Neural Style Transfer  

---

## 🔗 Related  
- [Back to AR-based Style Transfer](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
