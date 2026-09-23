# TSMASTER-C-MINI-PROGRAM-FOR-INTERIOR-LIGHT-CONTROL

## AIM: Develop a TSMaster C Mini Program to Control the Interior Light Based on Vehicle Door Status

---

## Apparatus Required

| S. No. | Apparatus / Software | Specification |
|:---:|---|---|
| 1 | PC / Laptop | For TSMaster configuration |
| 2 | Software | **TSMaster** |
| 3 | CAN Interface | **CAN Interface / CAN Simulator** |
| 4 | CAN Database | **DBC File** |
| 5 | Programming Environment | **TSMaster C Mini Program** |
| 6 | Input Signals | **Door-Status CAN Signals** |
| 7 | Output Signal | **Interior-Light Signal** |
| 8 | Dashboard Controls | For signal simulation and monitoring |

---

## Procedure

1. Open the **TSMaster** project and load the required DBC file.
2. Identify the CAN signals corresponding to the **four vehicle doors**.
3. Create or open a **C Mini Program** in TSMaster.
4. Read the status of the four door signals.
5. Implement the control logic for the interior light.
6. Turn the **interior light ON** when at least one door is open.
7. Turn the **interior light OFF** when all doors are closed.
8. Compile the C Mini Program and resolve any compilation errors.
9. Start the C Mini Program and CAN communication.
10. Apply different combinations of **door-open and door-closed** inputs.
11. Observe the corresponding **interior-light output**.
12. Verify that the output matches the expected control logic.

---

## Control Logic

| Door Status | Interior Light |
|---|---|
| All doors closed | **OFF** |
| Front Left Door open | **ON** |
| Front Right Door open | **ON** |
| Rear Left Door open | **ON** |
| Rear Right Door open | **ON** |
| Any combination with at least one door open | **ON** |

---

## OUTPUT

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/984005b8-c085-45ad-98bb-010eaeb40107" />

---

## Result

The **TSMaster C Mini Program** was successfully developed and executed. The interior light was activated whenever **any vehicle door was open** and switched **OFF when all doors were closed**, confirming the correct implementation of the door-based interior-light control logic.
