# F4xxDiscoveryUART_Echo

Example to use interrupts to receive and transmit chars on UART6 on STM32F4Discovery.
The STM32 HAL function for the UART does not provide a byte-wise access to processing received data. The project created can be used to transmit and receive a block of data(receive reads a block of data untill the new line character \n is received). 
