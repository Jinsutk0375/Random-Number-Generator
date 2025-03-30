# Random-Number-Generator  
**Random Number Generator Using 555 Timer & 4026 IC**  
<p align="center">
  <img src="https://github.com/user-attachments/assets/e1d46a4d-884d-46a0-babd-8d79568bd0b3" width="45%" />
  <img src="https://github.com/user-attachments/assets/4fe1a897-3926-4488-b9ce-0c1770277612" width="45%" />
</p>

## 📌 Project Overview  
This project is a simple **random number generator** using a **555 timer IC** in astable mode, a **4026 decade counter IC**, and a **7-segment display**. The 555 timer generates clock pulses that drive the 4026 counter, which cycles through numbers **0 to 9** rapidly. When a push button is pressed, the counting stops, displaying a "random" number on the 7-segment display.  

## 📹 Project Video  
[![Watch Video](https://github.com/user-attachments/assets/938a7a37-ec61-4d7e-9ad2-bc1f2bd4c9a2)](https://github.com/user-attachments/assets/938a7a37-ec61-4d7e-9ad2-bc1f2bd4c9a2)  

## ⚙️ Components Required  
- **555 Timer IC** (for clock pulse generation)  
- **4026 Decade Counter IC** (counts and drives the 7-segment display)  
- **Common Cathode 7-Segment Display** (to display numbers)  
- **Resistors & Capacitors** (for timing adjustments)  
- **Push Button** (to pause counting)  
- **Power Supply (5V-9V)**  
- **Breadboard & Connecting Wires**  

## 🔧 Working Principle  
1. **Clock Generation**:  
   - The **555 timer** operates in astable mode, continuously generating clock pulses.  
   - The pulse frequency is determined by resistor and capacitor values.  

2. **Counting and Displaying Numbers**:  
   - The **4026 IC** receives these pulses and increments its count from 0 to 9.  
   - It also directly drives a **common cathode 7-segment display**, showing the current count.  

3. **Stopping the Count for a Random Number**:  
   - A **push button** is used to **pause the clock** by controlling the clock inhibit or reset pin.  
   - Since the numbers change rapidly, releasing the button **"freezes"** a number on the display, creating the effect of a random selection.  

## 🔌 Circuit Diagram  
![Circuit Diagram](https://github.com/user-attachments/assets/e7e7bcc9-913a-42cb-8c73-0ef77c356c0e)  

## 🎯 Applications  
- **Lucky Draw Systems**  
- **Basic Digital Circuit Learning**  
- **Embedded System Fundamentals**  

## 🛠️ Setup Instructions  
1. Connect the **555 Timer IC** in astable mode to generate pulses.  
2. Wire the **4026 IC** to receive clock pulses from the 555 Timer.  
3. Connect the **4026 outputs** to the **common cathode 7-segment display**.  
4. Add a **push button** to control the clock (pause function).  
5. Power the circuit with **5V-9V** and observe the display.  

