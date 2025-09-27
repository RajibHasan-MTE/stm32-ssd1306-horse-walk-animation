# 🐎 Horse Walking on Display with STM32 + SSD1306

Ever wondered if you could display a **walking horse animation** on an embedded device?  
Yes, you can! 🎉  

This project uses an **STM32 Blackpill** microcontroller with an **SSD1306 OLED** to display a simple frame-by-frame horse walking animation. It’s a fun introduction to embedded graphics, animation timing, and display interfacing.

---

## ⚡ Project Overview
- **MCU:** STM32 Blackpill  
- **Display:** SSD1306 OLED (128x64)  
- **IDE & Toolchain:** Keil µVision  
- **Project Type:** Basics / Graphics Demo  

💡 The project cycles through bitmap frames of a horse, creating the illusion of walking.  

---

## 🛠️ Hardware Requirements
- STM32 Blackpill board  
- SSD1306 OLED display (I2C/SPI supported)  
- Jumper wires  
- USB to ST-LINK programmer/debugger  

---

## 📂 Repository Structure
stm32-ssd1306-horse-walk-animation/
│── Core/ # STM32 source files
│── Drivers/ # SSD1306 driver + HAL
│── Inc/ # Header files
│── Src/ # Main source and animation code
│── horse_frames/ # Bitmap frames for the horse animation
│── README.md # Project documentation


---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stm32-ssd1306-horse-walk-animation.git

2. Open the project in Keil µVision IDE.

3. Connect the STM32 Blackpill to your SSD1306 (I2C/SPI).

4. Build and flash the firmware using ST-LINK.

5. Watch the horse walk… frame by frame! 🐎🎥

🎥 video link: https://www.facebook.com/share/v/17DPMQyqkW/

📚 Learn More

This project is a great way to explore:

- STM32 basics

- SSD1306 display interfacing

- Bitmap animations

- Frame rendering on embedded devices

🤝 Contributing

Feel free to open issues or suggest improvements. Want to add more animations? PRs are welcome!
