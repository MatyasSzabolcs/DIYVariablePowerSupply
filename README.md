
# DIY Variable Power Supply

A self-built bench power supply capable of delivering either a **fixed 5V output (1A)** or a **user-selectable voltage range from 0V to 22V (up to 3A)**. This project is ideal for electronics prototyping, lab setups, or powering microcontroller-based systems.

## Features

* **Fixed 5V Mode**

  * Stable 5V output
  * Maximum current: 1A
  * Suitable for powering USB devices, logic circuits, or microcontrollers

* **Variable Voltage Mode**

  * Adjustable from 0V to 22V
  * Maximum current: 3A
  * Suitable for analog circuits, motors, and testing power-hungry components

* **Manual Voltage Selection**

  * Potentiometer or rotary encoder-based control (depending on design)
  * Display output via voltmeter (digital or analog)

* **Overcurrent Protection** (optional)

  * Fuse or current-limiting circuitry to protect both power supply and connected devices

## Specifications

| Mode            | Voltage Range | Max Current |
| --------------- | ------------- | ----------- |
| Fixed Output    | 5V            | 1A          |
| Variable Output | 0V – 22V      | 3A          |

## Components (Typical)

* LM317 / LM338 / buck-boost converter modules
* Heat sink and thermal protection
* Toggle switch for mode selection
* Potentiometer for variable output
* Digital voltmeter display
* Power input (e.g., 24V DC adapter or transformer)
* Enclosure (3D printed or repurposed case)

## Safety Notes

* Ensure proper heat dissipation when operating at higher voltages/currents.
* Always check output voltage before connecting sensitive electronics.
* Fuse protection is strongly recommended.

## License

This project is open-source and provided under the [MIT License](LICENSE).

