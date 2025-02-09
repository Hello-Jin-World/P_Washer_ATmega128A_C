### Blog Link : https://blog.naver.com/daniel8608/223576122117

# 🚀 Washing Machine Implementation

## 📌 Project Overview

### Objective
- Develop a fully functional washing machine using **ATmega128a** microcontroller.
- Implement all features similar to a real washing machine.

### Technologies & Equipment Used
- **Language**: C
- **Microprocessor**: ATmega128a
- **Software**: Microchip Studio

### Achievements
- Independently developed all features.
- Ranked **1st place** in class project competition.

## 📂 Features Implemented

- **Mode Selection**: Choose from **Automatic Mode, Manual Mode, Quick Mode, Spin Mode**.
- **Automatic Mode**: Controls water temperature, rinse cycles, and spin strength automatically.
- **Manual Mode**: Users manually select water temperature, rinse cycles, and spin strength.
- **Quick Mode**: A faster version of Automatic Mode.
- **Spin Mode**: Only spin cycle with adjustable intensity.
- **User Interface**:
  - **LEDs and FNDs** display mode selection, progress, and spin direction.
  - **Four-button interface** optimized for intuitive use.
- **Motor Control**:
  - Alternates spin direction, mimicking a real washing machine.
  - Utilizes **PWM waveforms** for motor control.
- **Safety Features**:
  - The washing process only proceeds when the **door is closed**.
  - If the door is opened mid-cycle, the process **pauses** and resumes when closed and confirmed via button press.

## 🏗️ Initial Design
_![IMG_0796](https://github.com/user-attachments/assets/d7c51cce-04f5-4b44-8c44-72eaed7d8ea0)


## 🔄 FSM (Finite State Machine) Diagram
_![IMG_0799](https://github.com/user-attachments/assets/8dddaff0-743e-478c-8138-d689c81e2635)


## 🛠️ Hardware Implementation
_![IMG_0795](https://github.com/user-attachments/assets/5fe4a8e7-d926-475e-bc66-999eca368f6e)

## 📊 Motor Control PWM Waveform Analysis
_![IMG_0801](https://github.com/user-attachments/assets/488a3e8a-7559-4a86-99d9-5e74bfcc19f5)


## 🎥 Demo Video
- Watch the working prototype: [YouTube Video](https://youtu.be/nHj1sp85_1E?si=EzmtrwecQJhctsFp)

## 🔧 Areas for Improvement
- **Reduce hard coding** for better maintainability.
- **Fix FND refresh rate issue** (possible interference with PWM and Timer).
- **Enhance hardware design** to closely resemble a real washing machine.

---

### 🔹 Note
- **No generative AI** was used in this project.

