# IoTbasedLockV2.0

🔴 Project Name : IoT based Smart Lock V2.0

<br  />

📷 About Project -  

🚩   In this project we've build IoT based smart lock which have 4 layers of access. RFID + PIN + Fingerprint + OTP.  

🚩   We have slightly upgraded our previous version of the project. In this version we are going to add one more accessibility layer. That is biometric, means, we will add fingerprint based authentication.  

🚩   Also we are going to use different MCU development Board. In version 1 we have used Particle Photon Board, but in this project we will use ESP32 development board.  

🚩   So now, if user want to unlock this lock, then he or she should have Valid RFID, Fingerprint, PIN and OTP, means one time password.  

🚩   Also we have programmed this lock system to keep record data of user entries with user name and timestamp. This data will recorded on our dedicated my S.Q.L database which is hosted on our webserver, hence the system Administrator can login to that web portal and, keep track of how many time this lock got opened.  

🚩   Nextion Touchscreen HMI Display is used for interacting with this door lock.  

<br  />

📜 Parts Required  

1. NodeMCU ESP32 Development Board  
2. RC522 RFID Reader Module  
3. FPM10A Fingerprint Sensor  
4. 3.5" Nextion Touchscreen HMI Display  
5. MB102 Breadboard Power Supply module  
6. 12V Solenoid Lock  
7. 2 Channel Relay Board 5V    
8. Batteries - 7.4V LiPo, 11.1V LiPo and Power Bank.  

<br  />

🌐 YouTube Video Links -  

IoT based smart Lock V2.0    ▶️  [https://youtu.be/X8uOJ63XOb8]  

<br  />

||==========================================================================||  
🔗 *Important Links* 🔗  

⏩  Info about Telegram Bots  -  https://core.telegram.org/bots  

⏩  About Nextion Display and Download IDE -  https://nextion.tech/   

<br  />
How to Create Telegram Bot ?    ⏩  https://youtu.be/bmerNhPUTBg?t=498  
<br  />
How to Get your Telegram User ID ?        ⏩  https://youtu.be/bmerNhPUTBg?t=626  

||==========================================================================||

Libraries Used  
  
📕  MFRC RC5222 RFID Library  -  Arduino IDE Library Manager  

📕  Fingerprint Sensor Library - Arduino IDE Library Manager  

📕  Universal Telegram BOT Library  - Arduino IDE Library Manager  

📕  NTP Client Library  - Arduino IDE Library Manager  

📕  Nextion Display Library  -  https://github.com/itead/ITEADLIB_Arduino_Nextion  