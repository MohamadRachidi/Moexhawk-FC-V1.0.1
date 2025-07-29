  # 📢 **MOEXHAWK-FC V1.0.1**

The **MOEXHAWK-FC V1.0.1** is a fully custom-designed, compact, and reliable **Flight Controller (FC)** solution tailored for UAV and robotics applications.  
It integrates essential flight control hardware, high-performance sensors, and a wide array of I/O interfaces in a single board.

![render](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/moexhawk-fc-render.jpg)


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
| **Compact Size**           | Small form factor PCB optimized for tight integration       |
| **Wide Compatibility**     | Compatible with ArduPilot, Betaflight, iNav, and PX4        |

---

# 🔶 **Supported Firmwares**

## [**ArduPilot**](https://firmware.ardupilot.org/Copter/)
- Version Requirement: `4.3.0` and later
- ✅ Tested

## [**Betaflight**](https://github.com/betaflight/betaflight/releases)
- Version Requirement: `4.4.x` and later
- ✅ Tested

## [**iNav**](https://github.com/iNavFlight/inav/releases)
- Version Requirement: `6.x` and later
- ❌ Not Tested Yet

## [**PX4**](https://github.com/PX4/PX4-Autopilot/releases)
- Version Requirement: `1.13.1` and newer
- ❌ Not Tested Yet

---

# 🔶 **Test Status**

## Firmware Testing

| **Software**           | **Status**       |
|------------------------|------------------|
| **ArduPilot**          | ✅ Tested         |
| **Betaflight**         | ✅ Tested         |
| **iNav**               | ❌ Not Tested Yet |
| **PX4**                | ❌ Not Tested Yet |

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

---

# 🔶 **Board Image & Dimensions**

![Board Top View](https://github.com/MohamadRachidi/Moexhawk-FC/blob/main/images/moexhawk-fc-top.jpg)

📏 *Dimensions*: 55mm x 55mm  
🔩 *Mounting Holes*: Standard 30.5mm x 30.5mm M3 spacing


# 🔶 **Developer Notes**

- Bootloader and firmware flashing supported via DFU and SWD
- Compatible with MAVLink-based ground control stations (e.g., Mission Planner, QGroundControl)
- Fully open hardware design, KiCad source files will be released

# 🔶 **FEEDBACK**
If you have any feedback, please reach out to me at [muhammed.elrachidi@gmail.com](mailto:muhammed.elrachidi@gmail.com)

# 🔶 **ABOUT ME**
Connect with me on [LinkedIn](https://www.linkedin.com/in/muhammedrachidi44/)



