# Bluetooth Status Board

This repository contains documentation and files for a wireless status and leak detection system. The system is intended to be used aboard the Subjugator robot and possibly other future robots as well. Using a microcontroller connected to multiple two-pin sherlocks headers, this status board is able to detect leaks and be programmed via a SWD interface to respond accordingly.

The end goal of this system is to be able to interface with the status of the robot wirelessly via a Bluetooth application.

## Designers

Mehron Talebi

## Major Parts

### Microcontroller

* STM32F042F6P6

### Bluetooth

* RN4871-V/RM140

### Linear Regulator

* BD33KA5WF-E2

## Proposed Changes

- [ ] Replace STM32 MCU with TI TIVA4C
- [ ] Add CAN interface to board
- [ ] Add Mezzanine connector for sherlock header expansion board