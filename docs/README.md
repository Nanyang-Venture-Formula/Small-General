# Overview

The Small General is a STM32 based development board that boast a 48MHz Cortex-M0 STM32F072 Microcontroller and breaks out interfaces that a user would usually use when prototyping or for use in small spaces.


### Quick Links

- [Renders](./Renders.md)

## Form Factor

The Small General is 50mm x 80mm in size. 

There are 4 x M4 screw holes (padded top and bottom; connected to ground) that are 6mm x 6mm from the corners of the boards 50mm x 80mm dimensions.

There are 3mm fillets at all 4 corners of the board.

## Features

1. STM32F072CBT6 Microcontroller.
2. USB C (Power & Data)
3. Integrated CanBus. (Multiple Connections)
4. Dual Voltage Regulators for stable 3.3V and 5V supply ( $V_{MAX}$: 20V)
5. Dual trim potentiometers to scale down analog signals before processing + easily accessible testpoints to probe using multimeters.
6. NRST, BOOT0 buttons
7. LED Indicators for 3v3 Power, 5v power
8. Programmble User button and LED


## 5 Pin Connectors:

| Interface      | Pin A        | Pin B        |
| -------------- | ------------ | ------------ |
| ADC            | PA0 (A0)     | PA1 (A1)     |
| UART (UART2)   | PA2 (TX)     | PA3 (RX)     |
| I2C            | PB6 (SCL)    | PB7 (SDA)    |
| SW Debug (SWD) | PA13 (SWDIO) | PA14 (SWCLK) |

Compatible connectors (01x05 Styled - 2.00mm)

- JST PH S5B [Horizontal] (Refer to Parts)
- JST PH B5B [Vertical] (Refer to Parts)

### 8 Pin Connectors:
