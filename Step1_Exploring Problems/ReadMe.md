# Step 1: Exploring the Problem

## Restating the Problem
The goal is to design a safety system that ensures railway crossing gates are lowered whenever a train is approaching or a vehicle is still on the track, and only raised once it is completely safe. The system should be built with simple, intuitive logic using Boolean operations and digital logic gates.

---

## Inputs and Outputs of the System

### Inputs
- **Train Approaching (yes/no)** — Detects if a train is near the crossing.  
- **Vehicle on Track (yes/no)** — Detects if a vehicle is stuck or present on the crossing.  
- **System Control (on/off)** — Determines whether the safety system is active.  

### Outputs
- **Gate Raised (yes/no)**  
- **Gate Lowered (yes/no)**  

---

## Context
The crossing is located in a busy traffic area. The system must prevent accidents by lowering gates whenever a train is approaching or when vehicles are on the track. Gates can only be raised when both the train and vehicle sensors confirm the crossing is clear.

---

## Constraints
- **Technical**: Sensors must accurately detect both trains and vehicles.  
- **Economic**: Must be cost-effective enough to install at multiple crossings.  
- **Social**: Easy for the public to understand and trust; minimal complexity for operators.  
- **Environmental**: Must function reliably in extreme weather conditions.  
- **Legal**: Must comply with official railway safety regulations.  

---

## Stakeholders
- Local government authorities  
- Railway operators  
- Pedestrians and vehicle drivers  
- Maintenance and safety teams  

