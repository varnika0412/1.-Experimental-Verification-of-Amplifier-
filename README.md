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
<img width="985" height="796" alt="{4CB69F31-B8C5-42B9-A2DD-0F8B36D4E24B}" src="https://github.com/user-attachments/assets/2798042b-23f6-494b-b0dd-6f6988352924" />

### CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="1061" height="771" alt="{0AF910F5-D37B-465A-B486-64F2791C4C1C}" src="https://github.com/user-attachments/assets/29613e92-6254-4418-a204-a10d7e5250bc" />

### MODEL GRAPH 

<img width="992" height="767" alt="{F97667F8-C844-4060-BEA3-63FEDA49ECB3}" src="https://github.com/user-attachments/assets/5d6ca71b-9653-42b6-9aa5-53158e6d7e8b" />



### DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =100 R1
Choose R1 = 1kΩ, Rf=100kΩ
<img width="1176" height="760" alt="{A2FBA4B4-8944-446D-AF33-11C9C3FCD840}" src="https://github.com/user-attachments/assets/96ccd7e9-f1c2-4ffa-a8de-f472e3f43fd0" />


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

<img width="1396" height="783" alt="{43B886C3-4583-4EBB-B3C6-4A4AB922694D}" src="https://github.com/user-attachments/assets/898bd429-75cd-44c7-9644-9cefe81b033d" />

---
## CALCULATION

<img width="1826" height="697" alt="{A905D02C-2FBA-44CE-9C11-E53C520ABFD8}" src="https://github.com/user-attachments/assets/d626120a-21dc-4565-82eb-5ab2a0b23633" />

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="571" height="771" alt="{B2E35B35-0BB0-4A2E-9185-58291EC0C92F}" src="https://github.com/user-attachments/assets/f4e21d0e-bbea-4f1e-8a8a-0a260834c247" />

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

<img width="1019" height="738" alt="{3DE74AB8-782D-4B70-B43F-D6E1793B71AF}" src="https://github.com/user-attachments/assets/4b98db42-c8ee-4126-bcb9-c424b1aa0a2f" />

---

## MODEL GRAPH

<img width="901" height="779" alt="{D123773B-CDC8-4E17-850A-78DC9FDB5129}" src="https://github.com/user-attachments/assets/c63d5227-195d-49ff-8beb-72b5deb87ac6" />

---
## DESIGN 
<img width="471" height="788" alt="{4F8A0DA8-39A3-45E6-9B53-D0720E05CD44}" src="https://github.com/user-attachments/assets/d7da9f4c-1a90-4905-9da3-16dc401a0f27" />

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

<img width="1714" height="809" alt="{0D75F3C4-D6EE-47F7-88BD-5E5D0EC93092}" src="https://github.com/user-attachments/assets/63771ee7-4430-4a4d-894e-89c88204211b" />
<img width="1296" height="750" alt="{C958A9DB-73C0-4A08-9375-6C1722715876}" src="https://github.com/user-attachments/assets/a39e3a98-d16b-4deb-97b2-1cfc9fd26284" />

---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="552" height="773" alt="{4E2AD5D3-C3BC-464C-89C0-DD9AD40246FB}" src="https://github.com/user-attachments/assets/896b5053-63e8-4f67-9304-7019b2690fce" />

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
<img width="1010" height="721" alt="{FD788E10-55E3-433E-9E5C-16CE19F17F04}" src="https://github.com/user-attachments/assets/30b25a93-5aca-4073-8cc1-fa792500b32c" />

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
<img width="1903" height="777" alt="{29214920-C65D-4717-8526-F665A9288DA3}" src="https://github.com/user-attachments/assets/097a0328-f6f3-4ef8-ae8b-4b1b0e36c2bc" />

---
## CALCULATION 

<img width="1391" height="730" alt="{1C17BA94-24CA-411C-928F-8A5FA61CC966}" src="https://github.com/user-attachments/assets/d49ce4c6-779e-41d4-82aa-d174b62dc782" />

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="578" height="760" alt="{2C34C445-5155-48DC-BB44-E54C39242608}" src="https://github.com/user-attachments/assets/f84abf5c-62c9-426d-8169-cb90352aadc9" />

---
## INSTRUMENTATION AMPLIFIER

## THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="787" height="779" alt="{BBD9418F-6B66-4276-8AFC-DD878E9D7019}" src="https://github.com/user-attachments/assets/a4218bb6-8b54-4f1a-a808-a038f92065c5" />

## MODEL GRAPH

<img width="847" height="765" alt="{500E398C-1AA1-465A-870C-655BB95073A7}" src="https://github.com/user-attachments/assets/c46c459c-693a-49b8-9273-96a600261e32" />

## DESIGN

<img width="1148" height="768" alt="{87F33F89-605B-4E97-8BE2-A41023381B57}" src="https://github.com/user-attachments/assets/bccf9877-8edf-4106-bfc1-6aef53872d53" />

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
<img width="394" height="203" alt="{A3AAEE7C-F170-4C6B-B421-C08569A874BF}" src="https://github.com/user-attachments/assets/41902dcc-07c0-4116-b917-afc33e076594" />

## CALCULATION
<img width="433" height="235" alt="{DA27501E-133D-48D2-919D-72AC1D33B7E3}" src="https://github.com/user-attachments/assets/5abf46f5-ca1f-46e2-8844-1633ed981407" />

---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="403" height="519" alt="{1696BE49-61AB-4A01-AA26-E3D2A5F4F17C}" src="https://github.com/user-attachments/assets/35466fd7-bb8b-4e1c-8bcd-b33bb98ef6a5" />


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
