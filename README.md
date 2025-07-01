# Aerodynamic Tiny Minivan Concept (QuadriCycle) – Electric Cargo Vehicle

## Overview

This project explores aerodynamic optimization for a compact **electric minivan** designed to carry **large cargo** while minimizing drag. The vehicle features a **streamlined body** with experimental flow control techniques to enhance aerodynamic efficiency, especially important for electric vehicles where range and energy usage are critical.

## Vehicle Dimensions

- **Width:** 1500 mm  
- **Length:** 4250 mm  
- **Height:** 1200 mm  
- **Type:** Electric Minivan (Low-profile, large cargo volume)
- Tires with only 155mm width
- The car is still a boxy design which is easy to load 

## Aerodynamic Design Highlights

### 1. **Streamlined Profile**
- The overall shape has been tapered and smoothed to reduce flow separation drag.
- Roofline and underbody are optimized for attached flow at moderate highway speeds.


### 2. **High-Pressure Redirection**
- Instead of a traditional front radiator, the **high-pressure airflow** is redirected **downward** through the front intake area.
- This redirected flow energizes the **underfloor boundary layer**, helping reduce wake turbulence and improving underbody flow characteristics.

### 3. **Strake Integration**
- A series of **strakes (aerodynamic fins)** are strategically placed under the floor.
- These help **re-energize the flow**, manage vortex structures, and improve ground effect stability.

### 4. **Canopy and Rear Flow Refinement**
Numerous iterations of the canopy’s rear end were evaluated to reduce wake recirculation and drag while improving flow attachment.


## Goals & Benefits

- Reduce overall **drag coefficient** (Cd) to improve electric range.
- Maintain **large cargo space** without compromising aerodynamic efficiency.
- Demonstrate alternative front-end design strategies in EVs (no large cooling requirement).
- Cr down to 0.180
- Drag: 130.2N at 25m/s-1 (90 kph), Drag Power: 3255W
- Drag: 266.0N at 36m/s-1 (130 kph), Drag Power: 9577W


---

## Repository Structure

- `/docs` — Design notes, ideas, and simulation logs
- `/models` — FreeCAD files for each design iteration
- `/stl` — STL files for each CFD simulation 
- `/images` — Visualizations from CFD simulations

---

## Tools Used

- **CAD:** FreeCAD 1.0.x  
- **CFD:** InsightCAE (OpenFOAM-based)

## Simulation Screenshots

Here are some CFD simulation screenshots from various design iterations:

![Screenshot 2025-06-14 091352](images/Screenshot%202025-06-14%20091352.png)  
![Screenshot 2025-06-13 211135](images/Screenshot%202025-06-13%20211135.png)  
![Screenshot 2025-06-13 210509](images/Screenshot%202025-06-13%20210509.png)  
![Screenshot 2025-06-13 162620](images/Screenshot%202025-06-13%20162620.png)  
![Screenshot 2025-06-13 162607](images/Screenshot%202025-06-13%20162607.png)  
![Screenshot 2025-06-12 100539](images/Screenshot%202025-06-12%20100539.png)  
![Screenshot 2025-06-12 100433](images/Screenshot%202025-06-12%20100433.png)  
![Screenshot 2025-06-12 100205](images/Screenshot%202025-06-12%20100205.png)  
![Screenshot 2025-06-12 100155](images/Screenshot%202025-06-12%20100155.png)  
![Screenshot 2025-06-11 235054](images/Screenshot%202025-06-11%20235054.png)  
![Screenshot 2025-06-11 234823](images/Screenshot%202025-06-11%20234823.png)  
![Screenshot 2025-06-11 233728](images/Screenshot%202025-06-11%20233728.png)  
![Screenshot 2025-06-10 192857](images/Screenshot%202025-06-10%20192857.png)  
![Screenshot 2025-06-10 192725](images/Screenshot%202025-06-10%20192725.png)  
![Screenshot 2025-06-10 192540](images/Screenshot%202025-06-10%20192540.png)  
![Screenshot 2025-06-09 102752](images/Screenshot%202025-06-09%20102752.png)  
![Screenshot 2025-06-09 102557](images/Screenshot%202025-06-09%20102557.png)  
![Screenshot 2025-06-08 235350](images/Screenshot%202025-06-08%20235350.png)  
![Screenshot 2025-06-08 205318](images/Screenshot%202025-06-08%20205318.png)  
![Screenshot 2025-06-08 205301](images/Screenshot%202025-06-08%20205301.png) 
![Screenshot 2025-06-08 205247](images/Screenshot%202025-06-08%20205247.png)



## License

This project is shared under the MIT License. Feel free to use and contribute.

---

*This is an experimental project aimed at rethinking minivan design in the electric era, blending utility with efficiency.*
