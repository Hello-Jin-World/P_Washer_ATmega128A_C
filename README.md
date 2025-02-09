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
_(Insert design images here)_

## 🔄 FSM (Finite State Machine) Diagram
_(Insert FSM diagram here)_

## 🛠️ Hardware Implementation
_(Insert final hardware images here)_

## 📜 Source Code
- Available on GitHub: [GitHub Repository](https://github.com/Hello-Jin-World/harman_atmega128a/tree/main/09_WASHING_MACHINE)

## 📊 Motor Control PWM Waveform Analysis
_(Insert waveform images here)_

## 🎥 Demo Video
- Watch the working prototype: [YouTube Video](https://youtu.be/nHj1sp85_1E?si=EzmtrwecQJhctsFp)

## 🔧 Areas for Improvement
- **Reduce hard coding** for better maintainability.
- **Fix FND refresh rate issue** (possible interference with PWM and Timer).
- **Enhance hardware design** to closely resemble a real washing machine.

---

### 🔹 Note
- **No generative AI** was used in this project.

