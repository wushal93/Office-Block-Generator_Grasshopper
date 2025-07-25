# 🏙 High-Density Office Block Generator for Grasshopper

![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)
![Grasshopper](https://img.shields.io/badge/platform-Grasshopper-green)

A **Grasshopper-based parametric tool** for **automated generation of high-density office building layouts** across multiple plot scales. The generator automatically detects plot geometry and applies **context-sensitive patterns**, allowing designers to customize layouts through a wide range of **planning and morphological parameters**.

---

## ✨ Key Features

### ✅ Automatic Office Layout Generation
- Supports multiple plot scales (**1–4 ha**, **4–9 ha**, and large composite plots)
- Includes **multiple street/block patterns** for each scale

### ✅ Parametric Control
- **Planning Indicator:**  
  - Floor area ratio 
  - Building Density
- **Morphological Controls:**  
  - Secondary subdivision 
  - Building typology
  - Building depth/width/Height Control 

### ✅ Adaptive Logic
- Automatically detects **plot geometry**
- Generates **context-sensitive patterns** based on open space and buildable area distribution

---

## 📦 Plugin Components
The plugin includes **three main Grasshopper clusters**:

1. **Small-Scale Block Generator**  
   - Plot size: **1–4 hectares**  
   - Includes **3 block pattern options**
> Small-Scale Block Generator
<img width="4111" height="1572" alt="single block( 4ha)" src="https://github.com/user-attachments/assets/e9d86660-7d6c-4776-bc64-c90dff609a83" />



2. **Medium-Scale Block Generator**  
   - Plot size: **4–9 hectares**  
   - Includes **3 block pattern options**
> Medium-Scale Block Generator
<img width="4037" height="1883" alt="single block(4 9ha)" src="https://github.com/user-attachments/assets/ab66e4d2-370c-4dc9-bf66-74d4b4a2606d" />


3. **Large-Scale Composite Generator**  
   - Combines small plots into larger ones (**3×2 arrangement**)  
   - Adapts to **open space and buildable area** for **2 pattern options**
> Large-Scale Composite Generator
<img width="4065" height="2016" alt="multiple block( 9ha)" src="https://github.com/user-attachments/assets/228f5aa7-edc5-409e-8b32-f4d87abc1678" />


---

## 🛠 How to Use
1. **Download and unzip** the repository  
2. Open **Grasshopper in Rhino 8**  
3. Load the corresponding **`Office Block Generator.gh` definition**  
4. **Input your plot boundary curve by defining Set-edge points**  
5. **Adjust grid size(x,y) by sliders** to generate and customize building layouts in real time  

---

## 🖼 Screenshots
> Small-Scale Block Generator   
Example:  
![single block(1 5~4ha)](https://github.com/user-attachments/assets/0c7557ff-27e2-456c-a577-7c6cc4aac4a2)

> Medium-Scale Block Generator   
Example:
![single block(4~9ha)](https://github.com/user-attachments/assets/b53a47dc-159e-4e3f-8baf-cd3fc5d8e985)

> Large-Scale Composite Generator   
Example:
![multiple block](https://github.com/user-attachments/assets/76d6ddb4-9a94-4c58-a10d-356a8a90e6bf)


---

## 📋 Adjustable Parameters

### **Planning Indicators**
- Floor Area Ratio (**FAR**)
- Setback distances(**L(setback)**)

### **Morphological Controls**
- Division of Parcels: **L(parcel),S(parcel)**
- Building types (Courtyard, Slab, Tower) depth and width: **W(Tb),D(Tb),D(Cb),S(Cb)**
- Tower height range:**Floor_Start_Tower, Floor_Step**
- Distribution of Built& Open space: **Parcel_sel**

>variables
<img width="1191" height="641" alt="variables" src="https://github.com/user-attachments/assets/0aecb849-cf27-4da2-b335-acc0d39daa43" />


---

## 📄 License
This project is licensed under the **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)** license.

![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)

---

## 📚 Citation
If you use this work in research or publications, please cite:
> Wusihala, W., & Wang, P. (2025). High-Density Office Block Generator for Grasshopper (Version 1.0.0) [Computer software]. GitHub. https://github.com/YourUsername/HighDensityOfficeMorphology

Or see the [CITATION.cff](./CITATION.cff) file for more formats.

---

