&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;__Hi there👋__, and welcome to the Snow Light project! 🌟 This project uses a simple hardware circuit to create a magical snowflake light effect, simulating the serene beauty of falling snow. Whether it's for festive decorations or to bring a cosy atmosphere into your home, the Snow Light is guaranteed to make your space feel warm and enchanting! 🎄✨

This isn't just a fun DIY project; it's an exciting experience where you'll build something truly magical with your own hands. Let’s light up the winter season with sparkling lights and a touch of ✨ wonder! 🎇❄️

🌟 Table of Contents 📜
- 💡 Overview
- ✨ Features
- 📐 PCB Design, Circuit Schematic & Physical Build
- 🗂️ BOM (Bill of Materials)
- 🔧 Required Components
- 🛠️ Circuit Design Explanation
- ⚙️ Hardware Assembly
- 🎇 How to Use
  
# Snow Light Project ❄️✨
## Overview:
✨ The Snow Light project is an easy-to-build lighting system that uses RGB LEDs to simulate falling snowflakes. With just a few basic components, you can create a dazzling light display that is perfect for Christmas trees, festive decorations, or simply adding a warm glow to any space. It's a project designed for everyone, no matter your skill level! 🎄🌟

## Features
- 🎇 Magical Light Effects: Simulates falling snowflakes using dynamic LED patterns.
- 🎁 Beginner-Friendly: No programming or advanced tools required, just basic hardware assembly.
- 🔥 Perfect Festive Decor: Add warmth and joy to your holiday setup, lighting up the winter nights.
- 🔌 USB-Powered: Uses a USB Type-C connection for convenient and reliable power.
- 🔧 Customisable: Expand the design with more LEDs or integrate it into other projects for endless creativity. ✨

## PCB Design, Circuit Schematic & Physical Build
### Circuit Schematic
### PCB Layout
### Physical Build

## BOM (Bill of Materials)
| Component | Specification | Quantity |
|-------------------|--------------------|----------|
| USB-Type-C Module | - | 1 |
| AMS117-3.3 | Voltage Regulator | 1 |
| Capacitor | 10uF | 2 |
| Capacitor | 0.1uF | 2 |
| LED | RGB or Single Colour | 6 |
| Resistor | 10Ω | 6 |

## Required Components

## Circuit Design Explanation
### ⚡ Power Supply
- The USB Type-C module provides a steady 5V supply.
- The AMS1117 voltage regulator steps down the 5V to 3.3V, ensuring the LEDs operate within safe limits.
- Capacitors (10µF and 0.1µF) are placed at the input and output of the voltage regulator to stabilise the current and voltage.

### 💡 LED Circuit
- Six LEDs are connected in parallel to the 3.3V output of the regulator.
- Each LED is paired with a current-limiting resistor (330Ω or 470Ω) to prevent damage and ensure uniform brightness.
- You can add more LEDs by following the same setup for a brighter display!

## Hardware Assembly
### Connect the USB Type-C Module
- Connect the VBUS (5V) pin of the USB Type-C module to the VIN pin of the AMS1117 regulator.
- Connect the GND pin of the USB module to the ground of the circuit.
### Set Up the Voltage Regulator
- Solder a 10µF capacitor and a 0.1µF capacitor between the VIN and GND pins of the AMS1117.
- Similarly, solder another 10µF capacitor and a 0.1µF capacitor between the VOUT and GND pins.
- Connect the VOUT pin of the AMS1117 to the positive power rail of your circuit.
### Connect the LEDs
- Solder the anode (positive) of each LED to the 3.3V power rail.
- Solder the cathode (negative) of each LED to one side of its respective resistor.
- Connect the other side of each resistor to the ground rail.

Once connected, you’ll have a snowflake lighting system ready to shine! 🌟✨

## How to Use
- Power it up: Plug the USB Type-C connector into a power source (USB adaptor, power bank, or laptop).
- Enjoy the magic: Watch the LEDs light up in a snowflake pattern, filling your space with a cosy glow.
- Get creative: Adjust the number, colour, or arrangement of LEDs to customise your Snow Light.
- Festive Tip: Attach your Snow Light to a Christmas tree or hang it on a wall for an enchanting holiday effect! 🎄✨




