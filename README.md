# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1919" height="1199" alt="Screenshot 2026-03-18 125047" src="https://github.com/user-attachments/assets/8880345f-22a9-43ab-a4c4-f0127b1398ae" />
### 2. Network Server – Recent Events
<img width="1919" height="1196" alt="Screenshot 2026-03-18 125018" src="https://github.com/user-attachments/assets/8fca38e1-3755-4993-a629-d628f527d927" />
### 3. Dashboard Command Sending
<img width="1918" height="1189" alt="image" src="https://github.com/user-attachments/assets/280eefc5-048e-41f4-b77e-ea2a9e879da4" />

### 4. Relay Status Dashboard Output
<img width="1917" height="1190" alt="image" src="https://github.com/user-attachments/assets/94c5f32f-03af-4d0d-b3da-f68d7419df2b" />
### Bulb ON → Relay ON 
<img width="1919" height="1193" alt="Screenshot 2026-03-18 124919" src="https://github.com/user-attachments/assets/617e7ca5-4877-45fa-a11f-ae69edbf3b52" />

### Bulb OFF → Relay OFF
<img width="1913" height="1187" alt="Screenshot 2026-03-18 125154" src="https://github.com/user-attachments/assets/cb165cf0-f45e-4d4d-bf80-057100b359e4" />
## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
