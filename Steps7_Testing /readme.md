# Step 7: Testing and Refinement

## Truth Table
(See separate file for full truth table diagram)

---

## Test Cases

### Test Case 1: Train Approaching, No Vehicle on Track
- **Input**: Train detected, no vehicle detected.  
- **Expected Output**: Gates lowered, warning signals activated.  
- **Actual Output**: (recorded in separate file)  

### Test Case 2: Vehicle on Track, No Train Approaching
- **Input**: Vehicle detected, no train detected.  
- **Expected Output**: Gates lowered, warning signals activated.  
- **Actual Output**: (recorded in separate file)  

### Test Case 3: Train Approaching and Vehicle on Track
- **Input**: Train detected, vehicle detected.  
- **Expected Output**: Gates lowered, warning signals activated.  
- **Actual Output**: (recorded in separate file)  

### Test Case 4: No Train, No Vehicle
- **Input**: No train detected, no vehicle detected.  
- **Expected Output**: Gates remain raised, no warning signals.  
- **Actual Output**: (recorded in separate file)  

---

## Refinements and Suggestions
- **Add Warning Signals**: Ensure lights and/or bells activate whenever the gate is lowered (G = 1). This increases user awareness and system safety.  
- **Weather Adaptation**: Introduce radar or ultrasonic sensors as backup to infrared sensors, improving detection accuracy in fog, rain, or snow.  
- **Maintenance Schedule**: Regularly test and calibrate sensors to ensure long-term reliability.  

