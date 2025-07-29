# 📢 **MOEXHAWK-FC V1.0.1**

The **MOEXHAWK-FC V1.0.1** is a fully custom-designed, compact, and reliable **Flight Controller (FC)** solution tailored for UAV and robotics applications. This version is a standalone autopilot that directly integrates core flight control capabilities, sensor interfaces, and extensive I/O support on a single PCB. The design focuses on robust performance, precise sensing, and broad connectivity, making it suitable for both research and field deployment in autonomous systems. MOEXHAWK-FC has been tested and validated with ArduPilot and Betaflight firmware, confirming its compatibility and reliable operation in various flight scenarios. INAV support is also available, although full testing is pending.

![Top View](https://github.com/MohamadRachidi/Moexhawk-FC-V1.0.1/blob/main/images/izometric%20and%20render.jpg)


# 🔶 **Features**

| **Feature**                | **Description**                                              |
|----------------------------|--------------------------------------------------------------|
| **IMU Sensor**             | Onboard ICM42688-P (High Precision 6-axis IMU)              |
| **Barometer**              | Integrated DPS368XTSA1 (Ultra-Low Pressure Drift)           |
| **PWM Outputs**            | 9x PWM outputs for motors, servos, and actuators            |
| **Telemetry Ports**        | 4x Dedicated Telemetry ports (TELEM1–TELEM4)                |
| **I2C Interface**          | 1x I2C port for peripheral sensors and expansions           |
| **RC Input**               | 1x RC control input (PPM/SBUS supported)                    |
| **MicroSD Logging**        | MicroSD slot for flight data logging                        |
| **Status LEDs**            | Multi-color status indicators for FC operation              |
| **Compact Size**           | 39mm x 41.6mm, 4-layer PCB for EMI reduction & signal integrity |
| **Wide Compatibility**     | Compatible with ArduPilot, Betaflight, iNav, and PX4        |


# 🔶 **Test Status**

##  Supported Firmware

| **Software**           | **Status**       |
|------------------------|------------------|
| **ArduPilot**          | ✅ Tested         |
| **Betaflight**         | ✅ Tested         |
| **iNav**               | ❌ Not Tested Yet |
| **PX4**                | ❌ Not Tested Yet |


🔧 **Custom ArduPilot Firmware**  
The MOEXHAWK-FC requires a tailored ArduPilot firmware (`.apj`) for optimal compatibility.  
📥 Download it from:  
[👉 Custom ArduPilot Firmware (.apj)](https://github.com/MohamadRachidi/Moexhawk-FC-V1.0.1/blob/main/moexhawk%20Ardupilot%20firmware/bin/arducopter.apj)


## Peripheral Testing

| **Peripheral**          | **Status**       |
|--------------------------|------------------|
| **IMU (ICM42688-P)**     | ✅ Tested         |
| **Barometer (DPS368)**   | ✅ Tested         |
| **RC Input**             | ✅ Tested         |
| **PWM Outputs**          | ✅ Tested         |
| **Telemetry Ports**      | ✅ TELEM1-TELEM4  |
| **I2C Bus**              | ✅ Tested         |
| **MicroSD Logging**      | ✅ Tested         |
| **LED Indicators**       | ✅ Tested         |


# 🔶 **Port Layout**

### Telemetry (TELEM1–TELEM4)

| **Pin** | **Signal** | **Description**        |
|--------|------------|------------------------|
| 1      | VCC        | +5V                    |
| 2      | TX         | Transmit (3.3V level)  |
| 3      | RX         | Receive (3.3V level)   |
| 4      | GND        | Ground                 |

### I2C Port

| **Pin** | **Signal** | **Description**        |
|--------|------------|------------------------|
| 1      | VCC        | +5V                    |
| 2      | SCL        | Clock (3.3V)           |
| 3      | SDA        | Data (3.3V)            |
| 4      | GND        | Ground                 |

### PWM Outputs

| **Channel** | **Signal**   | **Voltage** |
|-------------|--------------|-------------|
| CH1–CH8     | PWM Outputs  | 3.3V Logic  |
| AUX         | PWM/Servo    | Up to 36V   |


# 🔶 **Board Images**

| **Top View** | **Bottom View** |
|--------------|------------------|
| ![Top View](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/Top%20real%20photo.png) | ![Bottom View](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/Buttom%20real%20photo.png) |


# 🛰️ **Drone Testing**

| **Flight Test 1** | **Flight Test 2** |
|------------------|------------------|
| ![Drone Test 1](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/Drone%20test%201.jpg) | ![Drone Test 2](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/Drone%20test%202.jpg) |


# 🧩 **3D & PCB Views**

| **Isometric Top** | **Isometric Bottom** |
|-------------------|----------------------|
| ![Iso Top](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/izometrik%20photo.png) | ![Iso Bottom](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/izometrik%20photo%20buttom.png) |

![PCB View](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/PCB.jpg)

![Board Details](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/otopilot%20details.png)


# 🔶 **Developer Notes**

- Bootloader and firmware flashing supported via DFU and SWD  
- Compatible with MAVLink-based ground control stations (e.g., Mission Planner, QGroundControl)  
- Fully open hardware design, KiCad source files will be released


# 🔶 **FEEDBACK**

If you have any feedback, questions, or feature requests, feel free to contact me at  
📧 [muhammed.elrachidi@gmail.com](mailto:muhammed.elrachidi@gmail.com)


# 🔶 **ABOUT ME**

📡 Embedded Systems, UAV Autonomy & Robotics Engineer  
🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/muhammedrachidi44/)
