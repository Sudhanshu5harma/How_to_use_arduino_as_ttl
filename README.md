# How_to_use_arduino_as_ttl
If you doesn't have TTL (Transistor-Transistor Logic) USB and want to do Rx-Tx transmission. Don't worry you can use us arduino.  


### How can you use your Arduino as USB TTL logic ?
From simple hardware modification you can use your Arduino as USB TTL and get the Rx-Tx transmission done so to do this make the connection as show -  
1. Connect your reset pin to ground pin.  
2. Connect the desire sensor pins RX to RX of arduino and TX to TX of arduino.  
3. Connect the pin VCC to VCC of arduino and GND to GND of arduino.  
![alt text](https://cdn.sparkfun.com/assets/9/1/e/4/8/515b4656ce395f8a38000000.png)  
Now open your Serial Monitor of arduino ide and select the port you have connected your arduino to. Your can either use putty software to run the command and check the sensor. 

### Why is it useful ?
Sometime we have to just check the sensor weather its working or not so this can be done. You can use AT command without writing the code for it in arduino ide.   
like - 

![alt text](http://www.vcc2gnd.com/pic/SIM800L-Module_PinOut_Connection-Wiring-Diagram.png)  

Now you don't need to buy TTL if you have arduino and few Jumper cables. 

### Why we use USB-TTL ?
The USB TTL Serial cables are a range of USB to serial converter cables which provide connectivity between USB and serial UART interfaces.  A range of cables are available offering connectivity at 5V, 3.3V or user specified signal levels with various connector interfaces.   

All cables feature an FTDI FT232R device integrated within the cable USB type ‘A’ connector, which provide access to UART Transmit (Tx), Receive (Rx), RTS#, CTS#, VCC (5V) and GND connections.  All cables are fully RoHS compliant and are FCC/CE approved.   
