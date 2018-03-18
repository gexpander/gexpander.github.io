## GEX

*This project is still under development, please check back in a couple months!*

![photo](photo.jpg?x)

GEX is [MightyPork](https://www.ondrovo.com/)'s hobby project developed for his 
electrical engineering master's thesis. The project is and will remain open source.

There *may* be a way for you to order a GEX board in the future. However, for now, there are just a few experimental prototypes.

### What is GEX

Probably everyone working with embedded electronics got at some point enough of writing 
single purpose firmwares just to try something out. As a result, there are certainly dozens 
of projects like this, universal GPIO tools that attach to the computer.

GEX is not the first and most certainly not the last such tool. What sets it aside?
Well, ... it's not finished yet, but when it is, it'll be very powerful and flexible. Here are some key points:

- Python and C library (planned MATLAB)
- LibUSB or Virtual Comport access
- Cross-platform support (thanks to PyUSB)
- Well documented protocol (um.. TODO)
- Wireless connection (planned) using a dongle or WiFi
- Microsecond-accurate event timestamps
- DFU firmware upload
- Virtual FAT16 filesystem (mass storage) with INI config files
- FreeRTOS core
- *Wide range of supported protocols, buses and features*
  - SPI
  - I2C
  - UART,USART
  - 1-Wire
  - NeoPixel
  - Touch sensing
  - ADC with oscilloscope-like features
  - DAC with DDS waveform synthesis
  - PWM generation
  - Frequency and pulse measurement
  - Raw GPIO input, output 
  - GPIO pulse output
  - GPIO pin change events

GEX is powerful. It's also large, could be a bit faster, and needs more documentation.

I'm working on it :o)

### Learn more

Here are some resources:

- [Hardware](https://github.com/gexpander/gex-hardware)
- [STM32F072 port source code](https://github.com/gexpander/gex-f072)
- [Python client](https://github.com/gexpander/gex-client-py)

Documentation and the Wireless functionality will be published when it's ready.

See [github.com/gexpander](https://github.com/gexpander) for other repositories
