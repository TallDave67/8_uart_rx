# Embedded Systems Bare-Metal Programming Ground Up™ (STM32): Program 8

[Code Development follows this Udemy Course](https://www.udemy.com/course/embedded-systems-bare-metal-programming/)

## Specs

Host

* MS Windows 10.0.19042
* STM32CubeIDE 1.8.0
* RealTerm 2.0.0.70

Device

* STM32F401RE chip
* STM32 Nucleo-64 development board

## Description

This program combines two main areas of focus:

* Toggling the LED
* UART2 communication

The program running on the device does the following:

* Reads one character at a time from the UART2 RX pin
* If the character is '1' the LED is turned on, otherwise it is turned off

RealTerm tool running on host sends characters to the board.

## Output

Screenshot of Host

![RealTerm writes to STM32F4](Output/realterm-to-stm32f4.png)

Video of Test

![LED changes on STM32F4 based on input character](Output/realterm-to-stm32f4.mp4)

