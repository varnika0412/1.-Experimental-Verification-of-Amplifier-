## **EX.NO:** 1  EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
## **DATE:24.1.2026**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

### PIN DIAGRAM
![WhatsApp Image 2026-03-27 at 7 12 40 PM](https://github.com/user-attachments/assets/2eaa8aa6-b4e4-465b-a983-0ff6c6bfc9a8)

### CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2026-03-27 at 7 13 29 PM](https://github.com/user-attachments/assets/ae4837b8-fb87-44a1-a846-46b67f20347a)

### MODEL GRAPH 

![WhatsApp Image 2026-03-27 at 7 14 59 PM](https://github.com/user-attachments/assets/e31ee1c1-ca53-41c0-b32b-1e80e6de9547)



### DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =100 R1
Choose R1 = 1kΩ, Rf=100kΩ
![WhatsApp Image 2026-03-27 at 9 47 26 PM](https://github.com/user-attachments/assets/ed886fd9-70c0-44e1-b243-89ccaa1a4b29)


### PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![WhatsApp Image 2026-03-27 at 7 23 50 PM](https://github.com/user-attachments/assets/5903015e-7fe0-4302-860a-3ca5a1b95f3f)

---
## CALCULATION

![WhatsApp Image 2026-03-27 at 7 23 07 PM](https://github.com/user-attachments/assets/e0032c4d-13ab-4b78-aaec-db0231888e7d)

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2026-03-27 at 7 25 34 PM](https://github.com/user-attachments/assets/f6a6dd1e-2dcb-4318-8420-feeecc1cfd24)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![WhatsApp Image 2026-03-27 at 7 27 27 PM](https://github.com/user-attachments/assets/82340f38-77f1-4fc6-94e7-e736af7d9423)

---

## MODEL GRAPH

 ![WhatsApp Image 2026-03-27 at 7 28 34 PM](https://github.com/user-attachments/assets/c2bd3bcd-5766-47bf-976f-b5f5e2e874b2)

---
## DESIGN 
![WhatsApp Image 2026-03-27 at 9 49 03 PM](https://github.com/user-attachments/assets/66e04527-8eba-4d2e-9225-d401ce182811)
![WhatsApp Image 2026-03-27 at 9 50 06 PM](https://github.com/user-attachments/assets/91189f00-29dc-4b0d-a319-c47a21047d89)

## PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

 ![WhatsApp Image 2026-03-27 at 7 34 13 PM](https://github.com/user-attachments/assets/e002aaf3-1caa-405d-8b99-bc41569692b3)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2026-03-27 at 7 35 50 PM](https://github.com/user-attachments/assets/49ae0916-a6aa-460c-8113-7de2c7645c22)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
 ![WhatsApp Image 2026-03-27 at 7 36 59 PM](https://github.com/user-attachments/assets/a87800fc-c329-4bb5-8ffb-e99b8c4e134a)

## MODEL GRAPH
 ![WhatsApp Image 2026-03-27 at 7 37 32 PM](https://github.com/user-attachments/assets/789020cb-5241-4603-860e-b5aa18d557d7)

---

## DESIGN

### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 100R1   
Choose  R1 = 1kOhm, Rf = 100kOhm
![WhatsApp Image 2026-03-27 at 9 51 36 PM](https://github.com/user-attachments/assets/c2477384-57ae-408f-b435-943684d7aa2b)

---

## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2026-03-27 at 7 39 25 PM](https://github.com/user-attachments/assets/ae6fd557-a61c-44c0-8391-9bcdfd6ef141)


---
## CALCULATION 

![WhatsApp Image 2026-03-27 at 7 38 10 PM](https://github.com/user-attachments/assets/fa0105fc-6437-4b94-ac3b-5736c6b5dcdb)

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2026-03-27 at 7 40 02 PM](https://github.com/user-attachments/assets/afdfa8c4-e6d6-404b-964d-d6180cef38a3)

---
## INSTRUMENTATION AMPLIFIER

## THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2026-03-27 at 7 41 30 PM](https://github.com/user-attachments/assets/fca5382b-7288-4d52-bd43-70ca703fc492)

## MODEL GRAPH

![WhatsApp Image 2026-03-27 at 7 43 20 PM](https://github.com/user-attachments/assets/fe7fb554-56ad-4eb1-97e0-9a5fefeb1d00)

## DESIGN

![WhatsApp Image 2026-03-27 at 9 53 26 PM](https://github.com/user-attachments/assets/dd02524f-71c2-4c29-8fbf-83de5ee46a6e)

## PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2026-03-27 at 7 45 19 PM](https://github.com/user-attachments/assets/df69f64d-f6e5-40fb-ba49-62c4d34f2a5f)

## CALCULATION
![WhatsApp Image 2026-03-27 at 7 44 36 PM](https://github.com/user-attachments/assets/f041d0fe-6914-42f1-b4e0-85c1e37ef14a)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2026-03-27 at 8 02 54 PM](https://github.com/user-attachments/assets/6d20f5a1-abbf-41d3-bb18-c4bd5aadb746)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
