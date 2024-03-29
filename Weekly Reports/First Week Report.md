# Week 1 Report

## Tasks and Progress Status

### 1. Research
- Detailed research was conducted on MicroPython, Pico LTE, and Raspberry Pi Pico W, and notes were taken. (The notes can be found at the bottom of this report.)

### 2. Installations
- Thonny was installed for coding with MicroPython.
- MicroPython was installed on the Raspberry Pi Pico W.
- The SDK was cloned from the GitHub repository, and the Pico LTE SDK installation was completed.
- To test if everything was working properly, sample code was executed.
- The SIM card has been successfully registered and activated on connect.sixfab.com.

### References

- [Thonny IDE](https://thonny.org/)
- [Raspberry Pi Pico Product Page](https://www.raspberrypi.com/products/raspberry-pi-pico/)
- [Pico LTE Documentation](https://docs.sixfab.com/docs/sixfab-pico-lte-documentation)
- [Pico LTE MicroPython SDK on GitHub](https://github.com/sixfab/pico_lte_micropython-sdk)
- [MicroPython Official Website](https://micropython.org/)
- [MicroPython on Raspberry Pi Pico](https://www.raspberrypi.com/documentation/microcontrollers/micropython.html)


---

## Raspberry Pi Pico

The Raspberry Pi Pico is a cost-effective microcontroller. It is high-performing, low-cost, and easy to program, making it a choice for IoT (Internet of Things) applications. It possesses features such as GPIO pins, analog inputs, I2C, SPI, which makes it suitable for integrating various sensors and devices into projects. The Raspberry Pi Pico can be programmed with MicroPython and C language support.

![Raspberry Pi Pico](https://market.samm.com/raspberry-pi-pico-raspberry-pi-modeller-raspberry-pi-2607-10-B.jpg)

## Pico LTE

The Pico LTE is an IoT development board that integrates with Raspberry Pi Pico W, containing a Quectel BG95-M3 modem. It offers global LTE-M connectivity, enabling users to develop devices and applications with cellular connectivity using the Raspberry Pi ecosystem.


-  The embedded SIM simplifies connectivity to cellular networks without the need for external SIM cards.
-  Supports various IoT platforms and services like AWS IoT, Azure IoT, Telegram API, ThingSpeak, and more.
-  Offers a GNSS solution supporting various satellite systems.

![Pico LTE](https://m.media-amazon.com/images/I/71+ReKrpytL.jpg)

## What is MicroPython?

MicroPython is an optimized version of the Python programming    language that brings the power and flexibility of Python to hardware-focused projects and devices with low processing power and memory capacity. It's designed for embedded systems like microcontrollers and can be programmed using Thonny IDE.

### Differences Between MicroPython and Standard Python

- **Resource Usage:** MicroPython is much more efficient in terms of memory and processor usage. This allows it to operate on devices with limited resources.
- **Libraries and Modules:** MicroPython does not include many of the standard Python libraries. Instead, it has specialized modules focused on functionality commonly used in embedded systems.


## Key Terms
- **GNSS:** A network of satellites providing global positioning and timing information.
- **I2C (Inter-Integrated Circuit):** A serial data communication protocol. Allows multiple integrated circuits to communicate with each other at low speeds.
- **SPI (Serial Peripheral Interface):** A protocol used for high-speed serial data communication. Facilitates data exchange between microcontrollers and peripherals like sensors and memory cards.
- **IoT (Internet of Things):** A concept that enables devices, vehicles, and other objects to exchange data over the internet.
- **GPIO (General Purpose Input/Output):** Pins found in microcontrollers that facilitate communication with various devices (LEDs, buttons, sensors, etc.) through digital signals.
- **Microcontrollers:** Small, integrated circuits; combine a processor, memory, and input/output ports on a single chip. Found in a wide range of applications such as smart devices, home appliances, vehicles, and medical devices. Preferred for their low power consumption, compact size, and flexible programming capabilities.
- **LTE-M (CAT-M1):** A cellular network technology with low power consumption and wide coverage area. Ideal for IoT devices, offering long battery life.
- **GPRS:** An older cellular technology providing data transmission in 2G and 3G networks. Used for low-speed internet access.
