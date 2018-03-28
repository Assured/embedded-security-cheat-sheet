# Embedded Security Cheat Sheet

Version: 1*10^-99a

TODO: Description

TODO: ToC

## Development

* Development stack
* Development process

## Testing

* Test stack/process

## Firmware

* Updating
* Reverting/downgrading
* Factory reset
* Hardening
* Protection (tampering, forging)
* Libraries
  - mbedtls?
  - libc?
  - versions?

## Hardware

### Microcontrollers

* Model of MCU
* Information stored in MCU
* Security measures in MCU
* Secure enclaves?
* Entropy sources, randomness generators
* HW cryptography support
* Software stack in MCU
  - OS
  - runtime
  - applications

### Memory

* Flash
* EEPROM
* RAM
* External
* What is stored in memory, how and where?

### Interfaces

* JTAG
* Bluetooth
* WiFi
* Ethernet
* UART
* SPI
* I2C
* RS-232
* TTL

* Hardware modules?
* Are interfaces exposed in:
  - Development?
  - Debugging?
  - Production?

## Keys

* Key generation
* Entropy sources
* Certificates/PKI
* Secure storage

## Protocols

* Setup
* Communication protocols
* Management protocols
* Security measures
* CIA
