# ESP32CAM-Picture-to-Telegram-Assignment


```markdown
## Momodou Jammeh : NOTES FOR CSN150

### Purpose:
The purpose of this project was to configure an ESP32-CAM to capture and send photos through Telegram using a Telegram Bot and Wi-Fi connection. This project demonstrates IoT communication, camera integration, and remote monitoring capabilities.

### Equipment Used:
- ESP32-CAM (AI-Thinker)
- FTDI Programmer / USB-to-Serial Adapter
- USB Cable
- Computer or Laptop
- Wi-Fi Network

### Tools Used:
- Arduino IDE
- Telegram App
- GitHub
- GPTx / ChatGPT
- Serial Monitor
- Random Nerd Tutorials Documentation

### Steps I Followed:
1. Created a new GitHub repository for the project documentation.
2. Installed the ESP32 board package in Arduino IDE.
3. Connected the ESP32-CAM to the FTDI programmer and computer.
4. Created a Telegram Bot using BotFather in Telegram.
5. Copied the Bot Token and Chat ID into the Arduino sketch.
6. Configured the Wi-Fi SSID and password in the code.
7. Selected the AI-Thinker ESP32-CAM board in Arduino IDE.
8. Uploaded the sketch to the ESP32-CAM.
9. Opened the Serial Monitor and confirmed the ESP32 connected to Wi-Fi.
10. Tested the Telegram Bot by sending commands and receiving photos from the ESP32-CAM.
11. Added screenshots and updated the README documentation on GitHub.

### Problems / Solutions:
One problem I experienced was upload failures caused by incorrect wiring and board settings. I solved this by reconnecting the GPIO0 pin correctly, selecting the proper COM port, and pressing the reset button during upload. Another issue was Telegram not sending images initially, which was fixed by verifying the Bot Token and Chat ID.

### Final Report:
This project successfully demonstrated how an ESP32-CAM can integrate with Telegram to provide remote image capture and notifications over Wi-Fi. The project improved my understanding of IoT devices, Arduino programming, wireless networking, and GitHub documentation practices. The final setup allowed the ESP32-CAM to capture and send photos directly to Telegram through a custom bot.
```
