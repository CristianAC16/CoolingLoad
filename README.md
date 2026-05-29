# Restaurant HVAC Cooling Load Calculation (Montreal — July Design)

## Project Summary
This project calculates the **peak summer cooling load** for a **4,150 ft² restaurant** in Montreal using a **July design day**.  
The building is divided into six zones, and all major load components were evaluated: conduction, solar gains, people, lighting, equipment, infiltration, and ventilation.

**Final Result:**  
**Total Cooling Load = 238,846 BTU/hr ≈ 20 tons**

---

## Building & Zones
- Single‑story restaurant  
- Ceiling height: 10 ft  
- **Zones:** Dining, Kitchen, Storage/Prep, Walk‑In Cooler, Washrooms, Entrance/Lobby

**Insert image:**  
<img src="https://i.imgur.com/zdNXy5j.png" height="100%" width="100%" alt="Floor Plan"/>

---

## Design Conditions
### Outdoor (July — Montreal)
- Humidity ratio: **W₁ = 0.0162 lb/lb**

### Indoor
- Dining / Lobby: **75°F**, 50% RH  
- Kitchen: **80°F**  
- Storage / Washrooms: **75°F**  
- Humidity ratio: **W₃ = 0.0094 lb/lb**

---

## 🪟 Glazing & Solar
### Dining Room Windows
- Size: **10 ft × 5 ft**  
- Type: **Double insulating glass (3 mm + air + 3 mm)**  
- Solar transmission / SC: **0.76**  
- Interior shading: **None**  
- Peak solar hour used: **4 PM**

### Entrance Window
- Size: **5 ft × 5 ft**  
- SC: **0.76**

**Insert image:**  
`![Window Layout](images/windows.png)`

---

## Ventilation & Infiltration
- Dining: **1,600 CFM**  
- Kitchen: **120 CFM**  
- Storage: **60 CFM**  
- Washrooms: **50 CFM**  
- Lobby: **140 CFM**  
- Infiltration: **0.5 ACH**

Latent ventilation load:  


\[
Q_{lat} = 4840 \cdot \text{CFM} \cdot (W_{out} - W_{in})
\]



---

## 📊 Zone Load Summary

| Zone | Total Load (BTU/hr) |
|------|----------------------|
| Dining Area | **178,921** |
| Commercial Kitchen | **33,370** |
| Storage / Prep | **7,082** |
| Walk‑In Cooler | **1,054** *(conduction only — product load not considered)* |
| Washrooms | **4,763** |
| Entrance / Lobby | **13,655** |
| **Total** | **238,846 BTU/hr ≈ 20 tons** |

**Insert image:**  
`![Zone Load Table](images/zoneloads.png)`

---

## Key Notes
- Solar loads calculated using SHGF tables; **peak hour only** included.  
- Ventilation latent load is high due to July humidity — typical for restaurants.  
- Walk‑in cooler **product load excluded** (handled by its own refrigeration system).  
- Final system recommendation: **20‑ton cooling capacity**.

---

## Suggested Images to Include
- `images/floorplan.png` — Zone layout  
- `images/windows.png` — Window placement & sizes  
- `images/glazing.png` — Glass type (3 mm + air + 3 mm)  
- `images/solarcalc.png` — Solar load example  
- `images/psychrometrics.png` — Ventilation latent calc  
- `images/zoneloads.png` — Final load table  

---

## Conclusion
This project demonstrates a complete, realistic HVAC cooling load calculation for a multi‑zone restaurant using July design conditions.  
The final peak cooling load is **~20 tons**, driven mainly by dining room solar gains and ventilation latent loads.
