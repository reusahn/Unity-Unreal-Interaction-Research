# 📷 Jemulpo Photo Studio  
*(Interactive Media Installation – 2022 · Incheon Metropolitan Museum)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**Jemulpo Photo Studio** is an interactive media installation that reimagines the aesthetics of early Korean **“New Women” magazine culture** from the colonial era.  
Visitors’ portraits are captured in real time and **transformed through AI-based face swapping and neural style transfer**,  
producing reinterpreted covers that blend modern identity with early 20th-century visual modernity.  

Each portrait—stylized in the vibrant, liberated tone of Jemulpo’s early photo studios—is automatically framed, displayed, and archived in real time on a virtual wall,  
turning the gallery into a **living archive of self-modernization and historical reinterpretation**.

---

## ⚙️ Technical Description  
- **Engine:** Unity  
- **Framework:** AR Foundation · OpenCV for Unity  
- **Software:** Photoshop · After Effects (graphic composition)  
- **Languages:** C# · Python  
- **AI Frameworks:** Unity Barracuda (segmentation) · OpenCV (face detection & swap)  
- **Hardware:** PC (NVIDIA RTX 4070 Super) · DSLR Camera · Display Monitors  
- **Networking:** TCP Server for live data and image archiving  

### 🧩 Pipeline  
1. **Face Capture & Detection**  
   - Real-time facial detection using **OpenCV DNN** models integrated in Unity.  
   - Extended detection region to include **hair and head area** via post-processing on facial landmarks, ensuring style transformation affects full portrait.  
2. **Face Swap & Style Mapping**  
   - Implemented a custom **face-swap system** merging visitor features with pre-designed 1920s “New Women” portrait references.  
   - Style filters layered through custom **shader-based watercolor and pointillist noise blending**, referencing early magazine printing textures.  
3. **Artistic Style Assets**  
   - Illustrated base templates by **Yu Soohyun**, inspired by “New Women” visual language and reinterpreted for both male and female figures.  
   - **Junsoo Ha** collaborated on historical art direction and layout curation.  
4. **Segmentation & Background Replacement**  
   - Applied **Unity Barracuda-based person segmentation** to separate subjects from background.  
   - Replaced the backdrop with **vintage magazine-style layouts** dynamically mapped to color palettes extracted from 1920s Korean publications.  
5. **Archiving & Exhibition Display**  
   - Generated portraits sent via **TCP connection** to an external display wall,  
     where results appeared in a looping slideshow simulating a virtual photo gallery.  
   - All portraits auto-saved in timestamped folders for archival record and curatorial review.  

---

## 🧠 Artistic & Research Focus  
This project investigates how **historical aesthetics can be reactivated through AI and real-time media art**.  
By merging colonial-era “New Women” imagery with contemporary digital interfaces,  
the installation creates a space where visitors can **temporarily inhabit a reimagined past**,  
exploring the interplay between **gender, modernization, and visual media**.  

The live archiving process reflects on photography’s role as both documentation and performance—  
turning spectators into **participants of a digitally reconstructed modern history**.

---

## 🖼️ Media
<p align="center">
  <img src="./media/Jemulpo_01.jpg" width="40%" style="margin-right:5px;"/>  
  <img src="./media/Jemulpo_02.jpg" width="40%" style="margin-right:5px;"/>
</p>

---

## 🎥 Video Documentation
<p align="center">
  <a href="https://vimeo.com/1011870114/e6a92f4ef4" target="_blank">
    <img src="./media/Jemulpo_03.jpg" width="40%" style="border-radius:10px;"/>
  </a>
  <br>
  <em>Click to view full video on Vimeo</em>
</p>

---

## 👤 Credits  
**Technical Director:** Jonghoon Ahn  
**Collaborating Artist:** Junsoo Ha  
**Illustrator:** Yu Soohyun  
**Year:** 2022  
**Exhibition:** Incheon Metropolitan Museum  
**Medium:** Interactive Art Installation  

---

## 🔗 Related  
- [Back to AR-based Style Transfer](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)
