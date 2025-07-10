# SPI_Master_Controller_in_Verilog

#OVERVIEW
This project implements a simple SPI (Serial Peripheral Interface) master controller using Verilog HDL. The module supports 8-bit data transmission over the MOSI line and generates a 10 MHz SPI clock from a 100 MHz system clock. It includes a finite state machine (FSM) with clear state transitions, controlled data loading, and a done_send flag to signal the end of transmission.
