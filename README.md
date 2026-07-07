
ADAS-Dashboard 🚗⚡

Real-time Electric Vehicle Dashboard using *STM32F103C8T6 Blue Pill* + *Python*

📌 About
This project reads sensor data from an STM32 microcontroller and displays it on a Python dashboard.
It shows live Battery %, Light/Front sensor data, and estimated range for an EV prototype.

✨ Features
- *UART Serial Communication* between STM32 and PC
- *Live Dashboard* with Battery, Light Sensor, Range
- *STM32CubeIDE Project* with HAL drivers
- *Cross-platform Python GUI*

🛠️ Hardware Requirements
- STM32F103C8T6 Blue Pill
- ST-Link / USB to UART
- Light Sensor, Battery Voltage Sensor

💻 Software Requirements
```bash
pip install pyserial


▶️ How to Run
1. Open ev_dash.ioc in STM32CubeIDE and flash the code to Blue Pill
2. Connect STM32 to PC via USB
3. Check your COM port in Device Manager. Example: COM1
4. Run the dashboard:
python ev_dashboard.py --port COM1


📁 Project Structure
ev_dashboard.py   # Python dashboard GUI
ev_dash.ioc       # STM32CubeIDE configuration
Core/             # Main application code
Drivers/          # STM32 HAL drivers



👩‍💻 Author
@saiamritakoduri-lab
