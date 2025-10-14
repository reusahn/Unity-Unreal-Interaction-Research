# 💠 Fineo – Translated Universe / Constructed Material World  
*(Data Visualization & VR Installation – 2019 · Grand Prize, 16th Kookmin University Art & Design Exhibition)*  

[← Back to main repository](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)

---

## 🧩 Overview  
**«Fineo»** is a **data visualization and VR installation** that reconstructs the periodic table into a *harmonic artificial universe*.  
By transforming numerical data into light, motion, and geometry, the project imagines a **mechanistic world** where science and art converge into one generative system.  

Awarded the **Grand Prize** at the 16th Kookmin University Art & Design Exhibition,  
*Fineo* translates the atomic structures of elements into living, mathematical forms —  
each rendered as a **harmonograph** that evolves into molecular and planetary compositions.  
The result is a speculative cosmology, where data is not simply measured but **experienced** as rhythm and emotion.  

---

## ⚙️ Technical Description  
- **Engines:** Unity (VR SDK · WebGL)  
- **Languages:** C# · Processing · JavaScript  
- **Software:** Processing · Blender · After Effects · TouchDesigner · Excel  
- **Hardware:** PC (NVIDIA RTX 4070 Super) · HTC Vive / Meta Quest · Projection System  
- **Pipeline:**  
  1. **Data Collection** – Extract atomic radius, valence, mass, and period from the periodic table.  
  2. **Mathematical Visualization** – Map numerical data to variables in **harmonograph equations**:  

     ```text
     x = Σ(Axₙ sin(tfxₙ + pxₙ)e⁻ᵈˣⁿ/ᵗ)
     y = Σ(Ayₙ sin(tfyₙ + pyₙ)e⁻ᵈʸⁿ/ᵗ)
     z = Σ(Azₙ sin(tfzₙ + pzₙ)e⁻ᵈᶻⁿ/ᵗ)
     ```
     where  
     - Damping ↔ Atomic Number  
     - Frequency ↔ Group  
     - Amplitude ↔ Atomic Radius  
     - Phase ↔ Electronegativity  

  3. **Generative System (Processing)** – Points drawn in 3D as spatial strings over time, forming “finitium” (element).  
  4. **VR World Construction** – Elements combine into molecules (*finecula*), molecules into planetary clusters.  
  5. **Visualization Layers** – Particle trails, constellations, and wave interference patterns simulate cosmic expansion.  
  6. **Interactive Exhibition** – VR exploration with navigation system; projection and holographic display for audiences.  

---

## 🧠 Artistic & Research Focus  
Rooted in **Descartes’ mechanistic worldview**, *Fineo* explores how numerical logic can give birth to poetic form.  
It treats data as matter and equations as space — a **constructed nature** born from information itself.  

Through **harmonograph equations** and **procedural visualization**,  
the project bridges philosophy, physics, and media art, redefining scientific abstraction as **emotional geometry**.  
Participants experience a living system where data oscillates, decays, and harmonizes —  
a translation of **logic into motion, number into presence**.  

> “미시세계의 시각화를 위한 방법론을 다양한 매체에 적용시키며  
> 자랄 수 있는 모든 가지를 뻗어나가게 하는 것이 본 프로젝트의 핵심 가치이다.”  

---

## 💫 Conceptual Structure  

data ≈ finitium ✱ fineom ∷ finecula ◊ planet ∞ solar system


| Symbol | Concept | Description |
|:------:|:---------|:-------------|
| `≈` | **Data** | Fundamental numerical input — the code of existence. |
| `✱` | **Finitium** | Element — generated through harmonograph equations. |
| `∷` | **Finecula** | Molecule — spatial connection of atomic harmonics. |
| `◊` | **Planet** | Molecular aggregation forming orbiting systems. |
| `∞` | **Expansion** | The continuous evolution into a constructed material world. |

---

## 💻 Example Code (Processing)

int num = 3; 
float[] radius = {25, 28, 145, 105, 85, 70, 65, 215};
float a = radius[num-1];
float f = num * 0.15;
float t = 0;

void draw() {
  background(0);
  beginShape();
  for (int i = 0; i < 2000; i++) {
    float x = a*sin(t*f+PI/3)*exp(-0.002*t);
    float y = a*sin(t*f+PI/4)*exp(-0.002*t);
    float z = a*sin(t*f+PI/6)*exp(-0.002*t);
    stroke(200, 255, 255);
    vertex(x, y);
    t += 0.001;
  }
  endShape();
}

Each visualized atom (“finitium”) emerges as a living harmonic form generated from elemental data.

## 🖼️ Media  
| ![Fineo_01](./media/Fineo_01.jpg) | ![Fineo_02](./media/fineo_02.jpg) | ![Fineo_03](./media/fineo_03.jpg) |
|:--:|:--:|:--:|
| Fineo Visual 1 | Fineo Visual 2 | Fineo Visual 3 |

---

## 🎥 Video Documentation  
[![Watch on Vimeo](./media/Fineo_01.jpg)](https://vimeo.com/666371092/5759d8c3ae)

---

## 👤 Credits  
- **Artists / Developers:** Geum Jaesung · Jonghoon Ahn · Yu Hwanjun  
- **Collective:** 초코로로딩 (Choco Loading)  
- **Year:** 2019  
- **Institution:** Kookmin University, College of Design  
- **Award:** Grand Prize, 16th Art & Design Exhibition  
- **Medium:** Data Visualization · VR Installation · Generative Art  

---

## 🔗 Related  
- [Back to Interactive VR Experience](../README.md)  
- [View All Projects](https://github.com/reusahn/Unity-Unreal-Interaction-Research/tree/main)


