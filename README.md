## ECPC Competition Problem Solutions - NRW 2024

![image](https://github.com/bnina-ayoub/ECPC-Problems/assets/94785911/ffeba1d6-0c65-4ff1-a245-4929d44f3326)


This repository contains solutions to problems tackled during the NRW (National Robotics Weekend) competition, the opening event of the Eastern Collegiate Programming Championship (ECPC). The ECPC is a prestigious programming competition for university students in Eastern Europe.

### **Focus:**

These solutions are specifically designed for use with STM32CubeIDE, a popular development environment for embedded systems utilizing STM32F407VG microcontrollers.

### **Problem Folders:**

Each problem addressed in the NRW competition has its own dedicated folder within this repository. Folder names directly correspond to the problem number.

### **Problem Structure:**

Within each problem folder, you'll find:

* Code Files (Core/These files contain the source code for the implemented solution, specifically designed for use with STM32CubeIDE.

## **Problem 4 : Ping Pong Challenge :**

This challenge introduces basic communication between two microcontrollers (MCUs) using UART (Universal Asynchronous Receiver Transmitter). 

**Goal:** Develop a program for the MCUs that enables them to exchange "PING PONG" messages via UART.

### **Requirements:**

* **Two-way communication:**
    * Upon receiving "PING," an MCU responds with "PONG."
* **Initiation:**
    * One MCU randomly sends "PING" on startup to initiate the exchange.
* **Program Identicality:**
    * Both MCUs run the same program, acting as transmitter or receiver dynamically.
* **Non-blocking communication:**
    * The program shouldn't halt while waiting for messages.
* **Communication indication:**
    * Implement logging (debugger monitor/UART/Logic Analyzer) or an LED blink to confirm communication and program functionality.

**Hint:** Introduce a random delay at startup to ensure one MCU sends "PING" before the other.

This challenge lays the foundation for building more complex communication protocols between MCUs.


**Getting Started:**

1. **Clone the Repository:**

   Use the following command to clone this repository to your local machine:

   ```bash
   git clone https://github.com/bnina-ayoub/ECPC-Solutions.git
   ```

2. **Open in STM32CubeIDE:**

   - Launch STM32CubeIDE.
   - Navigate to **File > Open Projects from File Systems**.
   - In the import dialog, select the root folder of your cloned repository.
   - Click **Finish**.

   STM32CubeIDE will import the project structure, allowing you to explore and work with the provided solutions.
