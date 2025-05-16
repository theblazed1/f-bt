# 💥 FUCK BT - Bluetooth Jammer for Flipper Zero

**FUCK BT** is a Bluetooth jamming tool designed for the Flipper Zero, leveraging the nRF24 module to disrupt Bluetooth communications. Configure packet size, prioritize data or packet density, and choose from three jamming methods to suit your needs.

---

## 🛠️ Features
- **Adjustable Packet Size**: Tune payloads from **1 to 32 bytes**.
- **Prioritization Modes**:
  - **Packet Density**: Flood the spectrum with more packets (faster).
  - **Data Throughput**: Maximize data per packets (more data by repeating).
- **Jamming Methods**:
  - **Narrow**: Focused interference on 1-2 channels at once.
  - **Mid**: Focused interference on 3-4 channels at once.
  - **Wide**: Focused interference on 6+ channels at once (Best).

---

## 🕹️ How to
- **How to install**:  
  Copy the .fap file to your apps folder
- **Switch Prioritization**:  
  Navigate to **Apps → FUCK BT → Settings**
- **Adjust Jamming Method**:  
  Navigate to **Apps → FUCK BT → Settings**
- **Start jamming**
  **Apps → FUCK BT → Start**

---

## ⚙️ Configuration Details
### Packet Size (`1–32`)
- Smaller sizes (e.g., `1-8`) prioritize speed and packet count.
- Larger sizes (e.g., `24-32`) maximize data per transmission.

### Prioritization Mode
- **Packets**: Ideal for overwhelming target devices with high-frequency noise.
- **Data**: Better for sustained interference with larger payloads.

### Jamming Methods
| Method  | Channels per packet | Effect                     |
|---------|-------------------|------------------------------|
| Narrow  | 1-2               | Low          |
| Mid     | 3-4               | Mid            |
| Wide    | 6+                | High (makes bluetooth audio stop)    |

---

## ⚠️ Disclaimer
**This project is for educational and research purposes only.**  
⚠️ Bluetooth jamming is **illegal** in most jurisdictions.  
⚠️ Use responsibly and comply with local laws.  
⚠️ The developers assume **no liability** for misuse.

---
readme template made using by deepseek
