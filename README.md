# ✈️ Yield Prediction in Aircraft Wing Spar

An **interactive Streamlit web app** developed as part of the **ES 221** course project to predict yielding in an aircraft wing spar modeled as a **cantilevered I-beam**.  
Define custom distributed loads, compute stress distributions, and evaluate yielding using **von Mises** and **Tresca** criteria.

🔗 **Live Demo:** https://mosprojectgroup7.streamlit.app/

---

## 🚀 Features

- **Custom geometry input** — define spar length, total height, flange height & width, and web width  
- **Material properties** — set material yield strength  
- **Custom load definition** — enter symbolic expressions (e.g., `1000*x`) and specify the load segment range  
- **Structural analysis** — calculates shear force and bending moment diagrams  
- **Stress computation** — computes normal, shear, von Mises, and Tresca stresses across the cross-section  
- **Visual outputs** — interactive plots for load distribution, shear force, bending moment, and yield zones

---

## 🛠 How to Use

1. Enter the **yield strength** of the material.  
2. Specify spar geometry: length, total height, flange height & width, and web width.  
3. Define the distributed load as a symbolic expression (for example `1000*x`) and set the limits of the load segment.  
4. Click **Calculate** to generate stress distributions and yield contour plots.

---

## 📊 Output Visualizations

- **Load Distribution** — graph of the applied load along the beam  
- **Shear Force Diagram** — V(x) variation along the spar  
- **Bending Moment Diagram** — M(x) variation along the spar  
- **Von Mises & Tresca Maps** — contour plots highlighting yielding regions  
- **Normal & Shear Stress Maps** — cross-sectional stress distributions

---

# Contributors
- Mukesh Dewangan
- Sai Gawali
- Siddhesh Patil
- Kushagra Shahi
- Vivek Kumar
