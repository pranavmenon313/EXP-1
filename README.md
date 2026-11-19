## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |Pranav Menon G.k | **Reg. No.:** |26018309 |
|---|---|---|---|
| **Date:** | 5/11/2026| **Batch / Section:** | cse|

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

*[ Insert the KVL circuit diagram here ]*

**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

*[ Insert the KCL circuit diagram here ]*

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation
<img width="1177" height="628" alt="BEE(kvl before)" src="https://github.com/user-attachments/assets/bdd806db-30a1-428d-b8e3-0fb8e58b7478" />

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1123" height="595" alt="BEE(KCLbefore)" src="https://github.com/user-attachments/assets/2b8a46ab-4654-40a6-9355-cb9fbb49a474" />

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 |5 |1.16 |1.66 |1.67 |5.00 |
| 2 | 10|3.33 |3.34 |3.33 |10.00 |
| 3 | 15|5.00 |5.00 |5.00 |15.00 |
| 4 | 20|6.67 |6.66 |6.67 |20.00 |
| 5 | 25|8.33 |8.34 |8.33 |25.00 |

### B. KCL – Current measurements

| S. No. | Supply voltage Vs (V) | Total current It (A) | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | I1 + I2 + I3 (A) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 |5 |5 |1.16 |1.66 |1.67 | 5.00|
| 2 |10 | 10|3.33 | 3.33| |10.00 |
| 3 |15 |15 | 5.00| |5.00 |15.00 | 
| 4 | 20|20| 6.67| 6.66| 6.67|20.00 | 
| 5 |25 |25 |8.33 |8.34 |8.33 |25.00 | 

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1915" height="1075" alt="BEEE(kvl)" src="https://github.com/user-attachments/assets/1b7163d5-1943-4fb3-805b-d928135f5c82" />

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1915" height="1074" alt="BEEE(kcl)" src="https://github.com/user-attachments/assets/531fe9a9-b438-44d6-ab25-cb9a74f09f43" />

**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
