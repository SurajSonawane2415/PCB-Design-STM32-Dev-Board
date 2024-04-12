# STM32 Development Board

This is a custom STM32 Development PCB Board with an on-board SPI sensor (TC72).

![image](https://github.com/SurajSonawane2415/PCB-Design-STM32-Dev-Board/assets/129578177/08fd48e2-5ccf-4f22-9114-4b370c6056a7)

## Board Images

- **Frontend**
  
  ![image](https://github.com/SurajSonawane2415/PCB-Design-STM32-Dev-Board/assets/129578177/f0a5b9c0-0448-4cc4-b0ae-8044c735b295)

- **Backside**
  
  ![image](https://github.com/SurajSonawane2415/PCB-Design-STM32-Dev-Board/assets/129578177/a59e3fe3-b131-40bd-911d-e44cd0f685b9)

## About the Project

## Getting Started with a Development Board

### STM32F103C8

![image](https://github.com/SurajSonawane2415/PCB-Design-STM32-Dev-Board/assets/129578177/9a162c95-c18c-49b2-8a81-cb04fac642ee)

- The STM32F103xx medium-density performance line family incorporates the high-performance Arm® Cortex®-M3 32-bit RISC core operating at a 72 MHz frequency, high-speed embedded memories (Flash memory up to 128 Kbytes and SRAM up to 20 Kbytes), and an extensive range of enhanced I/Os and peripherals connected to two APB buses. All devices offer two 12-bit ADCs, three general-purpose 16-bit timers plus one PWM timer, as well as standard and advanced communication interfaces: up to two I2Cs and SPIs, three USARTs, a USB, and a CAN.
- The devices operate from a 2.0 to 3.6 V power supply. They are available in both the –40 to +85°C temperature range and the –40 to +105 °C extended temperature range. A comprehensive set of power-saving mode allows the design of low-power applications. The STM32F103xx medium-density performance line family includes devices in six different package types: from 36 pins to 100 pins. Depending on the device chosen, different sets of peripherals are included, the description below gives an overview of the complete range of peripherals proposed in this family.
- These features make the STM32F103xx medium-density performance line microcontroller family suitable for a wide range of applications such as motor drives, application control, medical and handheld equipment, PC and gaming peripherals, GPS platforms, industrial applications, PLCs, inverters, printers, scanners, alarm systems, video intercoms, and HVACs.

### I²C Bus

![image](https://github.com/SurajSonawane2415/PCB-Design-STM32-Dev-Board/assets/129578177/1fabcc85-4bef-471a-9051-11e9fff73a8e)

- I2C communication is the short form for inter-integrated circuits. It is a communication protocol developed by Philips Semiconductors for the transfer of data between a central processor and multiple ICs on the same circuit board using just two common wires.
- Up to two I²C bus interfaces can operate in multimaster and slave modes. They can support standard and fast modes. They support dual slave addressing (7-bit only) and both 7/10-bit addressing in master mode. A hardware CRC generation/verification is embedded.
- They can be served by DMA and they support SM Bus 2.0/PM Bus.
- The I2C Communication starts when the master initiates the START condition, where the SDA line goes from HIGH to LOW while the SCL line in HIGH. This is followed by a 7-bit slave address and a single bit indicating a read (‘1’) operation or a write (‘0’) operation.

 ### Universal Synchronous/Asynchronous Receiver Transmitter (USART)

![image](https://github.com/SurajSonawane2415/PCB-Design-STM32-Dev-Board/assets/129578177/9a162c95-c18c-49b2-8a81-cb04fac642ee)

- The universal synchronous asynchronous receiver transmitter (USART) offers a flexible means of full-duplex data exchange with external equipment requiring an industry-standard NRZ (Non-Return-To-Zero) asynchronous serial data format. The USART offers a very wide range of baud rates using a fractional baud rate generator. It supports synchronous one-way communication and half-duplex single-wire communication. It also supports the LIN (local interconnection network), Smartcard Protocol and IrDA (infrared data association) SIR ENDEC specifications, and modem operations (CTS/RTS). It allows multiprocessor communication. High-speed data communication is possible by using the DMA for multi-buffer configuration.
- One of the USART interfaces is able to communicate at speeds of up to 4.5 Mbit/s. The other available interfaces communicate at up to 2.25 Mbit/s. They provide hardware management of the CTS and RTS signals, IrDA SIR ENDEC support, are ISO 7816 compliant and have LIN Master/Slave capability. All USART interfaces can be served by the DMA controller.

### Serial Peripheral Interface (SPI)

![image](https://github.com/SurajSonawane2415/PCB-Design-STM32-Dev-Board/assets/129578177/6c4faa2c-30e7-4af2-bc7f-a2ca9808b7b8)

- Serial Peripheral Interface or SPI is a synchronous serial communication protocol that provides full – duplex communication at very high speeds. Serial Peripheral Interface (SPI) is a master – slave type protocol that provides a simple and low-cost interface between a microcontroller and its peripherals.
- Up to two SPIs are able to communicate up to 18 Mbits/s in slave and master modes in full-duplex and simplex communication modes. The 3-bit prescaler gives 8 master mode frequencies and the frame is configurable to 8 bits or 16 bits. The hardware CRC generation/verification supports basic SD Card/MMC modes.
- Both SPIs can be served by the DMA controller.

## Contributor

- [Purva Yeshi](https://github.com/PurviSYeshi)
- [Suraj Sonawane](https://github.com/SurajSonawane2415)

## Acknowledgements and Resources

- [Vishwa VITI](https://vishwaspace.github.io/vishwa-web/) for providing us with required resources and Special thanks to my mentor [Karteek Nayak](https://github.com/Karteek-N) and all the seniors at Vishwa, VJTI for their constant support and guidance throughout the project.
- [KiCAD Tutorials](https://www.youtube.com/playlist?list=PL3bNyZYHcRSUhUXUt51W6nKvxx2ORvUQB)
- [STM32F103C8 Datasheet](https://www.st.com/resource/en/datasheet/stm32f103c8.pdf)

## License

[MIT License](https://opensource.org/license/mit)
