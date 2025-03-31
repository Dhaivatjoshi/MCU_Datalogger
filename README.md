---

## **MCU Data Logger – PCB Design with KiCad**  

### **Project Overview**  
This project is an **MCU-based Data Logger** designed to improve my skills in PCB design and embedded systems. The PCB was developed using **KiCad**, incorporating key components for reliable data logging and real-time tracking. This project helped me refine my understanding of component placement, routing, and communication protocols.  

### **Key Features**  
✅ **2-Layer PCB Design** – Created and optimized using KiCad.  
✅ **Microcontroller** – ATmega328P-AU for processing and control.  
✅ **Non-Volatile Storage** – 24LC1025 EEPROM for data logging.  
✅ **Real-Time Clock** – DS1337 RTC for accurate timekeeping.  
✅ **Communication Interfaces** – Supports UART, SPI, and I2C for flexibility.  
✅ **GPIOs for Expansion** – Designed with future scalability in mind.  
✅ **3D PCB Visualization** – Front, back, and combined views for better insights.  

---

## **Project Flow**  

1️⃣ **Microcontroller (ATmega328P-AU)**  
   - Handles all system operations and manages communication.  
   - Reads and writes data to EEPROM for storage.  
   
2️⃣ **RTC Module (DS1337)**  
   - Provides accurate timestamps for logged data.  
   - Communicates via I2C with the MCU.  
   
3️⃣ **EEPROM Storage (24LC1025)**  
   - Stores logged data persistently.  
   - Connected over I2C for data transfer.  

4️⃣ **Communication Interfaces**  
   - **UART**: Serial communication for debugging/logging.  
   - **SPI & I2C**: Expandability for additional peripherals.  

5️⃣ **Power Management & PCB Layout**  
   - Designed for stable operation with proper power routing.  
   - Optimized signal paths to reduce interference and improve reliability.  

---

## **PCB Design & Visualizations**  

### **1️⃣ Front Copper Layer**  
![Front Copper Layer](https://github.com/Dhaivatjoshi/MCU_Datalogger/blob/master/image/Front_layer.PNG)


### **2️⃣ Back Copper Layer**  
![Back Copper Layer](https://github.com/Dhaivatjoshi/MCU_Datalogger/blob/master/image/Bottom_Layer.PNG)  

### **3️⃣ Combined (Both Layers)**  
![Combined Layers](https://github.com/Dhaivatjoshi/MCU_Datalogger/blob/master/image/Both_Layer.PNG)  

### **4️⃣ 3D Model (Front & Back)**  
![3D Model - Front](https://github.com/Dhaivatjoshi/MCU_Datalogger/blob/master/image/F_3d_MCU_Datalogger.png)
![3D Model - Back](https://github.com/Dhaivatjoshi/MCU_Datalogger/blob/master/image/B_3d_MCU_Datalogger.png)

---

## **Download & Build**  
📥 You can download the complete project files, including KiCad PCB designs, and schematics from my **GitHub repository**  

---

## **Feedback & Suggestions**  
I'm constantly learning and improving my PCB design skills. If you're experienced with KiCad or embedded systems, I'd love to hear your thoughts! Feel free to open an **issue** or drop a **comment**. 🚀  

---
