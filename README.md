## 👋 Hi, I'm Stefan Schlee

**Mechatronics Engineer** | **Embedded Software 💻** | **Robotics and Control 🤖**

I'm passionate about building robust embedded systems and intelligent control architectures. My work bridges low-level firmware and high-level algorithm development — from real-time embedded C/C++ systems to model-based design with Simulink.

### 💼 What I Do

**🔧 Embedded Software Development**
- Design and implementation of efficient, modular embedded software architectures (C/C++)
- CI/CD setup using Python, CMake, and Jenkins
- Automated testing infrastructure for continuous software quality assurance

**📐 Model-Based Design**
- Rapid control prototyping and algorithm development for robotic systems using Matlab/Simulink
- Development of automation frameworks for large-scale modular Simulink projects

---

You can also find me on [LinkedIn](https://www.linkedin.com/in/stefan-schlee-9b67aa227/)  
Feel free to explore my projects below — many of them are inspired by my academic and professional journey!

## 🗂️ Projects Overview

### 📂 Quadcopter Flight Controller (ESP32-Based)

During my bachelor’s studies, I built a custom quadcopter from scratch and developed a flight controller firmware running on an ESP32. The controller received inputs from an RC receiver, fused IMU sensor data using a Kalman filter to estimate the current flight attitude, and applied a cascaded PID controller to compute motor setpoints. These were output as PWM signals to control four brushless motors. Additional sensors included a GPS receiver and barometer for extended navigation data. The system also streamed real-time telemetry via Bluetooth to a PC for monitoring and analysis.

> ⚠️ **Note:** This project was developed early in my academic journey. From today's perspective, the code quality and software architecture are no longer up to my current standards.

<p align="left">
  <img src="images/quadcopter.jpg" alt="quadcopter_photo" width="200"/>
</p>

#### 🔗 Related Repositories

| Repository | Description |
|------------|--------------|
| [Quadcopter Firmware](https://github.com/StefanSchlee/Quadrokopter_V2) | This is the main repository for the firmware |
| [MPU9250_SPI](https://github.com/StefanSchlee/MPU9250_SPI) | Driver for the MPU9250 inertial measurement unit (IMU) |
| [IMU Kalman Filter](https://github.com/StefanSchlee/IMU_KalmanFilter/tree/master) | Kalman filter for state estimation |
| [Digital Filter Lib](https://github.com/StefanSchlee/DigitalFilter/tree/master) | Library with digital filters |

---
### 📁 Python Package Demo

This repository is a minimal example of how to structure and test a Python package that is installable via `pip` (locally, not yet published to PyPI). It demonstrates best practices for packaging, unit testing, and continuous integration — ideal for learning or teaching the Python packaging workflow.

The demo package includes a single module with a simple `square(x)` function as its core logic.

**Key Features:**
- 📁 Structured as an installable Python package (`pip install .`)
- ✅ Unit tests written using `pytest`, run in isolated environments using `tox`
- 🔄 Automated test execution via **GitHub Actions** CI

#### 🔗 Repository
[Python_Testing_Demo](https://github.com/StefanSchlee/Python_Testing_CI_Demo/blob/master/src/MyPackage/MyModule.py)


<!--
**StefanSchlee/StefanSchlee** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
