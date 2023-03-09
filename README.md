# STM32-DHT11

## Project Background

This project is about building a room temperature and humidity detector by using STM32, DHT11 and UART serial communication.  The main purpose of building this project is to help people be aware with the temperature rises in their room where this can be very helpful to avoid wildfires from happening.

This project overall is controlled by a microcontroller named STM32 where this microcontroller is based on the ARM Cortex M processor of 32 bit product range that combines very high performance, real-time capabilities, digital signal processing, and uses low voltage power to operate. 
                               
The DHT11 sensor is ideal for extended temperature and humidity measurement in a variety of communication, environmental, and instrumentation applications. It is a basic, ultra low-cost digital temperature and humidity sensor. It uses a capacitive humidity sensor and a thermistor to measure the surrounding air, and spits out a digital signal on the data pin. The device is specified for operation over a temperature range of 0-50°C and humidity range of 20-80% RH. 
                                 
For the data output, we use asynchronous UART serial communication where the output will be displayed on serial COM in our computer with baud rate of 115200 bits/s. Then, for UART connectivity, both transmitter and receiver were located at PA9 and PA10. In UART communication, the transmitting UART converts parallel data from a controlling device like a CPU into serial form, transmits it in serial to the receiving UART, which then converts the serial data back into parallel data for the receiving devices. Data flows from the Tx pin of the transmitting UART to the Rx pin of the receiving UART.

                          


