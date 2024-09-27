## STM32 EEPROM Emulator with State Machine

This application demonstrates how to save and read data from the STM32 EEPROM Emulator. It uses a state machine for debugging purposes, allowing the user to verify if three variables have been successfully saved inside the flash memory. 

- **Read Operation**: When the flash memory is read, LED D2 turns on, indicating the data has been retrieved.
- **Write Operation**: When new values are written to the flash memory, LED D2 turns off.

This project provides a simple and visual way to confirm the functionality of EEPROM emulation on STM32 microcontrollers.

# To test project we need to add 2 variables in debug mode  

![image](https://github.com/user-attachments/assets/9ba38e25-b605-4d10-9b4e-46af59e73149)

# Then change option value to 1 or 2 (write of read) to go inside the state machine 

![image](https://github.com/user-attachments/assets/fca71ecb-69a2-4beb-9055-083c9ea71073)

# While reading VarDataTmp will show curent variable value inside flash memory

![image](https://github.com/user-attachments/assets/d1f7f009-3cf3-4389-b8c2-5c5be337bb32)

# After reading LED turns on and turns off after writing

![image](https://github.com/user-attachments/assets/4bda36ca-83ef-40e4-b457-a3dcc7467f96)


Microcontroller STM32F4VE

Course name: Mastering STM32 microcontrollers

Link: https://www.udemy.com/course/mastering-stm32f407-microcontrollers/
