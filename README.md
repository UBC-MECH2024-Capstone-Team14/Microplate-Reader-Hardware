# Microplate-Reader-Hardware

This is the hardware subsystem of the [Microplate-Reader](https://github.com/UBC-MECH2024-Capstone-Team14/Microplate-Reader) project.

## LED Driver

The [LED driver](./LED%20Driver/) is a PCB board containing 8 [CN5711](https://www.hestore.hu/prod_getfile.php?id=12002) LED driver ICs. It can control the LED intensities independently through PWM.

## Photodidoe Amplifier

The photodiode amplifier is a circuit to convert photodiode current to voltage for the MCU ADC to sample. We use a photovoltaic circuit built on a breadboard with general-purpose op-amps (MCP6002).

![](https://www.allaboutcircuits.com/uploads/articles/Photovoltaic_and_Photoconductive_Modes_of_Photodiode_Operation_1.png)

## LED & Photodiode PCB

## [TMC5130ABOB](https://www.analog.com/en/resources/evaluation-hardware-and-software/evaluation-boards-kits/tmc5130a-bob.html)

This is the stepper motor driver.

## Power Supply

We selected a [12V wall plug](https://www.amazon.ca/Universal-adapters-Converter-Inverter-Transformer/dp/B08CXND8ZK) for the stepper motor driver and a [DC-DC converter](https://www.amazon.ca/DROK-Waterproof-Converter-Adjustable-Transformer/dp/B00C0KL1OM) to provide 5V for the LED driver.

## Misc

- Breadboard
- Jumper Wires

You may also need a soldering iron to make connections.
