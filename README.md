# Office-Block-Generator_Grasshopper
## ✨ Key Features

### ✅ Automatic Office Layout Generation
- Supports multiple plot scales (**1–4 ha**, **4–9 ha**, and large composite plots)
- Includes various **street/block patterns** for each scale

### ✅ Parametric Control
- **Planning Indicators:**  
  - Floor Area Ratio (**FAR**)  
  - Building coverage  
  - Setbacks  
- **Morphological Controls:**  
  - Secondary subdivision  
  - Building depth/width  
  - Tower size ranges  

### ✅ Adaptive Logic
- Automatically detects **plot geometry**
- Generates **context-sensitive patterns** based on open space and buildable area distribution

---

## 📦 Plugin Components
The plugin consists of **three main Grasshopper scripts (clusters):**

1. **Small-Scale Block Generator**  
   - Plot size: **1–4 hectares**  
   - Includes **3 block pattern options**

2. **Medium-Scale Block Generator**  
   - Plot size: **4–9 hectares**  
   - Includes **3 block pattern options**

3. **Large-Scale Composite Generator**  
   - Combines small plots into larger ones (**3×2 arrangement**)  
   - Adapts to **open space and buildable area** for **2 pattern options**

---

## 🛠 How to Use
1. **Download and unzip** the repository  
2. Open **Grasshopper in Rhino**  
3. Load the corresponding **`.gh` definition**  
4. **Input your plot boundary curve**  
5. **Adjust sliders** to generate and customize building layouts in real time  

---

## 📋 Adjustable Parameters

### **Planning Indicators**
- Floor Area Ratio (**FAR**)
- Building coverage
- Setback distances

### **Morphological Controls**
- Subdivision strategy
- Building types (slab, tower) depth and width
- Tower height range
