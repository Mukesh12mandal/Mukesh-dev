# Hi, I am Mukesh Kumar Mandal 

Embedded Systems & Robotics Developer focused on low-level firmware architecture, real-time control systems, and hardware-software integration.

I build aerial platforms, robotics manipulators, and physical computing systems from the silicon up-designing custom PCBs, implementing deterministic closed-loops, and writing bare-metal firmware without high-level abstraction crutches.

---

### Technical Focus & Toolkit

- **Core Languages:** Embedded C, C++ (OOP / Systems), Python, MySQL, Javascript, PHP
- **Embedded & Silicon:** STM32 (ARM Cortex-M3),ESP32, Arduino, Bare-Metal Register Control, Hardware Timers, DMA.
- **Communication Buses & Protocols:** SPI (up to 18 MHz), I2C, USART/UART, i-BUS Serial.
- **Robotics & Control Dynamics:** Madgwick AHRS, Closed-Loop PID Control, Sensor Fusion (IMUs), Kinematics, Servo Actuation.
- **Software & Machine Learning:** Multithreaded Python, OpenCV, Scikit-learn, Audio DSP (MFCCs / Librosa), Tkinter GUI.

---

### Flagship Hardware & Robotics Projects

#### [AZRAEL.V1.0 — Embedded STM32 Flight Controller](https://github.com/Mukesh12mandal/AZRAEL)
An embedded flight control system engineered from scratch for the **STM32F103C8T6 (ARM Cortex-M3)** on a custom PCB.
- **Deterministic Scheduling:** Implemented a real-time **400 Hz (2500 µs)** core loop for sensor sampling and motor updates.
- **Attitude Stabilization:** Fused 18 MHz SPI sensor bursts via Madgwick AHRS to drive real-time closed-loop PID attitude stabilization for stable manual flight.
- **Peripheral Isolation:** Dedicated hardware `TIM2` for ESC actuation and isolated high-speed `USART3` for i-BUS serial receiver frames.
- 🔗 **[Read the Documentation & Watch Maiden Flight](https://github.com/Mukesh12mandal/AZRAEL)**.

#### [ORION — 6-DOF Voice-Interactive Robotic Arm](https://github.com/Mukesh12mandal/ORION)
A dual-mode robotic manipulation platform integrating natural language interaction with hardware motion control.
- **Dual-Mode Control:** Supports conversational voice commands and real-time Tkinter GUI manual slider control.
- **Concurrency & State Management:** Engineered a dedicated mutex state synchronization layer to resolve cross-thread text-to-speech race conditions and prevent kinematic discontinuities.
- **Actuation Core:** PCA9685 16-channel PWM driver controlling high-torque metal gear servos with isolated logic and power rails.
- 🔗 **[Explore Architecture & Schematics](https://github.com/Mukesh12mandal/ORION)**.

#### [Multilingual Voice Gender Classification](https://github.com/Mukesh12mandal/voice-gender-detection)
A machine learning classification pipeline designed to categorize acoustic speech profiles.
- Extracted Mel-Frequency Cepstral Coefficients (MFCCs) and spectral features using `librosa`.
- Evaluated and benchmarked Random Forest and Support Vector Machine (SVM) models.
- 🔗 **[View Repository & Datasets](https://github.com/Mukesh12mandal/voice-gender-detection)**

---

### Commercial Engineering & Field Deployment

- **Hardware/Embedded Engineer Intern | D.L Upload Private Limited:** Engineered, tested, and deployed an automated door lock system unit integrated with the **FitHisaab** ecosystem, currently servicing active users in production environments.

---

### Connect With Me

- **Email:** michealmandal85@gmail.com
- **GitHub:** [@Mukesh12mandal](https://github.com/Mukesh12mandal)
