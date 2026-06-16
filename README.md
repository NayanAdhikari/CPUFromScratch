- Inspired by Ben Eater, and built by me with revisions. (See below).
- Thank you so much Ben Eater, https://www.youtube.com/@BenEater

#  CPU Emulator

A 6502-inspired 8-bit CPU emulator written in C++ to explore computer architecture concepts including memory management, instruction decoding, register operations, and the fetch-decode-execute cycle. I added a couple quirks to this.

#  Following Will Be Included

- Schematics
- Architecture diagrams
- Timing diagrams
- Instruction set documentation
- Build logs
- Failure analysis

## Features

- 64 KB memory model
- A, X, Y, SP, and PC registers
- Status flags
- Opcode execution engine
- Extensible instruction set

## Architecture

The emulator consists of:
- CPU class
- Memory class
- Opcode decoder
- Execution engine

## Supported Instructions

| Opcode | Mnemonic | Description |
|----------|----------|----------|
| 0xA9 | LDA | Load Accumulator |
| 0xAA | TAX | Transfer A to X |
| 0xE8 | INX | Increment X |
| 0x00 | BRK | Stop Execution |
