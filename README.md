# Smart-GreenHouse---Group-8
IOT102 - IA_20001
Smart Greenhouse System - Group 8
An automated Microclimate Management System designed and simulated for the IOT102 Course (Progress Test 1) at FPT University.
📌 Project Overview
This project presents an automated, reactive climate control system designed for indoor agricultural applications. By combining three sensors (Inputs) and three actuators/displays (Outputs), the system maintains optimal plant growth conditions without requiring constant manual supervision.
🛠️ Hardware & Components (Simulation)
Microcontroller: Arduino Uno R3 (acting as simulation twin)
Inputs (Sensors):
TMP36: For atmospheric temperature tracking
Photoresistor (LDR): For ambient light intensity measurement
Gas Sensor (MQ-2): For carbon dioxide / air quality monitoring
Outputs (Actuators):
LiquidCrystal LCD (16x2 Parallel): Real-time on-site telemetry display
DC Motor: Simulates the microclimatic extraction fan
Light Bulb: Simulates supplemental photosynthetic LED grow lights
Piezo Buzzer & Red LED: Local auditory and visual hazard alarms
⚙️ Automated Threshold Logic
Light Regulation: Actuates the supplemental Grow Light when ambient light falls below the safe photosynthetic limit ($Light < 500$ raw ADC units).
Climate & Air Quality Safety: Triggers the Extraction Fan when the internal temperature exceeds $22.0^\circ\text{C}$.
Hazard Alert: Sounds the Piezo buzzer and activates the warning LED when gas levels accumulate above safe thresholds ($Gas > 400$ raw ADC units).
👥 Team Members & Roles
Phạm Mai Huy (Hardware Specialist): Physical hardware integration and empirical board validation.

Nguyễn Quang Hiếu Liêm (Simulation Engineer): Tinkercad simulation schematic mapping and circuit validation.

Nguyễn Thái Tài (System Architect): Architectural system block definition and project workflow design.

MNguyễn Hoàng Tuấn (Technical Writer): Technical report compilation and documentation synchronization.
