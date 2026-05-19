# Hi! Welcome inside Sydney’s mind

Computer Science student @ Université Côte d'Azur & École 42 Nice
Software Developer, Systems & Networks — C | C++ | FreeRTOS | ESP32
Actually looking for a 2-year apprenticeship 
Nice, France

---

## About

Software and system enthusiast focused on low-level development.
I implement drivers and applications from scratch while eating chips, design
custom communication protocols in music, and build real-time architectures
on bare-metal microcontrollers trying to not explose.

Currently deepening my knowledge of FreeRTOS, moving toward
STM32 and automotive/spatial embedded systems.

---

## Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**RTOS & Frameworks**

![FreeRTOS](https://img.shields.io/badge/FreeRTOS-8CC84B?style=flat&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Protocols**

![TCP/IP](https://img.shields.io/badge/TCP%2FIP-555555?style=flat)
![HTTP](https://img.shields.io/badge/HTTP-555555?style=flat)
![UDP](https://img.shields.io/badge/UDP-555555?style=flat)
![SSH](https://img.shields.io/badge/SSH-555555?style=flat)
![I2C](https://img.shields.io/badge/I²C-555555?style=flat)
![SPI](https://img.shields.io/badge/SPI-555555?style=flat)
![UART](https://img.shields.io/badge/UART-555555?style=flat)
![PWM](https://img.shields.io/badge/PWM-555555?style=flat)
![LoRaWAN](https://img.shields.io/badge/LoRaWAN-0085CA?style=flat)
![CAN](https://img.shields.io/badge/CAN%20-555555?style=flat)

**Microcontrollers**

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32%20-03234B?style=flat&logo=stmicroelectronics&logoColor=white)

---

## Featured Projects

### Embedded Systems

**Embedded Drivers from Scratch — ESP32, C**
Low-level drivers implemented without libraries, reading datasheets directly.
- **I²C** — SSD1306 OLED display, MPU-6500 IMU (accelerometer/gyroscope)
- **SPI** — RC522 RFID reader (Mifare Classic UID)
- **UART** — Custom serial protocol `[START][CMD][LEN][DATA][CRC][END]`
  with state-machine parser and unit tests (timeout, overflow, checksum)

**LoRaWAN Connected Anti-theft System**
Connected anti-theft device using LoRaWAN protocol, built at the
University FabLab in the context of the
*Wireless Communication from Ground to Space* course.

**Real-time Embedded System — Motor Control & Obstacle Detection**
Dual state machine (movement + distance measurement), HC-SR04 driver
implemented from scratch (non-blocking), 4 DC motors controlled via L293D,
real-time OLED display. Fully non-blocking architecture.

---

### Systems Programming

**IRC** — Internet Relay Chat server in C++  
Custom IRC server implementing the RFC protocol, multi-client management.

**minishell** — Unix shell implementation in C  
Custom Bash-like shell: command parsing, pipes, redirections,  
environment variables, signal handling.

---

### Algorithms

**push_swap** — Sorting algorithm in C using two stacks  
Optimized instruction sequence to sort a stack with minimal moves.

---

### Concurrency

**philosophers** — Dining philosophers problem  
Concurrency, mutex, threads — race condition management in C.

---

### Computer Graphics

**miniRT** — Ray tracer in C  
3D rendering engine from scratch: rays, lighting, shadows, reflections.

**FdF** — Wireframe 3D map renderer  
Isometric projection of height maps using MiniLibX.

---

## Currently Learning

- FreeRTOS — tasks, queues, mutex, semaphores
- STM32 — STM32CubeIDE, HAL drivers

---
