1) Rename files in PCB folder with proper names according to project.
	   Note: Altium project, schematic, and  pcb files should have same name.
	   There are some situations in more complex designs in which this is not the
	   case but for now follow this rule.
	   Example: Template.PcbDoc -> YourProjectName.PcbDoc
				Template.PrjPCB -> YourProjectName.PrjPCB
				Template.SchDoc -> YourProjectName.SchDoc
2) Populate Firmware folder with appropriate CCS/TrueStudio/Etc files.
3) Populate Document folder with appropriate documents files for project.

# Bluetooth Status Board

This repository contains documentation and files for a wireless status and leak detection system. The system is intended to be used aboard the Subjugator robot and possibly other future robots as well. Using a microcontroller connected to multiple two-pin sherlocks headers, this status board is able to detect leaks and be programmed via a SWD interface to respond accordingly.

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