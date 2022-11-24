# Experiment--09-Configuring-UART-in-LPC2148-for-serial-data-transmission-

Name :	
Roll no 
Date of experiment :



 Date: 
### Configuring UART in LPC2148 for serial data transmission 

### Aim: 
To configure internal UART for transferring serial data and display it on the Virtual terminal  
Components required: Proteus ISIS professional suite, Kiel μ vision 5 Development environment 
### Theory: 
	The UART Protocol uses only two wires (or pins in a device like microcontroller) to transmit the data. In that, one is for transmitting the data and the pin is called TX pin in the device. The other pin is used to receive the data and is called RX pin.
As UART is a serial communication, the data is transmitted in a series of packets. Usually, a packet consists of 4 parts: a start bit, the actual data, a parity bit and stop bits. The following image shows a typical structure of the data packet in UART.
![image](https://user-images.githubusercontent.com/36288975/203727146-383ce4b4-677b-44c3-bb13-a9e203950760.png)
### FIGURE -01 UART PACKET 


### UART in LPC2148
Coming to UART in LPC2148, the LPC214x series of MCUs have two UART blocks called UART0 and UART1. Each UART block is associated with two pins, one for transmission and the other for receiving.
In UART0 block, the TXD0 (Transmit) and RXD0 (Receive) pins in the device are P0.0 and P0.1 respectively. In case of UART1, the TXD1 and RXD1 pins are P0.8 and P0.9 respectively.
