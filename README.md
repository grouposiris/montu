<h2> montu: SPI to UART Bridge IP Core </h2>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

<p align="center">
  <img src="docs/images/results/montu_logo.png" width=250 alt="Montu IP logo">
</p>

## Introduction

Montu is a high-performance **SPI-to-UART bridge IP core** designed to provide seamless communication between SPI-based controllers and UART-enabled devices. Serving as a protocol translator, Montu accepts data and control information over the Serial Peripheral Interface (SPI) and transmits or receives it via a standard Universal Asynchronous Receiver-Transmitter (UART) interface.

This IP core is ideal for embedded systems where SPI hosts need to interact with serial devices such as GPS modules, Bluetooth transceivers, modems, or legacy serial equipment without adding dedicated UART hardware to the system.

Key features of Montu include:
- **Full-Duplex SPI Interface:** Operates in master or slave mode for flexible system integration.
- **UART Protocol Support:** Translates SPI commands into standard UART TX/RX operations.
- **Configurable Baud Rates:** Supports a wide range of baud rates for compatibility with various devices.
- **Configurable SPI Modes:** Compatible with all four SPI clock polarity (CPOL) and phase (CPHA) configurations.
- **FIFO Buffers:** Separate transmit and receive FIFOs for smooth data handling and reduced latency.
- **Low Latency Translation:** Optimized for quick turnaround between SPI commands and UART transmission.
- **Flow Control Support:** Optional hardware (RTS/CTS) or software (XON/XOFF) flow control.
- **Error Handling:** Detects framing errors, parity errors, and buffer overruns.
- **Interrupt Support:** Event-driven signaling for data availability, transmission completion, and error conditions.

Montu comes with a robust verification suite to validate its performance and correctness across multiple configurations.  
It is designed for FPGA and ASIC implementations, enabling reliable bridging between high-speed SPI interfaces and versatile UART communication.

Refer to the [documentation](docs/) for integration guidelines, configuration options, and simulation examples.
