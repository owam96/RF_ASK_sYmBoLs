# RF_ASK_sYmBoLs
Drivers for FS1000A (433MHz) radio transmitter and receiver modules, which utilize Amplitude Shift Keying, written in assembly.

## Transmitter Module

The code written for the transmitter module assumes a joystick module is connected to the microcontroller. The position of the joystick is encoded into symbols and sent over UART to the receiver module.

Transmitter code is available in the file: RF_ASK_Tx_sYmBoLs_JoyStick

## Receiver Module

The code written for the receiver module assumes a number of LEDs connected to the microcontroller in a certain way. The data received from the transmitter is translated back into its original form and mapped to light a certain LED based on the position of the joystick.

Receiver code is available in the file: RF_ASK_Rx_sYmBoLs_JoyStick
