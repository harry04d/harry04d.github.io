---
title: "Wing Design"
permalink: /wing-design/
date: 2025-09-06
categories: [projects]
tags: [VTOL, UAV, Aerodynamic Analysis]
excerpt: "A design for a glider wing for a lightweight VTOL, the wing is designed to ensure distance travelled and weight carrying requirements."
---

# Wing Design Report  

## 1. Introduction  
The purpose of this report is to document the aerodynamic design and analysis of a wing for a small-scale vertical take-off and landing (VTOL) aircraft. The wing is a critical component for enabling efficient gliding, reducing power consumption during spraying operations, and maintaining flight stability under varying payload conditions.  

---

## 2. Airfoil Selection  
The Reynolds number for typical low-altitude gliding operation was calculated as **170,000**, which is expected for small UAV applications. Airfoil selection at this low Reynolds number is crucial to achieving sufficient lift and maintaining aerodynamic efficiency.  

The airfoil requirements were defined as follows:  

- Operate effectively at **low Reynolds numbers** for low-speed flight.  
- Provide a **high lift-to-drag ratio** to maximise gliding efficiency.  
- Be **thin and lightweight** to minimise overall structural weight.  
- Exhibit a **high stall angle** to tolerate gusts and enable safe take-off.  

Based on these design criteria, the **Selig S1123** airfoil was selected. This airfoil provides a favourable lift-to-drag ratio, strong performance in low-Reynolds regimes, and a stall margin suitable for agricultural UAV use.  

![Selig S1123 Airfoil Data Charts](/assets/images/Selig.jpg)

---

## 3. Glide Ratio and Angle of Attack Analysis  

### 3.1 Aircraft Mass and Weight  
The maximum operational weight was determined under full payload conditions:  

- Pesticide payload: **20.0 kg**  
- Aircraft structure: **3.89 kg**  
- Components: **1.11 kg**  
- **Total mass = 25.0 kg**  

The total weight is therefore:  


### 3.2 Coefficient of Lift Calculation  
At a glide velocity of **18 m/s** and wing area of **0.7 m²**, the required lift coefficient is:  


A coefficient of lift of 1.76 is achievable with the Selig S1123 airfoil. Reference to its **CL–α curve** shows that this corresponds to an angle of attack of approximately **5°**, which also coincides with the airfoil’s maximum lift-to-drag ratio.  

---

## 4. Drag Estimation and Glide Ratio  

### 4.1 Drag Components  
The total drag coefficient was estimated by combining induced and parasitic drag values:  

- Induced drag coefficient: **CDᵢ = 0.019**  
- Parasitic drag coefficient: **CD₀ = 0.020** (based on comparable UAVs and gliders)  


### 4.2 Glide Ratio  
The aerodynamic efficiency of the wing can be expressed as the lift-to-drag ratio:  


This indicates that the aircraft will descend only **1 m for every 45 m travelled horizontally**, a glide performance comparable to that of high-performance sailplanes.  

---

## 5. Conclusion  
The wing design, based on the Selig S1123 airfoil, satisfies the aerodynamic requirements for the VTOL aircraft. The airfoil’s suitability for low Reynolds numbers, combined with its high lift-to-drag ratio, enables efficient gliding under maximum payload conditions.  

The analysis demonstrates:  

- A required coefficient of lift of **1.76**, achievable at an angle of attack of **5°**.  
- A total drag coefficient of **0.039**.  
- A resulting glide ratio of approximately **45**, allowing extended endurance and efficient coverage during spraying operations.  

This confirms that the selected airfoil and wing configuration provide the aerodynamic performance necessary for the UAV’s intended agricultural role.  

