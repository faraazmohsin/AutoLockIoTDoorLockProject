# AutoLockIoTDoorLockProject

### Servo_control_blynk2.0.ino

Main file that links the blynk application to the ESP32. First part includes the definitions used to connect to the cloud network. The next part of the code includes the servo commands for the servo motor. Commands are provided through the input from the cloud framework. The blynk edgent is a blynk library that manages device connection and communication to the internet.

### Other config files and header files

The remaining files in the folder are configuration files provided from the Blynk library. 

### BlynkEdgent.h

This header file is responsible of managing device connectivity and communicaiton with the internet.

### BlynkState.h

This header file is responsible for checking the state of the Blynk configuration files and the application.

### ConfigMode.h

This header file is responsible for the configuration mode of the application and making sure the overall structure of the application is running through the lifecycle.

### Indicator.h

This header file is responsible for the led indicator and configuration on the ESP32 board.

### OTA.h

This header file is responsible for the over the air configuration of the ESP32 board and connecting to the UI through the internet.

### ResetButton.h

This header file is responsible for possible resetting of the configurations and resetting the ESP32 board.

### Settings.h

This header file is responsible for the settings configuration with the Blynk module and ESP32 board.
