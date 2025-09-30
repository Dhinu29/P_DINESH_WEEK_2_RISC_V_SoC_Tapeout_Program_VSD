# 🚀 P_DINESH_WEEK_2_RISC_V_SoC_Tapeout_Program_VSD

 # Overview:
BabySoC is a simplified, open-source SoC built around the RVMYTH processor core, a RISC-V-based CPU. It integrates a Phase-Locked Loop (PLL) for precise clock generation and a 10-bit Digital-to-Analog Converter (DAC) for interfacing with external analog systems. While the DAC allows BabySoC to interact with devices such as televisions or mobile phones by converting digital signals to analog, this task emphasizes understanding the internal digital behavior through simulation.

# **Focus on:**
 - What is a System-on-Chip (SoC)?
 - Components of a typical SoC (CPU, memory, peripherals, interconnect).
 - Why BabySoC is a simplified model for learning SoC concepts.
 - The role of functional modelling before RTL and physical design stages. 

# **Tools Used for BabySoC Design**

1️⃣ **Icarus Verilog (iverilog):**

  - Used for compiling and simulating the BabySoC RTL modules.
  - Allows verification of functional behavior of the SoC components like CPU, PLL, and DAC.

2️⃣ **GTKWave:**
 - Used for visualizing simulation waveforms.
 - Helps analyze signal interactions, timing, and system behavior in a graphical form.


# What is a System on a Chip (SoC)?
A System on a Chip (SoC) is a highly integrated circuit that functions like a mini-computer built onto a single chip. Instead of requiring separate physical parts for each function, an SoC combines all the necessary components into one small package.

This design is essential for devices where 

**space, power, and efficiency** are critical, such as smartphones, smartwatches, and tablets.


# 1️⃣ Introduction to VSDBabySoC
**The VSDBabySoC (or BabySoC)** is a small yet highly capable SoC with a primary objective of being an educational platform. It was designed to facilitate the simultaneous testing of three specific open-source intellectual property (IP) cores for the first time while also allowing for the calibration of its analog components.

# 2️⃣ BabySoC Key Components
The BabySoC integrates both digital and analog parts, including:

- **RVMYTH Microprocessor (RISC-V CPU):** This is the brain of the BabySoC, an open-source, customizable CPU that handles all the processing tasks and communicates with the other parts of the system.

- **8x Phase-Locked Loop (PLL):** The PLL generates a stable and synchronized clock signal to ensure all components—the RVMYTH processor and the DAC—operate in harmony and avoid timing mismatches.

- **10-bit Digital-to-Analog Converter (DAC):** The DAC's function is to receive digital signals from the RVMYTH processor and convert them into an analog output signal.

# 3️⃣ BabySoC Uses and Functionality
The main use of the BabySoC is tied to its capability for digital-analog interfacing and its educational purpose:

- **Digital-Analog Interfacing:** The 10-bit DAC allows the BabySoC to communicate with external analog devices.

- **Multimedia Output:** By converting the processed digital values into an analog signal, the DAC enables the SoC to provide output in the form of audio or video.

- **External Device Connectivity:** This analog output can be fed to external devices that interpret analog signals, such as televisions and mobile phones.

- **Educational Platform:** The Sky130-technology-based SoC is intended to provide a highly documented platform for learning and experimentation in modern embedded systems design and digital-analog interfacing




# ⚡Key Parts of a General System on a Chip (SoC)
 
# BabySoC – System-on-Chip Educational Platform

## What is a System-on-Chip (SoC)?
| Feature | Description |
|---------|-------------|
| Definition | A System-on-Chip (SoC) is a highly integrated circuit that functions like a mini-computer on a single chip. |
| Integration | Combines all necessary components into a single compact package. |
| Importance | Essential for devices where space, power, and efficiency are critical, such as smartphones, smartwatches, and tablets. |

 
# Key Parts of a System-on-Chip (SoC)

| Component | Description |
|-----------|-------------|
| **CPU (Central Processing Unit)** | The brain of the SoC, handling all main instructions and decisions. Manages tasks such as calculations, data processing, and running applications. |
| **Memory** | - **RAM (Random Access Memory):** Temporarily stores data while the device is running.<br>- **ROM/Flash Storage:** Stores information permanently, retaining data even when the device is powered off. |
| **I/O Ports (Input/Output)** | Connects the SoC to external devices like cameras, USB peripherals, sensors, or headphones. Enables the SoC to send and receive data externally. |
| **GPU (Graphics Processing Unit)** | Responsible for rendering visuals on displays. Handles gaming, video playback, animations, and graphical interfaces. |
| **DSP (Digital Signal Processor)** | Specialized processor for handling audio, video, and other signal processing tasks. Improves sound quality, reduces noise, and enhances multimedia performance. |
| **Power Management Unit (PMU)** | Regulates power consumption to ensure efficient operation. Crucial for extending battery life in portable devices and maintaining stable performance. |
| **Special Features / IP Blocks** | Additional modules like Wi-Fi, Bluetooth, security cores, cryptography engines, AI accelerators, or dedicated hardware for machine learning. Varies depending on SoC purpose. |
| **Clock & Timing Units** | Manages system timing, often with integrated **PLL (Phase-Locked Loops)**, ensuring synchronous operation of CPU, memory, and peripherals. |
| **Analog Components / DACs** | Converts digital signals into analog output for audio, video, or interfacing with sensors and external analog devices. Often used in multimedia and embedded applications. |



## Introduction to VSDBabySoC
| Feature | Description |
|---------|-------------|
| Purpose | Small yet highly capable SoC designed as an **educational platform**. |
| Features | - Simultaneous testing of three open-source IP cores<br>- Calibration of analog components |

## BabySoC Key Components
| Component | Description |
|-----------|-------------|
| RVMYTH Microprocessor (RISC-V CPU) | Brain of the SoC; handles all processing tasks and communicates with other components. |
| 8x Phase-Locked Loop (PLL) | Generates stable, synchronized clock signals; ensures CPU and DAC operate in harmony. |
| 10-bit Digital-to-Analog Converter (DAC) | Converts digital signals from RVMYTH processor into analog output. |

## BabySoC Uses and Functionality
| Use | Description |
|-----|-------------|
| Digital-Analog Interfacing | DAC allows communication with external analog devices. |
| Multimedia Output | Converts processed digital values into audio or video signals. |
| External Device Connectivity | Analog output can be fed to TVs, mobile phones, and other devices. |
| Educational Platform | Sky130-based SoC provides a well-documented platform for learning modern embedded systems and digital-analog interfacing. |

